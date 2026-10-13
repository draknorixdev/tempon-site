# TEMPON · DrakNorix

TEMPON için tanıtım, gizlilik, destek, veri silme, kullanım koşulları ve kapalı beta bilgilendirme sitesi.

Canlı adres: https://draknorixdev.github.io/tempon-site/

Gizlilik politikası: https://draknorixdev.github.io/tempon-site/gizlilik.html

## Yayın

GitHub Pages: `main` dalı, `/docs` klasörü. Statik HTML/CSS; JavaScript, üyelik, izleme veya harici yazı tipi yoktur.

Sayfaları yeniden oluşturmak: `python build_site.py`. Önizleme: `python -m http.server 8766 --directory docs`.

Yalnız bu siteye ait dosyalar yayımlanır. Uygulama kaynakları, gerçek ekran görüntüleri, tester e-postaları, APK/AAB dosyaları, müşteri verileri ve imza anahtarları bu depoya eklenmez.

Politika metni, yayımlanacak uygulamanın veri davranışı değişirse aynı sürümle birlikte güncellenmelidir. Beta bağlantısı hazır olduğunda `build_site.py` içindeki beta durumu ve bağlantıları güncellenir.
