# Azazil



![Azazil Icon](https://github.com/user-attachments/assets/9a5a5230-f28f-45ae-87b7-c4b5ae4c0f10)

Azazil, hızlı bir şekilde çalışmanıza olanak sağlayan Türkçe Programlama Dili Editörüdür ve sistemlerinizi daha etkili bir şekilde entegre etmenizi sağlar.



İndirme Linki: [İndir](https://firebasestorage.googleapis.com/v0/b/aile-dad9d.appspot.com/o/Azazil%20V1-0.3.zip?alt=media&token=90a66472-9346-4aaa-8e47-586faa26b888)



Kurulum videosu: [İzle](https://youtu.be/eNTVDYABZgM?si=B2X6r9SUkO_C4X1j)



## Hakkında

Azazil, arka planda Python kullanan Türkçe Programlama Dili Editörüdür. Temel Python özellikleri Türkçe bir yapıda sunarak, yazılım geliştiricilere ana dillerinde kod yazmayı sağlar. Azazil, hızlı çıkış alma seçeneği ile öne çıkar. Geliştirilen yazılımlar kolayca çalıştırılabilir ve tek bir tuşla `.exe` dosyası alınabilir. Bu sayede hem öğrenme süreci hızlanır hem de pratik bir geliştirme deneyimi sunar. Karmaşık yapıları basitleştiren ve Türkçe bir alternatif sunan Azazil, yazılım dünyasında özgün bir yere sahiptir.

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
- ✅ Günlüğe kayıt işlemleri kütüphanesi
- ✅ Hata izleme işlemleri kütüphanesi
- ✅ Çoklu iş parçacığı kütüphanesi
- 🚧 Birden fazla platforma yazılım geliştirme seçeneği(web, android, ios, linux, windows)

## Dökümantasyon

### Yazdırma İşlemi

Bir mesaj veya değişkeni ekrana yazdırmak için:

```python
# Azazil'de ekran çıktısı
yazdır("Merhaba Dünya")
```
### Veri tipleri

Veri tipleri Python'da olduğu gibi kullanılmaz bir kaç farklılık vardır,

```python
# Azazil veri tipi dönüşümleri

# Sayıyı metne dönüştürme
yazı = metin(15)  # "15" olarak döner
yazdır(yazı)

# Birden fazla veri tipini metne dönüştürme
birdenfazla=birleştir(42, " yaşındayım, boyum ", 1.76, " metre.")
yazdır(birdenfazla)

# Metni sayıya dönüştürme
sayı = tam_sayı("42")  # 42 olarak döner
yazdır(sayı)

# Ondalıklı bir metni sayıya dönüştürme
ondalik_sayi = ondalık("3.14")  # 3.14 olarak döner
yazdır(ondalik_sayi)

# Mantıksal ifadeyi metne dönüştürme
mantik_metin = metin(Doğru)  # "Doğru" olarak döner
yazdır(mantik_metin)

# Sayıyı mantıksal değere dönüştürme
mantik = mantıksal(1)  # Doğru olarak döner (0 = Yanlış, diğer tüm sayılar = Doğru)
yazdır(mantik)

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

Platm bilgisi almak için:

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

Tau sabiti kullanmak için:

```pythıon
#Azazil tau sabiti hesaplama
sonuç = mat.tau_sabit
yazdır(sonuç)
```

Kesme işelmi için:

```python
#Azazil kesme işlmei
sonuç = mat.kes(2.8)
yazdır(sonuç)
```

En küçük artışı hesaplamak için:

```python
#Azazil en küçük artışı hesaplama
sonuç = mat.en_küçük_artış(1.0)
yazdır(sonuç)
```

### Zaman kütüphanesi komutları

Zaman kütüphanesini yüklemek için:

```python
#Azazil zaman kütüphanesini yükleme
zaman kütüphanesini yükle
```

Zaman dizisini almak için:

```python
#Azazil zaman dizisini alma
sonuç = zaman.zaman_dizisi()
yazdır(sonuç)
```

Zamanı almak için:

```python
#Azazil zamanı alma
sonuç = zaman.zaman()
yazdır(sonuç)
```

Gündüz ışığını almak için:

```python
#Azazil günüdz ışığını alma
sonuç = zaman.gündüz_ışığı()
yazdır(sonuç)
```

Saat bilgilerini almalk için:

```python
#Azazil saat bilgilerini alma
sonuç = zaman.saat_bilgisi_al()
yazdır(sonuç)
```

GMT zamanını almak için:

```python
#Azazil GMT zamanını alma
sonuç = zaman.gmtime()
yazdır(sonuç)
```

Yerel zamanı almakl için:

```python
#Azazil yerel zamanı alma
sonuç = zaman.gmtime()
yazdır(sonuç)
```

Zamanı dönüştürmek için:

```python
#Azazil zamanı dönüştürme
sonuç = zaman.zaman_dönüştür(1635620400)
yazdır(sonuç)
```

Monotonik zaman ölçümü yapmak için:

```python
#Azazil monotonik zaman ölçümü yapma
sonuç = zaman.monotonik()
yazdır(sonuç)
```

Monotonik zaman ölçümü (ns) almak için:

```python
#Azazil monotonik zaman ölçümü (ns) alma
sonuç = zaman.monotonik_ns()
yazdır(sonuç)
```

Performans sayacı ölçümü almak için:

```python
#Azazil performans sayacı ölçümü alma
sonuç = zaman.performans_sayacı()
yazdır(sonuç)
```

Performans sayacı ölçümü (ns) almak için:

```python
#Azazil performan sayacı ölçümü (ns) alma
sonuç = zaman.performans_sayacı_ns()
yazdır(sonuç)
```

İşlem zamanı almak için:

```python
#Azazil işlem zamnı alma
sonuç = zaman.işlem_zamanı()
yazdır(sonuç)
```

İşlem zamanı (ns) almak için:

```python
#Azazil işlem zamnı (ns) alma
sonuç = zaman.işlem_zamanı_ns()
yazdır(sonuç)
```

Uyumak için:

```python
#Azazil uyumak için
zaman.uyumak(2)  # 2 saniye uyuma
```

Zamanı formatlamak için:

```python
#Azazil zamanı formatlama
sonuç = zaman.zaman_formatla("%Y-%m-%d %H:%M:%S", zaman.zaman())
yazdır(sonuç)
```

Zasmanı ayırmak için:

```python
#Azazil zamnanı ayırma
sonuç = zaman.zaman_ayır("%Y-%m-%d %H:%M:%S", "2024-12-03 15:30:00")
yazdır(sonuç)
```

Yapı zamanını almak için:

```python
#Azazil Yapı zamanını almak için
'sonuç = zaman.yapı_zamanı()
yazdır(sonuç)
```

İş parçası zamanını alamak için:

```python
sonuç = zaman.iş_parçası_zamanı()
yazdır(sonuç)
```
İş parçası zamanını (ns) almak için:

```python
#Azazil iş parçası (ns) alma
sonuç = zaman.iş_parçası_zamanı_ns()
yazdır(sonuç)
```

Zaman dilimini almak için:

```python
#Azazil zaman dilimini alma
sonuç = zaman.zaman_dilimi()
yazdır(sonuç)
```

Zaman diliimi adını almak için:

```python
#Azazil zaman dilimi adını alma
sonuç = zaman.zaman_dilimi_adı()
yazdır(sonuç)
```

###Tarih zaman kütüphanesi komutları

Tarih zaman kütüphaneisini yüklemek için:

```python
#Azazil tarih zaman kütüphanesini yükleme
tarih zaman kütüphanesini yükle
```

Bugünün tarihini almak için:

```python
#Azazil bugünün tarihini alma
sonuç = tarih_zaman.bugünün tarihi()
yazdır(sonuç)
```

Şimdiki zamanı almak için:

```python
#Azazil şimdiki zamanı alma
sonuç = tarih_zaman.şimdiki zaman()
yazdır(sonuç)
```

Berlirli bir zamanı oluşturmak için:

```python
#Azazil belirli bir zamanı alma
sonuç = tarih_zaman.belirli zaman(2024, 12, 8, 14, 30)
yazdır(sonuç)
```

 Yıl bilgisini almak için:
 ```python
#Azazil yıl bilgisini alma
sonuç = tarih_zaman.yıl()
yazdır(sonuç)
```

Ay bilgisini almak için:

```python
#Azazil ay bilgisini alma
sonuç = tarih_zaman.ay()
yazdır(sonuç)
```

Gün bilgisini almak için:

```python
#Azazil gün bilgisini alma
sonuç = tarih_zaman.gün()
yazdır(sonuç)
```

Saat bilgisi almak için:

```python
#Azazil saat bilgisi alma
sonuç = tarih_zaman.saat()
yazdır(sonuç)
```

Dakika biligisini almak için:

```pythone
#Azazil dakika bilgisini alma
sonuç = tarih_zaman.dakika()
yazdır(sonuç)
```

Saniye bilgisini almak için:

```python
#Azazil saniye bilgisini alma
sonuç = tarih_zaman.saniye()
yazdır(sonuç)
```

Bir tarihi oluşturmak için:

```python
#Azazil tarih oluşturma
sonuç = tarih_zaman.tarihi_oluştur(2024, 12, 8)
yazdır(sonuç)
```

Bir zaman oluşturmak için:

```python
#Azazil bir azman oluşturma
sonuç = tarih_zaman.zamanı_oluştur(14, 30)
yazdır(sonuç)
```

Belirli bir zamanı dilime dönüştürmerk için:

```python
#Azazil belirli bir zamanı dilime dönüştürme
sonuç = tarih_zaman.zamanı_dilime_dönüştür(datetime.timezone.utc)
yazdır(sonuç)
```

Bir zamanı diziye çevirmek için:

```python
#Azazil bir zamanı dizeye çevirme
sonuç = tarih_zaman.dizeye_çevir("%Y-%m-%d", belirli zaman(2024, 12, 8))
yazdır(sonuç)
```

Bir dizgeyi zamana dönüştürmek için:

```pyhon
#Azazil bir dizgeyi zaana dönüştürme
sonuç = tarih_zaman.dizeden_zamana("%Y-%m-%d", "2024-12-08")
yazdır(sonuç)
```

UTC zamanını almak için:

```python
#Azazil UTC zamanı alma
sonuç = tarih_zaman.utc_zamanı()
yazdır(sonuç)
```

### Rastgele kütüphanesi komutları

Ratgele kütüphanesini yüklemek için:

```python
#Azazil rastgele ktüphanesini yükle
rastgele kütüphanesini yükle
```

Rastgele sayı üretmek için:

```python
#Azazil
rastgele kütüphanesini yükle
```

Bir aralıktan rastgele bir sayı seçmek için:

```python
#Azazil bir aralıktan ratgele sayı seçme
sonuç = rastgele.sayı()
yazdır(sonuç)
```

Bir tam sayı seçmek için:

```python
#Azazil bir tam sayı seçme
sonuç = rastgele.aralık(1, 100)
yazdır(sonuç)
```

Bir öğe seçmek için:

```python
#Aazil bir öğe seçme
sonuç = rastgele.tamsayı(1, 100)
yazdır(sonuç)
```

Birden fazla öğe seçmek için:

```python
#Azazil birden fazla öğe seçme
sonuç = rastgele.seç([1, 2, 3, 4, 5])
yazdır(sonuç)
```

Bir listeyi karıştırmak için:

```python
#Azazil bir listeyi karıştırma
sonuç = rastgele.seçimler([1, 2, 3, 4, 5], k=3)
yazdır(sonuç)
```

Üçgen dağılımı oluşturmak için:

```python
#Azazil üçgen dağılımı oluşturma
sonuç = rastgele.üçgen(1, 10, 5)
yazdır(sonuç)
```

Bir örnek seçmek için:

```pythone
#Azazil bir örnek seçme
sonuç = rastgele.örnek([1, 2, 3, 4, 5], 2)
yazdır(sonuç)
```

Logaritmik dağılım oluşturmak için:

```python
#Azazil logaritmik dağılım oluşturma
sonuç = rastgele.logaritmik(0.5, 1.0)
yazdır(sonuç)
```

Normal dağılım oluşturmak için:

```pythone
#Azazil normal dağılım oluşturma
sonuç = rastgele.normal(0, 1)\nyazdır(sonuç)
```

Üstel dağılım oluşturmak için:

```python
#Azazil üstel dağılım oluşturma
sonuç = rastgele.üstel(1.0)
yazdır(sonuç)
```

Gauss dağılımı oluşturmak için:

```python
#Azazil gauss dağılımı oluşturma
sonuç = rastgele.gauss(0, 1)
yazdır(sonuç)
```

## Düzenli ifadeler kütüphanesi komutları 

Düzenli ifadeler kütüphanesi yüklemek için:

```python
#Azazil düenli ifadeler kütüphanesi yükleme
düzenli ifade kütüphanesini yükle
```

Bir düzenli ifade derlemek için:

```python
#Azazil bir düenl iifade oluşturma
şablon = düzenli_ifadeler.derle(r"\\d{2,4}")
```

Bir düzenli ifade ile arama yapmak için:

```python
#Azazil bir düzenli ifade ile arama yapma
sonuç = düzenli_ifadeler.ara(r"\\d{2,4}", "1234")\nyazdır(sonuç)
```

Tüm eşleşmeleri bulmak için:

```python
#Azazil tüm eşleşmeleri bulmak için:
sonuç = düzenli_ifadeler.tüm eşleşmeler(r"\\d", "abc123xyz456")
yazdır(sonuç)
```

Eşleşmeleri itertif olarka yamak için:

```python
#Azazil eşleşmeleri iteratif olarak yapma
sonuç = düzenli_ifadeler.iteratif eşleşmeler(r"\\d", "abc123xyz456")
yazdır(sonuç)
```

Tam eşleşmeyi kontrol etmek için:

```python
#Azazil tam eşleşmeleri kontrol etme
sonuç = düzenli_ifadeler.tam eşleşme(r"abc", "abc")
yazdır(sonuç)
```

Kaçış karakteri eklemek için:

```python
#Azazil kaçış karakteri ekleme
sonuç = düzenli_ifadeler.kaçış(r"\\d")
yazdır(sonuç)
```

Bir metni bölmek için:

```python
#Azazil bir metni bölme
sonuç = düzenli_ifadeler.böl(r"\\s+", "merhaba dünya")\nyazdır(sonuç)
```

Bir alt metin değiştirmek için:

```python
#Azazil bir alt metin değiştirme
sonuç = düzenli_ifadeler.alt(r"\\d", "#", "abc123xyz456")\nyazdır(sonuç)
```

Birden fazla alt metin değiştirmek için:

```python
#Azazil birden fazla alt metin değiştirme
sonuç = düzenli_ifadeler.alt_sayı(r"\\d", "#", "abc123xyz456")\nyazdır(sonuç)
```

Bir metni temizlemek için:

```python
#Azazil wdbir metni temizleme
sonuç = düzenli_ifadeler.temizle("abc123xyz456")
yazdır(sonuç)
```

Eşleşme kontrolü yapmak için:

```python
#Azazil eşleşme kontrolü yapma
sonuç = düzenli_ifadeler.eşleşme(r"abc", "abc123")
yazdır(sonuç)
```

## JSON kütüphanesi komutları

Json kütüphanesini yüklemek için:

```python
#Azazil json kütüphanesi yükleme
json_kütüphanesini_yükle
```

Bir json dosyasını okumak için:

```python
#Azazil bir json dosyaysını okuma
veri = json.oku(dosya)
```

Bir nesneyi json formatında dosyaya yazmak için:

```python
#Azazil bir nesneyi json fomratında yazama
json.yaz(nesne, dosya)
```

Bir nesneyi JSON formatında metin olarak yazmak için:

```python
#Azazil bir nesneyi json fomratında metin olarak yazma
json_dize = json.metine_yaz(nesne)
```

JSON formatındaki bir metni okumak için:

```python
#Azazil json formatındaki bir metni okumak için:
veri = json.metinden_oku(json_dize)
```

Bir JSON kod çözücü kullanmak için:

```python
#Azazil bir json çözücü kullanma
çözücü = json_işlemleri.kod_çözücü()
```

Bir JSON kodlayıcı kullanmak için:

```python
#Azazil json kodlayıcı kullanma
kodlayıcı = json.kodlayıcı()
```

Bir JSON kodlama hatasını yakalamak için:

```python
#Azazil json kodlama hatası yakalamak için:
hata = json.kodlama_hatası
```

JSON kodlama algoritmasını algılamak için:

```python
#Azazil json kodlama algoritmasını algılama
algıla = json.kodlama_algıla(dosya)
```

Bir JSON tarayıcı kullanmak için:

```python
#Azazil bir json tarayıcı kullanma
tarayıcı = json.tarayıcı()
```

## Kayıt kütüphanesi komutları

Kayıt kütüphanesini yüklemek için:

```python
#Azazil kayıt kütüphanesini yükleme
kayıt_kütüphanesini_yükle
```

Kaydetme seviyelerini kullanmak için:

```python
#Azazil kaydetme seviyelerini kullanma
#kritik seviyesi
seviyeler = kayıt.kritik
yazdır(seviyeler)

#hata seviyesi
seviyeler = kayıt.hata
yazdır(seviyeler)

#hata ayıklama seviyesi
seviyeler = kayıt.hata_ayıklama
yazdır(seviyeler)

#bilgi seviyesi
seviyeler = kayıt.bilgi
yazdır(seviyeler)

#uyarı seviyesi
seviyeler = kayıt.uyarı
yazdır(seviyeler)

#hiçbiri seviyesi
seviyeler = kayıt.hiçbiri
yazdır(seviyeler)
```

Temel yapılanmdırma ayarlarını yapmak için:

```python
#Azazil temel yapılandırma ayarlarını yapma
kayıt.temel_ayarla(seviye=kayıt.bilgi)
```

Kaydedici oluşturmak için:

```python
#Azazil kaydedici oluşturma
logger = kayıt.kayıt_al("örnek_logger")
logger.info("Bu bir bilgi mesajıdır.")
```

Kaydedici sınıfını almak ve ayarlamak için:

```python
#Azazil kaydedici sınıfını almak ve ayarlama
sınıf = kayıt.kayıt_sınıfı_al()
yazdır(sınıf)

kayıt.kayıt_sınıfı_ayarla(YeniLoggerSınıfı)
```

Özel kayıt seviyesi ayarlamak için:

```python
#Azazil özel kayıt seviyesi ayarlama
#kaydedici sınıfı al
kayıt.seviyeyi_adlandır(25, "ÖZEL_SEVİYE")
#kaydedici sınıfı ayarla
yazdır(kayıt.seviyeyi_al(25))
```

Uyarı ve hata işlemleri için:

```python
#Azazil uyarı ve hata işlemleri
#uyarıları yakala
kayıt.kayıt_yakala(True)

#Hata Baskıla
kayıt.hata_baskıla(kayıt.hiçbiri)

#uyarıları kapat
kayıt.uyarıları_kapat()
```

Kaydetme işlemleri için:

```python
#Azazil kaydetme işlemleri
#bilgi kaydı
kayıt.kayıt_et(kayıt.bilgi, "Bilgi kaydı mesajı")

#hata kaydı
kayıt.hata_kayıt("Bu bir hata mesajıdır.")

#uyarı kaydı
kayıt.uyarı_kayıt("Bu bir uyarı mesajıdır.")

#hata ayıklama kaydı
kayıt.debug_kayıt("hata ayıklama mesajı")

#kritik kaydı
kayıt.kritik_kayıt("Kritik hata mesajı")
```

Formatlayıcılar ve tutucular için:

```python
#Azazil formatlayıcı ve tutucular
#formatlayıcı
formatlayıcı = kayıt.formatlayıcı("%(asctime)s - %(isim)s - %(seviye)s: %(mesaj)s")

#akış tutucu
akış_tutucu = kayıt.akış_tutucu()
kaydedici = kayıt.kayıt_al("akış_logger")
logger.addHandler(akış_tutucu)

#dosya tutucu
dosya_tutucu = kayıt.dosya_tutucu("log_dosyası.log")
logger = kayıt.kayıt_al("dosya_logger")
logger.addHandler(dosya_tutucu)

#boş tutucu
boş_tutucu = kayıt.boş_tutucu()
kaydedici = kayıt.kayıt_al("boş_logger")
logger.addHandler(boş_tutucu)
```

Diğer kaydetme işlemler için:

```python
#Azazil diğer kaydetme işlemleri
#kayıt süreçleri
yazdır(kayıt.kayıt_süreçleri)

#kayıt işlemleri
yazdır(kayıt.kayıt_işlemleri)

#kayıt oluşturucu ayarla
kayıt.kayıt_oluşturucu_ayarla(yeni_oluşturucu)

#kayıt oluşturucu al
yazdır(kayıt.kayıt_oluşturucu_al())
```

## Hata izleme kütüphanesi komutları

Hata izleme komutları kütüphanesini yüklemek için:

```python
#Azazil hata izleme kütüphanesi yükleme
hata_izleme_kütüphanesini_yükle
```

Bir çerçeve özeti oluşturmak için:

```python
#Azazil bir çerçeve özeti oluşturma
çerçeve = hata_izleme.çerçeve_özeti(dosya_adı, satır_no, işlev_adı)
```

Bir yığın özeti oluşturmak için:

```python
#Azazil bir yığın özeti oluşturma
yığın = hata_izleme.yığın_özeti()
```

Bir geri izleme istisnası oluşturmak için:

```python
#Azazil Bir geri izleme istisnası oluşturma
istisna = hata_izleme.hata_izleme_istisnası(*sys.exc_info())
yazdır(istisna)
```

Çerçeveleri temizlemek için:

```python
#Azazil çerçeveleri temizleme
hata_izleme.çerçeveleri_temizle(istisna)
```

Bir yığın çıkarımı yapmak için:

```python
#Azazil bir yığın çıkarımı yapma
yığın = hata_izleme.yığını_çıkar()
yazdır(yığın)
```

Bir izleme yığını çıkarmak için:

```python
#Azazil bir izleme yığını çıkarma
izleme_yığını = hata_izleme.izleme_yığınını_çıkar(istisna.tb)
```

Bir hatayı biçimlendirmek için:

```python
#Azazil bir hatayı biçimlendirme
hata_metin = hata_izleme.format_hata()
yazdır(hata_metin)
```

Bir istisnayı biçimlendirmek için:

```python
#Azazil bir istisnayı biçimlendirme
istisna_metin = hata_izleme.format_istisna(*sys.exc_info())
yazdır(istisna_metin)
```

Yalnızca istisna bilgisini biçimlendirmek için:

```python
#Azazil yalnızca istisna bilgisini biçimlendirme
sadece_istisna = hata_izleme.yalnızca_istisna_formatla(*sys.exc_info())
yazdır(sadece_istisna)
```

Bir listeyi biçimlendirmek için:

```python
#Azazil bir listeyi biçimlendirme
liste = hata_izleme.liste_formatla(yığın)
yazdır(liste)
```

Bir yığını biçimlendirmek için:

```python
#Azazil bir yığını biçimlendirme
formatlanmış_yığın = hata_izleme.yığın_formatla()
yazdır(formatlanmış_yığın)
```

Bir izleme yığınını biçimlendirmek için:

```python
#Azazil bir izleme yığınını biçimlendirme
formatlanmış_izleme = hata_izleme.izleme_yığınını_formatla(istisna.tb)
yazdır(formatlanmış_izleme)
```

Bir istisnayı yazdırmak için:

```python
#Azazil bir istisnayı yazdırma
hata_izleme.istisna_yazdır()
```

Son istisnayı yazdırmak için:

```python
#Azazil son istisnayı yazdırmak için:
hata_izleme.son_istisnayı_yazdır()
```

Bir yığında dolaşmak için:

```python
#Azazil bir yığında dolasma
sıralı döngü komutu çerçeve, yol in hata_izleme.yığın_yürü():
    yazdır(çerçeve, yol)
```

Bir izleme yığınında dolaşmak için:

```python
#Azazil bir izleme yığınında dolaşma
sıralı döngü komutu çerçeve, yol in hata_izleme.izleme_yığınında_yürü(istisna.tb):
    yazdır(çerçeve, yol)
```

Hataları baskılamak için:


```python
#Azazil hataları baskılama
ile hata_izleme.baskıla():
    potansiyel_hatalı_fonksiyon()
```

## İş parçacığı kütüphanesi komutları


İş parçacığı kütüphanesini yüklemek için:

```python
#Azazil iş parçacığı kütüphanesini yükleme
iş_parçacığı_kütüphanesini_yükle
```

Bir engel (barrier) oluşturmak için:


```python
#Azazil bir engel (barrier) oluşturma
engel = iş_parçacığı.engel(katılımcı_sayısı)
```

Sınırlı semafor oluşturmak için:

```python
#Azazil sınırlı semafor oluşturma
sınırlı_semafor = iş_parçacığı.sınırlı_semafor(değer)
```

Bir bozulan engel hatası örneği oluşturmak için:

```python
#Azazil bir bozulan engel hatası örneği oluşturma
hata_yakala:
    engel.bekle()
hata_ver iş_parçacığı.bozuk_engel_hatası:
    yazdır("Engel bozuldu!")
```

Bir koşul nesnesi oluşturmak için:


```python
#Azazil bir koşul nesnesi oluşturma
koşul = iş_parçacığı.koşul()
```

Bir olay nesnesi oluşturmak için:

```python
#Azazil bir olay nesnesi oluşturma
olay = iş_parçacığı.olay()
```

Bir kilit nesnesi oluşturmak için:

```python
#Azazil bir kilit nesnesi oluşturma
kilit = iş_parçacığı.kilit()
```

Bir yeniden giriş kilidi oluşturmak için:

```python
#Azazil bir yeniden giriş kilidi oluşturma
r_kilit = iş_parçacığı.yeniden_giriş_kilidi()
```

Bir semafor nesnesi oluşturmak için:

```python
#Azazil bir semafor nesnesi oluşturma
semafor = iş_parçacığı.semafor(değer)
```

Maksimum zaman aşımı değerini öğrenmek için:

```python
#Azazil maksimum zaman aşımı değerini öğrenme
yazdır(zaman_aşımı_maks)
```

Bir iş parçacığı oluşturmak için:

```python
#Azazil bir iş parçacığı oluşturma
iş = iş_parçacığı.iş_parçacığı(hedef=fonksiyon, args=(argümanlar,))
iş.başlat()
```

Aktif iş parçacıklarının sayısını almak için:

```python
#Azazil aktif iş parçacıklarının sayısını alma
yazdır(iş_parçacığı.aktif_sayı())
```

Geçerli iş parçacığını almak için:

```python
#Azazil geçerli iş parçacığını alma
geçerli = iş_parçacığı.geçerli_iş_parçacığı()
```

İş parçacıklarını sıralamak için:

```python
#Azazil iş parçacıklarını sırala
yazdır(iş_parçacığı.sıralama())
```

Bir iş parçacığı kimliğini almak için:

```python
#Azazil bir iş parçacığı kimliğini alma
yazdır(iş_parçacığı.kimlik_al())
```

Bir profil ayarlamak için:

```python
#Azazil bir profil ayarlama
iş_parçacığı.profil_ayarla(profil_fonksiyonu)
```

Bir izleme ayarlamak için:

```python
#Azazil bir izleme ayarlama
iş_parçacığı.izleme_ayarla(izleme_fonksiyonu)
```

Bir iş parçacığı yığın boyutunu ayarlamak için:

```python
#Azazil "bir iş parçacığı yığın boyutunu ayarlama
iş_parçacığı.yığın_boyutu(boyut)
```

## Katkıda Bulunun

Azazil'e katkıda bulunmak isterseniz, lütfen [GitHub]([https://github.com/azazil-dev](https://github.com/merttalha/azazil-Turkish-programming-language/tree/main?tab=readme-ov-file)) sayfamızı ziyaret edin ve geliştirme rehberimizi inceleyin.

## Lisans

Azazil, [Azazil Lisansı](https://azazil.fly.dev/license) altında sunulmaktadır. Daha fazla bilgi için lisans sayfamızı ziyaret edebilirsiniz.
