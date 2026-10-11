Chn SRPR — İş Takip & Raporlama

GitHub Pages'e yüklenecek dosyalar:
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

GitHub deposunun ana dizinine bu dosyaların tamamını yükleyin.
Ardından Settings > Pages bölümünde Deploy from a branch, branch main ve folder /(root) seçin.

ÖNEMLİ SUPABASE NOTU:
index.html içindeki SUPABASE_URL ve SUPABASE_ANON_KEY değerleri yer tutucudur.
Bu nedenle bu paket tek başına Supabase üzerinden cihazlar arası eşitlemeyi etkinleştirmez.
Önceki canlı projedeki gerçek bağlantı ayarları güvenli şekilde eklenip eşitleme test edilmelidir.
Yerel tarayıcı kayıtları ve çevrimdışı çalışma davranışı cihaz/tarayıcıya bağlıdır; site verileri temizlenirse yerel kayıtlar kaybolabilir. Düzenli yedek alın.
