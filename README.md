# Fmpeg Converter v1

**The Mechatronic Workshop** tarafından geliştirilen Windows video dönüştürme ve ekran önizleme aracı.

## Özellikler
- MP4, MOV, MKV, AVI ve FFmpeg destekli diğer videolar
- MJPEG (`.mjpeg`) çıktı
- ESP32 CYD, TFT/LCD, HDMI/Monitor, OLED/AMOLED ve özel çözünürlük profilleri
- Sığdır, Doldur, Esnet; döndürme, FPS ve JPEG kalite ayarları
- Hedef ekran ve dönüştürülmüş MJPEG önizlemesi (ilk 6 saniye)

## Kurulum ve kullanım
1. [Releases](../../releases) bölümünden **v1** Windows paketini indirin (yayınlandığında).
2. Arşivi tamamen çıkarın; `engine` klasörü uygulamayla aynı dizinde kalmalıdır.
3. `Fmpeg Converter.exe` dosyasını açın.
4. Kaynak video ve MJPEG çıktı yolunu seçin.
5. Çözünürlük, yerleşim, döndürme, FPS ve kaliteyi ayarlayın.
6. **HEDEF ÖNİZLEME** ve **MJPEG DÖNÜŞTÜR** seçeneklerini kullanın.

Windows PowerShell 5.1 ve Windows Forms gerektirir. Python gerekmez.

## ESP32 CYD
ESP32-2432S028 için örnek çözünürlük: dikey 240×320 veya yatay 320×240. Başlangıç için 20 FPS ve JPEG kalite 7 deneyebilirsiniz.

## Notlar
- Bu **v1 önizleme sürümüdür**; kapsamlı Windows testi yapılmamıştır.
- Çıktı MJPEG'dir, ses içermez. HDMI profili HDMI sinyali üretmez.
- Önizleme gerçek panel renklerini birebir garanti etmez.
- FFmpeg lisans ve kaynak kod yükümlülükleri için: https://ffmpeg.org/legal.html
- Proje kaynak kodu için henüz ayrı bir lisans belirtilmemiştir.

**The Mechatronic Workshop**