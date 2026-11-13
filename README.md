<p align="center">
  <img src="https://samalate.com/assets/logo.png" width="88" alt="SamaLate logosu" />
</p>

<h1 align="center">SamaLate</h1>

<p align="center"><strong>Altyazı çevir. 4K upscale yap. Yayınla.</strong></p>

<p align="center">Windows için video işleme, altyazı düzenleme ve yapay zekâ destekli upscale çalışma alanı.</p>

<p align="center">
  <a href="https://samalate.com/">Web sitesi ve canlı demo</a> ·
  <a href="https://github.com/YavieSama/samalate-releases/releases/latest">Windows için indir</a> ·
  <a href="https://samalate.com/yama-notlar%C4%B1">Yama notları</a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://samalate.com/assets/banner-dark.png" />
  <source media="(prefers-color-scheme: light)" srcset="https://samalate.com/assets/banner-light.png" />
  <img src="https://samalate.com/assets/banner-dark.png" alt="SamaLate'in Windows masaüstü arayüzü" width="100%" />
</picture>

## Bir bölümün hazırlığı, tek uygulamada

SamaLate, anime ve video üzerinde çalışırken ihtiyaç duyduğun araçları aynı yerde toplar. Altyazını çıkarıp çevir, sahne üzerinde zamanını ve stilini kontrol et, görüntüyü iyileştir ve videonu istediğin ayarlarla kodla. Dosyalar arasında geçerken her işlem için ayrı bir uygulama açman gerekmez.

Windows'a uyumlu arayüz, açık ve koyu tema, Türkçe ve İngilizce dil seçenekleriyle çalışır.

## Neler yapabilirsin?

| Özellik | Yapabileceklerin |
| --- | --- |
| **Altyazı çevirisi** | Kendi API sağlayıcını ve modelini kullanarak altyazıları Türkçeye çevir. Birden fazla dosyayı sıraya al, kaynak diyaloglarla çeviri sonuçlarını karşılaştır. |
| **4K upscale** | Farklı anime odaklı modellerle görüntü çözünürlüğünü artır. Cihazına uygun CPU, DirectML, CUDA veya TensorRT hızlandırmasını seç. |
| **Video kodlama** | H.264, H.265 ve AV1 seçenekleriyle kalite, ön ayar, çözünürlük ve ses ayarlarını düzenle. Altyazılı veya altyazısız çıktı al. |
| **Görüntü filtreleri** | Deband, çizgi belirginleştirme ve keskinleştirmeyi ihtiyacına göre kullan. Filigran, logo veya intro ekle. |
| **Önizleme ve düzenleme** | Videoyu altyazısıyla izle; satır metinlerini, zamanlamayı ve ASS stillerini düzenle. Yazı tipi, boyut, renk, kontur ve hizalamayı sahne üzerinde kontrol et. |
| **Altyazı çıkarma ve SubFix** | Videodaki altyazı izlerini çıkar, birden fazla dosyayla çalış ve altyazı zamanlamasını videoya göre eşitle. |
| **Yayın takibi ve indirme** | Nyaa.si ve AnimeTosho yayınlarını ara, paket içinden istediğin dosyaları seç ve indirme kuyruğunu yönet. |
| **Medya araçları** | Altyazı biçimini dönüştür, zaman ve FPS ayarla, ses veya iz çıkar, MKV izlerini düzenle, videodan seçtiğin bölümü kes. |

### Önce küçük bir bölümde dene

Test kodlamasında videonun başından, ortasından veya sonundan bir aralık seçebilirsin. Ayarlarını kısa bir sahnede kontrol et, ardından tam videoyu kodla. Profillerini kaydet, sonraki işlerinde yeniden kullan veya profil koduyla paylaş.

Kodlama kuyruğunda işleri durdurup devam ettirebilir; geçen süreyi, tahmini kalan zamanı ve oluşan dosyanın boyutunu takip edebilirsin. Tamamlanan videoyu uygulamanın içindeki oynatıcıda açabilirsin.

## Kurulum

1. [Son sürümü aç](https://github.com/YavieSama/samalate-releases/releases/latest) ve **Assets** bölümündeki `.exe` kurulum dosyasını indir.
2. EXE'yi çalıştırıp kurulumu tamamla.
3. SamaLate'i aç; dosyanı ekleyip kullanmak istediğin bölümü seç.

**Platform:** Windows x64.

Çeviri için Ayarlar'dan desteklenen bir servis veya uyumlu API adresi, model ve kendi API anahtarını tanımlaman gerekir. API kullanım bedeli ve erişim koşulları seçtiğin sağlayıcıya bağlıdır.

Video işleme bilgisayarında yapılır. Çeviri sırasında altyazı metni seçtiğin API sağlayıcısına gönderilir.

Upscale hızlandırma seçenekleri donanımının desteğine bağlıdır. Eksik CUDA veya TensorRT bileşenleri ilk kullanımda indirilip hazırlanabilir; bu nedenle ilk işlem daha uzun sürebilir. Sonraki işlemler hazırlanan bileşenleri yeniden kullanır.

## Kurmadan önce keşfet

[samalate.com](https://samalate.com/) üzerinde kodlama, çeviri, önizleme ve araçlar bölümlerini örnek dosyalarla inceleyebilirsin. 4K karşılaştırma alanında model seçip ayırıcıyı sürükleyerek kaynak görüntüyle upscale sonucunu karşılaştırabilirsin.

Sitedeki uygulama demosu hazır örneklerle çalışır; kişisel video dosyalarını işlemek için Windows uygulamasını kullan.

## Güncellemeler ve geri bildirim

Yeni sürümleri uygulamanın güncelleme alanından yükleyebilirsin. Kısa sürüm özetleri [yama notları sayfasında](https://samalate.com/yama-notlar%C4%B1) yer alır.

Bir sorunla karşılaşırsan [Issues](https://github.com/YavieSama/samalate-releases/issues) üzerinden uygulama sürümünü, sorunun hangi adımda oluştuğunu ve mümkünse ekran görüntüsünü paylaşabilirsin. API anahtarını veya kişisel bilgilerini paylaşma.

---

Bu depo SamaLate'in resmi Windows kurulumlarını ve kullanım bilgilerini paylaşmak içindir. Uygulamanın kaynak kodu bu depoda yer almaz.

**[YavieSama](https://yaviesama.com) tarafından geliştirildi.**
