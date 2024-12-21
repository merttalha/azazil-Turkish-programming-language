# Azazil

![Azazil Icon](https://github.com/user-attachments/assets/da75c13d-6a80-494a-8720-613570692d8f)

Azazil, hızlı bir şekilde çalışmanıza olanak sağlayan Türkçe bir programlama dilidir ve sistemlerinizi daha etkili bir şekilde entegre etmenizi sağlar.

Resmi site: [azazil.fly.dev](https://azazil.fly.dev)


İndirme Linki: [İndir](https://drive.google.com/file/d/1wrKhrf3BjrkvxeSb1_6vCGWXW-dj7VTf/view?usp=sharing)

## Hakkında

Azazil, arka planda Python kullanan Türkçe bir yazılım dilidir. Temel Python özellikleri Türkçe bir yapıda sunarak, yazılım geliştiricilere ana dillerinde kod yazmayı sağlar. Azazil, hızlı çıkış alma seçeneği ile öne çıkar. Geliştirilen yazılımlar kolayca çalıştırılabilir ve tek bir tuşla `.exe` dosyası alınabilir. Bu sayede hem öğrenme süreci hızlanır hem de pratik bir geliştirme deneyimi sunar. Karmaşık yapıları basitleştiren ve Türkçe bir alternatif sunan Azazil, yazılım dünyasında özgün bir yere sahiptir.

## Özellikler

- **Türkçe Kodlama:** Azazil, Python'un güçlü altyapısını kullanarak Türkçe bir yazılım dili sunar.
- **Kolay Kullanım:** Türkçe komutlarla hızlı bir şekilde yazılım geliştirme imkanı sağlar.
- **.exe Desteği:** Geliştirilen yazılımlar tek tuşla çalıştırılabilir `.exe` dosyalarına dönüştürülebilir.
- **Eğitim Dostu:** Öğrenmeyi kolaylaştırır ve yazılım dünyasına yeni başlayanlar için idealdir.

  ## Yol Haritası

- ✅ İşletim sistemi kütüphanesi
- ✅ Sistem parametreleri ve koşulları kütüphanesi
- ✅ Matematikesel işlemler kütüphanesi
- ✅ Zaman kütüphanesi
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
    fonksiyon başlangıçta(self, marka):
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

### Matematik kütüphanesi 

Mateamtik kütüphanesini yüklemek için:

```python
#Azazil matematik kütüphanesi yükleme
matematik_kütüphanesi_yükle = matematik kütüphanesini yükle
```

Ark kosinus hesaplamak için:

```python
sonuç = mat.arkkosinüs(0.5)
yazdır(sonuç)
```

Ark Hiper kosinüs hesaplamak için:

```python
#Azazil Ark Hiper kosinüs hesaplama
sonuç = mat.arkhiperkosinüs(1)
yazdır(sonuç)
```

Ark Sinüs hesaplamak için:

```python
#Azazil Ark Sinüs hesaplama
sonuç = mat.arksinüs(0.5)
yazdır(sonuç)
```

Ark Hipersinüs hesaplamak için:

```python
#Azazil Ark Hipersinüs hesaplamak için
sonuç = mat.arkhipersinüs(1)
yazdır(sonuç)
```

Ark Tanjant hesaplamak için:

```python
#Azazil Ark Tanjant hesaplama
sonuç = mat.arktanjant(1)
yazdır(sonuç)
```

İki nokta arasındaki Ark Tanjant hesaplamak için:

```python
#Azazil iki nokta arasındaki Ark Tanjant hesaplama
sonuç = mat.arktanjant2(1, 1)
yazdır(sonuç)
```

Ark Hipertanjant hesaplamak için:

```python
#Azazil Hipertanjant hesaplama
 mat.arkhipertanjant(0.5)
yazdır(sonuç)
```

Küp Kök hesaplaması için:

```python
#Azazil küp kök hesaplama
sonuç = mat.küp_kök(27)
yazdır(sonuç)
```

Yuvarlama yukarı yapmak için:

```python
#Azazil yukarı yuvarlama yapma
sonuç = mat.yuvarla_yukarı(2.3)
yazdır(sonuç)
```

Kombinasyon hesaplamak için:

```python
#Azazil kombinasyon hesapalama,
sonuç = mat.kombinasyon(5, 2)
yazdır(sonuç)
```

İşaret kopyalamak için:

```python
#Azazil işaret kopyala
sonuç = mat.işaret_kopyala(-5, 3)
yazdır(sonuç)
```

Kosinüs hesaplamak için:

```python
#Azazil kosinüs hesapalama
 mat.kosinüs(0.5)
yazdır(sonuç)
```

Hiperkosinüs hesaplamak için:

```python
#Azazil Hiper kosinüs hesapalama
mat.hiperkosinüs(0.5)
yazdır(sonuç)
```
Dereceyi radiana çevirmekl için:

```python
#Azazil dereceyi raidana çevirme
sonuç = mat.derece(90)
yazdır(sonuç)
```

Uzaklık hesapalamak için:

```python
#Azazil uzaklık hesaplama
sonuç = mat.uzaklık((0, 0), (3, 4))
yazdır(sonuç)
```

E sabitini almak için:

```python
#Azazil E sabitini alma
sonuç = mat.e_sabit
yazdır(sonuç)
```

Hata fonksiyonu kullanmak için:

```python
#Azazil hta fonksiyonu alma
sonuç = mat.hata_fonksiyonu(1)
yazdır(sonuç)
```

Komplemanter Hata Fonksiyonu kullanmak için:

```python
sonuç = mat.komplemanter_hata_fonksiyonu(1)
yazdır(sonuç)
```

Üs almak için:

```python
#Azazil üs alma
sonuç = mat.üs(2, 3)
yazdır(sonuç)
```

İkinci üs almak için:

```python
#Azazil ikinci üs almak için
sonuç = mat.üs2(2)
yazdır(sonuç)
```

Eksponansiyel 1 hesaplamak için:

```python
#Azazil eksponansiyel 1 hesaplama
sonuç = mat.eksponansiyel1(1)
yazdır(sonuç)
```

Mutlak değeri hesaplamak için:

```python
#Azazil mutlak değer alma
sonuç = mat.mutlak_değer(-5)
yazdır(sonuç)
```

Faktöriyel hesaplamak için:

```python
#Azazil faktöriyel hesaplama
sonuç = mat.faktöriyel(5)
yazdır(sonuç)
```

Yuvarlama aşağı yapmak için:

```python
#Azazil aşağı yuvarlama yapma
sonuç = mat.yuvarla_aşağı(2.8)
yazdır(sonuç)
```

Modül hesaplamak için:

```python
#Azazil modül hesaplama
sonuç = mat.modül(5, 3)
yazdır(sonuç)
```

Serbest üstel hesaplamak için:

```python
#Azazil serbest üstel hesaplama
sonuç = mat.serbest_üstel(5, 2)
yazdır(sonuç)
```

Toplam hesaplamak için:

```python
#Azazil toplam hesaplama
sonuç = mat.toplam([1, 2, 3])
yazdır(sonuç)
```

Gamma fonksiyonunu hesaplamak için:

```python
#Azazil Gamma fonksiyomnu hesaplama
sonuç = mat.gamma_fonksiyonu(1.5)
yazdır(sonuç)
```

EKOK hesaplamak için:

```python
#Azazil EKOK hesaplama
sonuç = mat.ekok(12, 18)
yazdır(sonuç)
```

Hipotenüs hesaplamak için:

```python
#Azazil Hipotenüs hesaplama
sonuç = mat.hipotenüs(3, 4)
yazdır(sonuç)
```

Sonsuzluk değeri almak için:

```python
#Azazil sonsuzluk değeri alma
sonuç = mat.sonsuzluk
yazdır(sonuç)
```

Yakın mı hesaplamak için:

```python
#Azazil yakın mı hesaplama
sonuç = mat.yakın_mı(0.1, 0.10001)
yazdır(sonuç)
```

Sonlu mu kontrol etmek için:

```python
#Azazil sonlu mu kontrol etmek için:
sonuç = mat.sonlu_mı(1)
yazdır(sonuç)
```

Sonsuz mu kontrol etmek için:

```python
#Azazil sonsuz mu kontrol etme
sonuç = mat.sonsuz_mı(mat.sonsuzluk)
yazdır(sonuç)
```

Nan mı kontro letmek için:

```python
#Azazil Nan mı kontrol etmek için
sonuç = mat.nan_mı(mat.nan)
yazdır(sonuç)
```

Tam karekök hesaplamaka için:

```python
#Azazil tam karekök hesaplama
mat.tam_karekök(25)
yazdır(sonuç)
```

Çift tam sayı hesaplamak için:

```python
#Azazil çift tam sayı hesaplama
sonuç = mat.çift_tam_sayı(5, 2)
yazdır(sonuç)
```

Logaritma hesaplamak için:

```python
#Azazil logaritma hesaplama
sonuç = mat.logaritma(100)
yazdır(sonuç)
```

Logaritma 10 hesaplamak için

```python
#Azazil logaritma 10 hesaplamak için:
sonuç = mat.log10(100)
yazdır(sonuç)
```

Logaritma 1p hesaplamaka için:

```python
#Azazil logaritma 1p hesaplamak için
sonuç = mat.log1p(0.5)
yazdır(sonuç)
```

Logaritma 2 hesaplamak için:

```python
#Azazil logaritma 2 hesaplama
sonuç = mat.log2(8)
yazdır(sonuç)
```

Mod dönüşümü yapmak için:

```python
#Azazil mod dönüşümü yapma
sonuç = mat.mod_dönüştür(5, 3)
yazdır(sonuç)
```

Tanımsız hesaplamak için:

```python
#Azazil tanımsız hesaplama
sonuç = mat.tanımısız
yazdır(sonuç)
```

Sonraki hesaplama için:

 ```python
#Azazil sonraki hesaplama
sonuç = mat.sonraki(0, 1)
yazdır(sonuç)
```

Permütasyon hesaplamak için:

```python
#Azazil permütasyon hesaplama
sonuç = mat.permütasyon(5, 3)
yazdır(sonuç)
```

Pi sabitini kullanmak için:

```python
#Azazil Pi sabitini kullanma
sonuç = mat.pi_sabit
yazdır(sonuç)
```

Güç almak için:

```python
#Azazil güç alma,
sonuç = mat.güç_al(2, 4)
yazdır(sonuç)
```

Çarpım hesaplamak için:

```python
#Azazil çarpım hesaplama
'sonuç = mat.çarpım([1, 2, 3])
yazdır(sonuç)
```

Radyan hesaplamak için:

```python
#Azazil radayan hesaplama
sonuç = mat.radyan(180)
yazdır(sonuç)
```

Kalan bölüm hesaplama:

```python
#Azazil kalan bölüm hesaplama
sonuç = mat.kalan_bölüm(5, 3)
yazdır(sonuç)
```

Sinüs hesaplamak için:

```python
#Azazil sinüs hesaplama
sonuç = mat.sinüs(0.5)
yazdır(sonuç)
```

Hipersinüs almak için:

```python
#Azazil Hipersinüs alma
sonuç = mat.hipersinüs(0.5)
yazdır(sonuç)
```

Karekök hesaplamak için:

```python
#Azazil karekök hesaplama
sonuç = mat.kare_kök(25)
yazdır(sonuç)
```

Tanjant hesaplamak için:

```python
#Azazil tanjant hesaplama
sonuç = mat.tanjant(0.5)
yazdır(sonuç)
```

Hipertanjant hesaplamak için:

```python
#Azazil hipertanjant hesaplama
sonuç = mat.hipertanjant(0.5)
yazdır(sonuç)
```
## Katkıda Bulunun

Azazil'e katkıda bulunmak isterseniz, lütfen [GitHub]([https://github.com/azazil-dev](https://github.com/merttalha/azazil-Turkish-programming-language/tree/main?tab=readme-ov-file)) sayfamızı ziyaret edin ve geliştirme rehberimizi inceleyin.

## Lisans

Azazil, [Azazil Lisansı](https://azazil.fly.dev/license) altında sunulmaktadır. Daha fazla bilgi için lisans sayfamızı ziyaret edebilirsiniz.
