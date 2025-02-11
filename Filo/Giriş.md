Flet Nedir Flet, ön yüz geliştirme konusunda önceden deneyim sahibi olmadan Python'da web, masaüstü ve mobil uygulamalar oluşturmanıza olanak tanıyan bir çerçevedir.

Google'ın Flutter'ına dayanan Flet kontrolleriyle programınız için bir kullanıcı arayüzü oluşturabilirsiniz. Flet, Flutter widget'larını sarmanın ötesine geçer. Daha küçük widget'ları birleştirerek, karmaşıklıkları basitleştirerek, kullanıcı arayüzü en iyi uygulamalarını uygulayarak ve mantıklı varsayılanları uygulayarak kendi dokunuşunu ekler. Bu, uygulamalarınızın sizden ek tasarım çabaları gerektirmeden şık ve cilalı görünmesini sağlar.

Flet uygulama Örnek bir "Sayaç" uygulaması oluşturun:

karşı.py

```python
import flet as ft

def main(page: ft.Page):
    page.title = "Flet counter example"
    page.vertical_alignment = ft.MainAxisAlignment.CENTER

    txt_number = filo.Metin_Alanı(value="0", text_align=ft.TextAlign.RIGHT, width=100)

    def minus_click(e):
        txt_number.value = str(int(txt_number.value) - 1)
        page.update()

    def plus_click(e):
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

