# Fmpeg Converter v1 — Sürüm Notları

**The Mechatronic Workshop**

## Özellikler
- Video dosyalarından MJPEG oluşturma
- ESP32 CYD, TFT/LCD, HDMI/Monitor, OLED/AMOLED ve özel çözünürlük seçenekleri
- Sığdır, Doldur, Esnet; döndürme, FPS ve JPEG kalite ayarları
- Hedef ve çıktı önizlemesi (ilk 6 saniye)

## Düzeltmeler
- PowerShell'in özel `$args` değişkeniyle FFmpeg parametrelerinin çakışması giderildi.

## Bilinen sınırlamalar
- Windows ortamında kapsamlı test tamamlanmadı.
- MJPEG çıktı ses içermez.
- FFmpeg dağıtımının lisans yükümlülükleri ayrıca karşılanmalıdır.

**Yayın etiketi: `v1`**