# 📊 01 - NumPy Temelleri

Bu projede, Python'da bilimsel hesaplama ve veri bilimi çalışmalarının temel taşı olan **NumPy** kütüphanesinin temel kavramları ve fonksiyonları, örnekler üzerinde pratik edilmiştir.

---

## 🛠️ Bu Projede Ne Yapıldı?
* **Array Oluşturma:** `np.array()` kullanılarak 1 boyutlu (1D) listelerden ve 2 boyutlu (2D) matrislerden array yapıları kuruldu.
* **Array Özellikleri:** `shape`, `ndim`, `size` ve `dtype` öznitelikleriyle dizilerin yapısal özellikleri incelendi.
* **Hazır Fonksiyonlar:** `zeros()`, `ones()`, `eye()`, `arange()` ve `linspace()` fonksiyonları ile özel sayı dizileri ve matrisler üretildi.
* **İndeksleme ve Dilimleme:** Köşeli parantez kullanarak eleman seçme, slicing işlemleri ve boolean (mantıksal) filtreleme yöntemleri uygulandı.
* **Şekillendirme (Reshape):** `reshape()` ve `flatten()` fonksiyonları ile dizilerin boyutları eleman kaybı yaşamadan yeniden düzenlendi.
* **Matematiksel İşlemler & Broadcasting:** Eleman bazlı aritmetik işlemler ve farklı boyutlu dizilerin otomatik uyumlandırma mekanizması (`broadcasting`) incelendi.
* **İstatistiksel Özetler:** `sum()`, `mean()`, `std()`, `min()` ve `max()` fonksiyonları ile axis (eksen) bazlı toplulaştırma hesaplamaları yapıldı.
* **Rastgele Sayı Üretimi:** `np.random` modülü (`rand`, `randint`, `randn`, `seed`) kullanılarak simülasyon verileri üretildi.
* **Doğrusal Cebir:** `np.linalg` alt modülü ile matris çarpımı (`@`), determinant, ters matris (inverse) ve transpoze işlemleri gerçekleştirildi.

---

## 💻 Kullanılan Teknolojiler
* **Python** (v3.12+)
* **NumPy** (v2.4.4+)
* **Geliştirme Ortamı:**  Google Colab 

---

## 📂 Dosya Yapısı
```text
01-numpy-temelleri/
├── README.md               # Proje açıklama dosyası.
└── numpy_temelleri.ipynb   # Satır satır açıklamalı NumPy kod notebook'u.