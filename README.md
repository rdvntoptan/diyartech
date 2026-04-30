# DiyarTech — Diyarbakır Güvenlik & Teknoloji Çözümleri

Profesyonel CCTV, IP kamera, plaka tanıma, alarm, geçiş kontrol, network altyapı, ERP ve web yazılım çözümlerinin tanıtım sitesi.

🌐 **Canlı**: https://diyartech.com.tr  
📞 **İletişim**: 0536 723 12 54  
📍 **Adres**: Medya Mah. Diclekent Bulvarı Bedir 5 No:88 İç Kapı No:9 Kayapınar / Diyarbakır

## 📁 Yapı

Tek başına çalışan **statik HTML** sitesidir. Tüm görseller ve stiller dosyaların içine Base64 olarak gömülmüştür — harici asset / build / sunucu gerekmez.

```
diyartech-site/
├── index.html                              # Ana sayfa
├── calismalarimiz.html                     # Portfolyo
├── hizmet-ip-kamera-sistemleri.html        # CCTV
├── hizmet-plaka-tanima.html                # CCTV
├── hizmet-alarm-sistemleri.html
├── hizmet-gecis-kontrol.html
├── hizmet-altyapi-ag-cozumleri.html        # Network
├── hizmet-erp-yazilim.html
├── hizmet-web-sitesi-kurulumu.html
├── sitemap.xml
└── robots.txt
```

## 🚀 Yayınlama

### Yöntem 1 — GitHub Pages
1. Reponun **Settings → Pages** sekmesine gidin
2. Source: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)` → Save
3. 1-2 dakika sonra `https://kullaniciadi.github.io/diyartech/` adresinde yayında

### Yöntem 2 — Netlify / Vercel
- Repoyu bağlayın → Build command boş → Publish directory: `/`
- Otomatik deploy

### Yöntem 3 — Kendi sunucu / cPanel
- Tüm dosyaları FTP ile `public_html/` klasörüne yükleyin

## 🔍 SEO

- Türkçe meta etiketleri ve `og:` / `twitter:` kartları
- `LocalBusiness` JSON-LD yapısal verisi
- `geo.region` / `geo.placename` (Diyarbakır)
- `sitemap.xml` ve `robots.txt`
- Tüm görsellerde anlamlı `alt` etiketleri

## 📱 Özellikler

- Tam mobil uyumlu (hamburger menü)
- WhatsApp lead toplama formu
- Google Maps konum entegrasyonu
- Hızlı yükleme (statik, CDN gerekmez)

---
© DiyarTech
