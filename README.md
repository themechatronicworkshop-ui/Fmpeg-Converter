# Fmpeg Converter

**The Mechatronic Workshop** tarafından geliştirilen Windows tabanlı video dönüştürme ve ekran önizleme aracı.

> **Preview v1.3 Fixed** — Deneme sürümüdür; Windows üzerinde kapsamlı test henüz tamamlanmamıştır. Uygulama başlığında v1.2 yazabilir.

## Özellikler
- MP4, MOV, MKV, AVI ve FFmpeg'in desteklediği kaynak videolar
- MJPEG (`.mjpeg`) çıktısı (ses aktarılmaz)
- ESP32 CYD, TFT/LCD, HDMI/Monitor, OLED/AMOLED ve özel çözünürlük profilleri
- **Sığdır** (kenar boşlukları olabilir), **Doldur** (kenarlar kırpılabilir), **Esnet** (oran bozulabilir)
- Döndürme, FPS ve JPEG kalite ayarları
- Hedef ekran önizlemesi ve dönüştürülmüş MJPEG önizlemesi (ilk 6 saniye)

## Windows'ta kullanım
1. [Releases](../../releases) bölümünden Windows ZIP paketini indirin (yayınlandığında).
2. ZIP'i tamamen çıkarın; `engine` klasörünü EXE'nin yanında tutun.
3. `Fmpeg Converter.exe` dosyasını çalıştırın.
4. Kaynak videoyu ve hedef `.mjpeg` yolunu seçin.
5. Ekran çözünürlüğü, yerleşim, döndürme, FPS ve kaliteyi ayarlayın.
6. **HEDEF ÖNİZLEME**, ardından **MJPEG DÖNÜŞTÜR** seçeneklerini kullanın.

Windows PowerShell 5.1 ve Windows Forms gerekir. Python kurulumu gerekmez.

## ESP32 CYD için örnek
ESP32-2432S028: dikey **240×320**, yatay **320×240**; başlangıç için **20 FPS** ve **JPEG kalite 7** deneyebilirsiniz. Gerçek cihazda performans video içeriğine göre değişebilir. Arduino'da ekran yönü ayrıca yapılandırılır.

## Sınırlamalar
- Ekran kategorileri çözünürlük profilleridir; donanım sürücüsü veya HDMI/H.264 çıktısı sağlamaz.
- Önizleme gerçek panel renklerini birebir simüle etmez.
- Büyük çözünürlükler mikrodenetleyicide oynatılamayabilir.
- Sorunları GitHub Issues üzerinden bildirebilirsiniz.

## Lisans ve FFmpeg
Uygulama FFmpeg kullanır. FFmpeg derlemesinin lisans koşullarına uyulmalıdır: https://ffmpeg.org/legal.html. GPL derleme dağıtılırken gerekli lisans ve kaynak kod yükümlülükleri karşılanmalıdır. Bu projenin kendi kaynak kodu için henüz ayrıca bir lisans belirtilmemiştir.

**The Mechatronic Workshop**