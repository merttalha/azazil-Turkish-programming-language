# Azazil

![Azazil Icon](https://github.com/user-attachments/assets/da75c13d-6a80-494a-8720-613570692d8f)

Azazil, hızlı bir şekilde çalışmanıza olanak sağlayan Türkçe bir programlama dilidir ve sistemlerinizi daha etkili bir şekilde entegre etmenizi sağlar.

Resmi site: [azazil.fly.dev](https://azazil.fly.dev)


İndirme Linki: [İndir](https://drive.google.com/file/d/111i7vmX7-4ARtOCS79EJC9TJN6cy0XoI/view?usp=sharing)

## Hakkında

Azazil, arka planda Python kullanan Türkçe bir yazılım dilidir. Temel Python özellikleri Türkçe bir yapıda sunarak, yazılım geliştiricilere ana dillerinde kod yazmayı sağlar. Azazil, hızlı çıkış alma seçeneği ile öne çıkar. Geliştirilen yazılımlar kolayca çalıştırılabilir ve tek bir tuşla `.exe` dosyası alınabilir. Bu sayede hem öğrenme süreci hızlanır hem de pratik bir geliştirme deneyimi sunar. Karmaşık yapıları basitleştiren ve Türkçe bir alternatif sunan Azazil, yazılım dünyasında özgün bir yere sahiptir.

## Özellikler

- **Türkçe Kodlama:** Azazil, Python'un güçlü altyapısını kullanarak Türkçe bir yazılım dili sunar.
- **Kolay Kullanım:** Türkçe komutlarla hızlı bir şekilde yazılım geliştirme imkanı sağlar.
- **.exe Desteği:** Geliştirilen yazılımlar tek tuşla çalıştırılabilir `.exe` dosyalarına dönüştürülebilir.
- **Eğitim Dostu:** Öğrenmeyi kolaylaştırır ve yazılım dünyasına yeni başlayanlar için idealdir.

## Örnek Kullanım

### Yazdırma İşlemi

Bir mesaj veya değişkeni ekrana yazdırmak için:

```python
# Azazil'de ekran çıktısı
yazdır("Merhaba Dünya")
```

### Değişken Tanımlama

Değişkenler Python'da olduğu gibi oluşturulur, sadece Türkçe isimler kullanabilirsiniz.

```python
#Azazil değişken tanımlama
sayı = 10
metin = "Merhaba"
mantıksal = Doğru
```

### Kullanıcıdan Veri Almak

Kullanıcıdan bir girdi almak için:

Giriş komutunu yansımasını Azazilde henüz görüntüleyemezsiniz bunun için exe dosyası oluşturun.

```python
#Azazil kullanıcıdan veri alma
girdi = giriş("Bir şey yazınız: ")
yazdır("Girdiğiniz: ", girdi)
```

### Koşul Yapıları

Bir koşulu kontrol etmek için:

```python
#Eğer
sayı=10
eğer sayı > 5:
    yazdır("Sayı beşden büyüktür")
```

Birden fazla koşulu kontrol etmek için:
```python
#İken ve değilse
sayı=10
eğer sayı > 5:
    yazdır("Sayı beşden büyüktür")
iken sayı > 5:
    yazdır("Sayı 5 ile 10 arasında")
değilse:
    yazdır("Sayı beşden küçük veya eşittir")
```

### Döngüler

Bir liste veya menzil üzerinde döngü yapmak için:

```python
#Sıralı Döndür
sıralı_döndür i menzil(5):
    yazdır(i)
```
Bir koşul doğru olduğu sürece döngü yapmak için:

```python
#Döndür
x = 0
döndür x < 5:
    yazdır(x)
    x = x + 1
```

### Fonksiyonlar ve Sınıflar

Bir fonksiyon tanımlamak için:

```python
#Azazil fonksiyon tanımlama ve çağırma
fonksiyon selam_ver(isim):
    yazdır(f"Merhaba {isim}")

selam_ver("Mert")
```
Bir sınıf tanımalamak için:

```python
#Azazil sınıf tanımlama
sınıf Araba:
    fonksiyon içinde(self, marka):
        self.marka = marka
```
### Veri işlemleri

Bir liste oluşturmak için:

```python
#Azazil listeleme
listele = [1, 2, 3, 4]
```
Listeye eleman eklemek için:

```python
#Azazil eleman ekleme
liste.ekle(5)
```
Listenin eleman saysını öğrenmek için:

```python
#Azazil eleman sayısı öğrenme
uzunluk = liste.sayım()
```
### İşletim sistemi kütüphanesi komutları

 İşletim sistemi kütüphanesi yükleme:

 ```python
#Azazil kütüphane yüklü
işletim sistemi kütüphanesini yükle
```

Bir dosyayı okumak için:

```python
#Azazil dosya okuma
dosya = işletim_sistemi.dosya_oku("dosya.txt", "r")
metin = işletim_sistemi.dosya_oku()
işletim_sistemi.dosya_kapat()
```

Bir dosyaya yazmak için:

```python
#Azazil dosyaya yazma
dosya = işletim_sistemi.dosya_oku("dosya.txt", "r")
metin = işletim_sistemi.dosya_oku()
işletim_sistemi.dosya_kapat()
```

Bir dizin oluşturmak için:

```python
#Azazil dizin oluşturma
işletim_sistemi.dizin_oluştur("yeni_klasor")
```

Bir dizini silmek için:

```python
#Azazil dizin silme
işletim_sistemi.dizin_sil("eski_klasor")
```

Bir dizindeki dosyaları listelemek için:

```python
#Azazil dizindeki dosyaları listeleme
dosyalar = işletim_sistemi.dizin_listele(".")
yazdır(dosyalar)
```

Bir dosyayı silmek için:

```python
#Azazil dosya silme
işletim_sistemi.dosya_sil("örnek.txt")
```

Bir soyayı veya bir dizini yeniden adlandırmak için:

```python
#Azazil bir soyayı veya bir dizini yeniden adlandırma
işletim_sistemi.yeniden_adlandır("eski_ad.txt", "yeni_ad.txt")
```
Mevcut dizini öğrenmek için:

```python
#Azazil mevcut dizini öğrenme
mevcut = işletim_sistemi.mevcut_dizin()
yazdır(mevcut)
```
Mevcut dizini değiştirmek için:

```python
#Azazil mevcut dizin değiştirme
işletim_sistemi.dizin_değiştir("yeni_klasor")
```
Birden fazla dizin yolunu birleştirmek için:

```python
#Azazil dizin yolu birleştirme
tam_yol = işletim_sistemi.dizin_yolu_birleştir("klasor", "alt_klasor", "dosya.txt")
yazdır(tam_yol)
```

Bir dizinin var olup olmadığını kontrol etmek için:

```python
#Azazil dizin kontrol etme
var_mı = işletim_sistemi.dizin_var_mı("hedef_klasor")
yazdır(var_mı)
```

Bir yolun mutlak yolunu almak için:

```python
#Azazil mutlak yol bulma
tam_yol = işletim_sistemi.mutlak_yol("göreli_yol")
yazdır(tam_yol)
```

Bir dosya yolunun son kısmını almak için:

```python
#Azazil dosya yolunun son kısmını alma
dosya_adı = işletim_sistemi.taban_adı("klasor/dosya.txt")
yazdır(dosya_adı)
```

Sistem komutu çalıştırmak için:

```python
#Azazil sistem komutu çalıştırma
işletim_sistemi.sistem("ls")
```

Geçerli kullanıcı adını almak için:

```python
#Azazil kullanıcı adı alma
kullanıcı = işletim_sistemi.kullanıcı_adı()
yazdır(kullanıcı)
```

Kullanılan platformun adını almak için:

```python
#Azazil platform adı alma
platform = platform()
yazdır(platform)
```

Detaylı platform bilgisi almak için:

```python
#Azazil platform bilgisi alma
işletim_sistemi.detaylı_platform()
yazdır(detaylar)
```

### HTTP istekleri

Bir API'den veri almak için:

```python
#Azazil  API'den veri alma
http.veriyi_çağır("https://api.example.com/data")
```

Bir API'ye veri göndermek için:

```python
#Azazil API'ye veri gönderme
http.veriyi_kaydet("https://api.example.com/data", {"anahtar": "değer"})
```

### Matematiksel işlemler

Liste elemanlarının toplamını bulmak için:

```python
#Azazil liste elemanlarının toplamını bulma
sonuç = mat.toplam([1, 2, 3, 4])
```

Bir sayının karekökünü almak için:

```python
#Azazil karekök alma
kök = kök_al(16)
```

Çıkarma işlemi yapmak için:

```python
#Azazil çıkarma işlemi yapma
çıkarma_sonuc = çıkarmak(10, 4)
```

### Sistem parametreleri ve koşulları kütüphanesi komutlar

Sistem parametreleri ve koşulları kütüphanesi yükleme:

```python
#Azazil sistem parametreleri ve koşulları kütüphanesi yükleme
sistem_modülü_yükle = import sys
```

Komut satırı argümanları almak için:

```python
#Azazil komut satırı argümanları alma
argümanlar = sistem_modülü.komut_satırı_argümanları
yazdır(argümanlar)
```

Python yorumlayıcı yolunu almak için:

```python
#Azazil python yorumlayıcı yolunu alma
yorumlayıcı_yolu = sistem_modülü.python_yorumlayıcı_yolu
yazdır(yorumlayıcı_yolu)
```

Python sürüm bilgisi almak için:

```python
#Azazil python sürüm bilgisi alma
sürüm = sistem_modülü.sürüm_bilgisi
yazdır(sürüm)
```

Platform bilgisi almak için:

```python
#Azazil platform bilgisi
platform = sistem_modülü.platform_bilgisi
yazdır(platform)
```

Yüklenen modülleri listelemek için:

```python
#Azazil yüklşenen modülleri yükleme
yüklenen_modüller = sistem_modülü.yüklenen_modüller
yazdır(yüklenen_modüller)
```

Varsayılan karakter setini öğrenmek için:

```python
#Azazil varsayılan karakter setini öğrenme
karakter_seti = sistem_modülü.varsayılan_karakter_seti
yazdır(karakter_seti)
```

Programı sonlandırmak için:

```python
#Azazil programı sonlandırma
istem_modülü.çık()
```

Bellek boyutunu öğrenmek için:

```python
#Azazil bellek boyutunu öğrenme
obj = "Merhaba Dünya"
boyut = sistem_modülü.bellek_boyutu(obj)
yazdır(boyut)
```

Özyineleme limitini öğrenmek için:

```python
#Azazil özyineleme linmitini öğrenme
limit = özyineleme_limiti_al()
yazdır(limit)
```

Son oluşan istisnayı almak için:

```python
#Azazil son oluşan istisnayı alma
istina = sistem_modülü.son_istisna()
yazdır(istina)
```

İş parçacığı alanını öğrenmek için:

```python
#Azazil iş parçacığı alanını öğrenme
aralık = sistem_modülü.iş_parçacığı_aralığı
yazdır(aralık)
```

İş parçacığı aralığını öğrenmek için:

```python
#Azazil iş parçacığı aralığını ayarlama
sistem_modülü.iş_parçacığı_aralığı_ayarla(0.01)
```

İstemci dosya akışı aralığını öğrenmek için:

```python
#Azazil iş dosya akışı aralığını öğrenme
istemci_dosya_akışı = sistem_modülü.istemci_dosya_akışı
yazdır(istemci_dosya_akışı)
```

Hata akışını öğrenmek için:

 ```python
hata_akışı = sistem_modülü.hata_akışı
yazdır(hata_akışı)
```

Giriş akışını öğrenmek için:

```python
#Azazil giriş akışını öğrenme
giriş_akışı = sistem_modülü.giriş_akışı
yazdır(giriş_akışı)
```

Sonlandırma kontrolü almak için:

```python
#Azazil sonlandırma kontrolü alma
sonlandırma_kontrolü = sistem_modülü.sonlandırma_kontrolü
yazdır(sonlandırma_kontrolü)
```

Unicode en yüksek değeri öğrenmek için:

```python
max_unicode = sistem_modülü.unicode_en_yüksek_değer
yazdır(max_unicode)
```

Tam sayı maksimum değeri öğrenmek için:

```python
#Azazil tam sayı maksimum değeri öğrenme
max_size = sistem_modülü.tamsayı_maksimum_değer
yazdır(max_size)
```


- ✅ Tarih ve zaman kütüphanesi
- ✅ Rastgele İşlem kütüphanesi
- ✅ Düzenli ifadeler kütüphanesi
- ✅ HTTP istekleri kütüphanesi
- ✅ JSON veri işlemleri kütüphanesi
- 🚧 Yerel veri işlemleri kütüphanesi
- 🚧 Günlüğe kayıt işlemleri kütüphanesi
- 🚧 Hata izleme işlemleri kütüphanesi
- 🚧 Çoklu iş parçacığı kütüphanesi
- 🚧 Birden fazla platforma yazılım geliştirme seçeneği(web,android,ios,linux,windows)


## Katkıda Bulunun

Azazil'e katkıda bulunmak isterseniz, lütfen [GitHub]([https://github.com/azazil-dev](https://github.com/merttalha/azazil-Turkish-programming-language/tree/main?tab=readme-ov-file)) sayfamızı ziyaret edin ve geliştirme rehberimizi inceleyin.

## Lisans

Azazil, [Azazil Lisansı](https://azazil.fly.dev/license) altında sunulmaktadır. Daha fazla bilgi için lisans sayfamızı ziyaret edebilirsiniz.
