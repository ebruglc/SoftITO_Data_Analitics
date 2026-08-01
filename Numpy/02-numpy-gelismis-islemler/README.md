# 🚀 02 - NumPy İleri Düzey Operasyonlar ve Optimizasyon

Bu proje, NumPy kütüphanesinin temel özelliklerinin ötesine geçerek; **bellek yönetimi, gelişmiş indeksleme, vektörleştirme performans optimizasyonları, yapılandırılmış diziler (structured arrays) ve ileri düzey doğrusal cebir** konularını pratik örneklerle ele alır.

---

## 🛠️ Bu Projede Neler Yapıldı?
* **View ve Copy Farkı:** Slicing işlemlerinin bellek paylaşımı (`view`) üzerindeki etkileri ve `.copy()` ile güvenli bağımsız kopya oluşturma yöntemleri incelendi[cite: 2].
* **Fancy Indexing:** Liste ve array'ler kullanılarak esnek indeks seçimi ve sıralama işlemleri uygulandı[cite: 2].
* **np.where ile Koşullu Mantık:** Döngü kullanmaksızın koşullu atamalar ve hızlı filtreleme senaryoları gerçekleştirildi[cite: 2].
* **Sıralama ve Tekilleştirme:** `sort`, `argsort` (indeks sıralaması) ve `unique` (tekil değerler ile frekans analizi) fonksiyonları kullanıldı[cite: 2].
* **Array Birleştirme & Bölme:** `concatenate`, `vstack`, `hstack` ve `split` fonksiyonlarıyla matris manipülasyonları yapıldı[cite: 2].
* **Axis (Eksen) Derinlemesine Analiz:** 2D ve 3D (küp) diziler üzerinde `axis` parametresinin çalışma mantığı detaylandırıldı[cite: 2].
* **Vektörleştirme Performansı:** Saf Python döngüleri ile NumPy vektörleştirilmiş işlemler arasındaki hız ve performans farkı kıyaslandı[cite: 2].
* **Universal Functions (ufunc):** Hazır matematiksel ufunc'lar incelendi ve `np.vectorize` ile özel fonksiyonlar optimize edildi[cite: 2].
* **Structured Array'ler:** Farklı veri tiplerini (isim, yaş, boy) tek bir matris yapısında tutan yapılandırılmış diziler oluşturuldu[cite: 2].
* **İleri Düzey Doğrusal Cebir:** `np.linalg.eig` ile özdeğer/özvektör hesaplama ve `np.linalg.solve` ile doğrusal denklem sistemleri çözüldü[cite: 2].
* **Girdi/Çıktı (I/O) İşlemleri:** `np.save` ve `np.savez` kullanılarak verilerin ikili (binary) formatta diske kaydedilmesi ve okunması sağlandı[cite: 2].
* **Maskeleme ile Veri Temizleme:** Eksik (`NaN`) ve aykırı (outlier) değerlerin mantıksal maskeleme teknikleriyle temizlendiği gerçekçi bir senaryo çalışıldı[cite: 2].

---

## 💻 Kullanılan Teknolojiler
* **Python** (v3.12+)
* **NumPy** (v2.4.4+)
* **Geliştirme Ortamı:**  Google Colab

---

## 📂 Dosya Yapısı
```text
02-numpy-ileri-duzey/
├── README.md                 # Proje açıklama dosyası.
└── numpy_ileri_duzey.ipynb   # Satır satır açıklamalı ileri düzey NumPy kod notebook'u.