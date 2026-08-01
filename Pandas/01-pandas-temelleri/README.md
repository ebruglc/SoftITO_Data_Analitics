# 📊 01 - Pandas Temelleri ve Netflix Top 10 Veri Analizi

Bu projede, Python'da veri manipülasyonu ve analitiğinin temel taşı olan **Pandas** kütüphanesinin temel özellikleri, gerçek dünya verisi olan **Netflix Top 10 Ülke Bazlı İzlenme ve Sıralama Veri Seti** (`netflix_top10_country.csv` / `.xlsx`) üzerinden adım adım ve pratik edilmiştir.

---

## 🛠️ Bu Projede Ne Yapıldı?
* **Series ve DataFrame:** Pandas'ın temel veri yapıları tanıtıldı; tek boyutlu diziler (`Series`) ve iki boyutlu tablolar (`DataFrame`) oluşturuldu.
* **Veri Okuma ve Yazma:** Harici `.csv` ve `.xlsx` formatındaki veri setleri `pandas` kullanılarak belleğe yüklendi ve farklı formatlarda diske kaydedildi.
* **Veri Yapısını İnceleme:** `head()`, `info()`, `describe()`, `shape` ve `columns` fonksiyonları ile devasa veri setinin genel yapısı, sütun tipleri ve istatistiksel özetleri çıkarıldı.
* **Seçme ve Filtreleme (`.loc`, `.iloc`):** Köşeli parantez notasyonları, etiket ve konum bazlı filtreleme teknikleriyle istenen satır ve sütunlar izole edildi.
* **Çoklu Koşullu Filtreleme:** Mantıksal operatörler (`&`, `|`) kullanılarak spesifik kategori ve sıralama filtrelemeleri uygulandı.
* **Veri Düzenleme & Özellik Türetme:** Mevcut sütunlardan matematiksel mantıkla yeni özellikler türetildi (örn. haftalık sıralama ve kalış süresine bağlı **`performance_score`** hesaplandı).
* **Koşullu Etiketleme (`.apply()`):** Lambda fonksiyonları yardımıyla satır bazlı kategorik etiketlemeler yapıldı (örn. yüksek/düşük performans sınıflaması).
* **Sıralama ve Gruplama (`groupby` & `agg`):** Ülkelere ve dizi/film isimlerine göre gruplama yapılarak toplam/ortalama performans skorları ve kayıt istatistikleri çıkarıldı.
* **Tablo Birleştirme (`Concat` & `Merge`):** Alt alta veri birleştirme (`concat`) ve harici kategorik/bölgesel sözlük tablolarıyla ana veri setini zenginleştirme (`merge`) işlemleri gerçekleştirildi.

---

## 💻 Kullanılan Teknolojiler
* **Python** (v3.12+)
* **Pandas** (v2.2+)
* **Geliştirme Ortamı:** Google Colab 

---

## 📂 Dosya Yapısı
```text
01-pandas-temelleri/
├── README.md                     # Proje açıklama dosyası
└── 01-pandas-temelleri.ipynb     # Satır satır açıklamalı Pandas eğitim notebook'u