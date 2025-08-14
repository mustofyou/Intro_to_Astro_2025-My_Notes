# Astronomi Kursu Öğrenme Sözlüğü

## 1️⃣ Komut Satırı & Unix Araçları

| Terim | Açıklama | Önemli Not |
|-------|----------|------------|
| `ls` | Bulunduğun dizindeki dosya ve klasörleri listeler. | `ls -l` detaylı, `ls -a` gizli dosyalar. |
| `cd` | Dizin değiştirir. | `cd ..` bir üst klasöre çıkar. |
| `pwd` | Şu an bulunduğun dizini gösterir. | Çalışma konumunu kontrol etmek için kullanılır. |
| `mkdir` | Yeni klasör oluşturur. | `mkdir -p` ile iç içe klasörler oluşturulabilir. |
| `cp` | Dosya veya klasör kopyalar. | `cp -r` klasör kopyalamak için. |
| `mv` | Dosya taşır veya yeniden adlandırır. | Veri düzenleme sürecinde çok kullanılır. |
| `rm` | Dosya veya klasör siler. | `rm -r` klasör siler, dikkatli kullanılmalı. |
| `grep` | Metin içinde arama yapar. | Büyük veri dosyalarında filtreleme için çok hızlıdır. |
| `wc` | Satır, kelime, karakter sayar. | `wc -l` satır sayısını verir. |
| `chmod` | Dosya izinlerini değiştirir. | Çalıştırılabilir script yapmak için (`chmod +x`). |
| `curl` / `wget` | Web’den dosya indirir. | API verisi çekmek için kullanılır. |
| `man` | Komutların kullanım kılavuzunu gösterir. | Terminal yardım kaynağı. |

---

## 2️⃣ Python & Veri Analizi Kütüphaneleri

| Terim | Açıklama | Önemli Not |
|-------|----------|------------|
| **Jupyter Notebook** | Kod, metin, görsel ve grafiği tek dosyada çalıştırmaya yarar. | Veri analizi ve sunum için ideal. |
| **NumPy** | Sayısal hesaplama kütüphanesi. | `np.array`, `np.mean`, `np.std` en temel fonksiyonlar. |
| **Pandas** | Tablo veri işleme kütüphanesi. | `pd.read_csv`, `.groupby`, `.merge` sık kullanılır. |
| **Matplotlib** | Grafik çizme kütüphanesi. | `plt.plot`, `plt.scatter`, `plt.hist` temel fonksiyonlar. |
| **Astropy** | Astronomi verileri ve koordinat dönüşümü. | FITS dosyası okuma (`astropy.io.fits`). |
| **Scipy** | Bilimsel hesaplama araçları. | İstatistik, optimizasyon ve entegrasyon fonksiyonları var. |
| **RadVel** | Radial velocity verisiyle gezegen yörünge modelleme. | Gezegen kütlesi ve yörünge parametresi çıkarır. |
| **Overleaf / LaTeX** | Bilimsel makale ve rapor yazma sistemi. | Denklemler, tablolar ve referans yönetimi çok güçlüdür. |

---

## 3️⃣ Astronomi Kavramları & Veri Kaynakları

| Terim | Açıklama | Önemli Not |
|-------|----------|------------|
| **Transit Yöntemi** | Gezegen yıldız önünden geçerken yıldız ışığındaki düşüşü ölçme. | Küçük gezegenleri tespit etmede çok başarılı. |
| **Radial Velocity (RV)** | Yıldızın salınımlarını Doppler kayması ile ölçerek gezegen tespiti. | Kütle bilgisi verir. |
| **Direct Imaging** | Gezegenin doğrudan görüntülenmesi. | Nadir ama atmosfer çalışmaları için önemli. |
| **Microlensing** | Arka plan yıldız ışığının yerçekimi merceklemesi ile güçlenmesi. | Uzak ve küçük kütleli gezegenleri bulur. |
| **NASA Exoplanet Archive** | Tüm onaylı dış gezegenlerin resmi veritabanı. | API ile veri çekilebilir. |
| **TESS (Transiting Exoplanet Survey Satellite)** | Geniş alan taraması yapan NASA teleskobu. | Yakın yıldızlardaki küçük gezegenler odaklı. |
| **JWST (James Webb Space Telescope)** | Yüksek hassasiyetli kızılötesi teleskop. | Atmosfer bileşimi tespit edebilir. |
| **ADS (Astrophysics Data System)** | Astronomi makale arama motoru. | Literatür taraması için en güvenilir kaynak. |
| **arXiv** | Ön baskı (preprint) bilimsel makale arşivi. | Güncel araştırmaları hızlıca takip etmek için. |
| **Transmission Spectroscopy** | Bir gezegen yıldızının önünden geçerken yıldız ışığının atmosferden süzülmesiyle oluşan tayfın incelenmesi. | Atmosferde su, metan, karbondioksit gibi moleküllerin varlığı bu yöntemle tespit edilir. |

