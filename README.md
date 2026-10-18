# VideoAl

YouTube, Instagram, TikTok, X, Facebook, Reddit ve 1000'den fazla siteden videoları **kaynak kalitesinde** indiren Windows ve Mac uygulaması.

- Kaynakta 8K varsa 8K, 4K varsa 4K iner; 1080p ise 1080p. Görüntü yeniden kodlanmaz, kalite düşürülmez.
- İndirme bitince dosyanın gerçek çözünürlüğü kaynakla karşılaştırılır ("kaynakla aynı ✓").
- Panodan otomatik ekleme, sürükle-bırak, aynı anda birden fazla indirme, kapanınca kaldığı yerden devam.
- Sadece ses (orijinal ya da MP3) seçeneği.
- Açık ve koyu tema. Windows sürümü kendini otomatik günceller; Mac sürümü yeni sürüm çıkınca haber verir.

## İndir

**[En son sürüm](https://github.com/yclpixels/videoal-releases/releases/latest)** — sayfanın altındaki "Assets" bölümünden:

### Windows 10 / 11 (64 bit)

1. `VideoAl-Kurulum-<sürüm>.exe` dosyasını indirip çalıştırın. Yönetici izni gerekmez.
2. Windows "Windows bilgisayarınızı korudu" derse **Ek bilgi → Yine de çalıştır**'a basın. Uygulama ücretli kod imzası taşımadığı için bu uyarı çıkar.

### Mac (macOS 11 ve üstü)

- Apple Silicon (M1, M2, M3, M4): `VideoAl-<sürüm>-mac-arm64.dmg`
- Intel işlemcili Mac: `VideoAl-<sürüm>-mac-x86_64.dmg`

Hangisi olduğunu  → **Bu Mac Hakkında**'dan görebilirsiniz ("Yonga: Apple …" = Apple Silicon).

1. .dmg dosyasını açıp **VideoAl**'ı **Applications** klasörüne sürükleyin.
2. İlk açılışta "Apple doğrulayamadı" uyarısı çıkarsa: **Sistem Ayarları → Gizlilik ve Güvenlik → en altta "Yine de Aç"**. Bu bir kez sorulur.

İlk açılışta gerekli ücretsiz bileşenler (ffmpeg, gerekirse Deno) tek onayla indirilir.

## Lisanslar

Kullanılan açık kaynak bileşenler (yt-dlp, FFmpeg, Deno vb.) ve lisansları kurulumla gelen `UCUNCU_TARAF_LISANSLAR.txt` dosyasında listelenir.

VideoAl yalnızca indirme hakkınız olan içerik için kullanılmalıdır. Sitelerin kullanım koşullarına ve telif haklarına uymak kullanıcının sorumluluğundadır.
