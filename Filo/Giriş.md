Flet Nedir Flet, ön yüz geliştirme konusunda önceden deneyim sahibi olmadan Python'da web, masaüstü ve mobil uygulamalar oluşturmanıza olanak tanıyan bir çerçevedir.

Google'ın Flutter'ına dayanan Flet kontrolleriyle programınız için bir kullanıcı arayüzü oluşturabilirsiniz. Flet, Flutter widget'larını sarmanın ötesine geçer. Daha küçük widget'ları birleştirerek, karmaşıklıkları basitleştirerek, kullanıcı arayüzü en iyi uygulamalarını uygulayarak ve mantıklı varsayılanları uygulayarak kendi dokunuşunu ekler. Bu, uygulamalarınızın sizden ek tasarım çabaları gerektirmeden şık ve cilalı görünmesini sağlar.

Flet uygulama Örnek bir "Sayaç" uygulaması oluşturun:

karşı.py

```python
Filo kütühanesini yükle

fonksiyon main(sayfa: Filo.):
    sayfa.title = "Flet counter example"
    sayfa.Dikey_Hizalama =filo.Ana_Eksen_Hizalaması.MERKEZ

    txt_number = filo.Metin_Alanı(Değer="0", Metin_Hizalama=filo.Metin_Hizalama.RİGHT, Genişlik=100)

    fonksiyon eksi_tıklama(e):
        metin_Sayı.değer = metin(tam_sayı(metin_sayı.değer) - 1)
        sayfa.güncelleme()

    fonksiyon artı_tıklama(e):
        txt_number.value = str(int(txt_number.value) + 1)
        page.update()

    page.add(
        ft.Row(
            [
                ft.IconButton(ft.Icons.REMOVE, on_click=minus_click),
                txt_number,
                ft.IconButton(ft.Icons.ADD, on_click=plus_click),
            ],
            alignment=ft.MainAxisAlignment.CENTER,
        )
    )

ft.app(main)
```

