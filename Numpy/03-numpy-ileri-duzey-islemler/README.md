# ⚡ 03 - NumPy Uzman Düzey & Performans Optimizasyonu

Bu projede, NumPy kütüphanesinin en gelişmiş özellikleri; bellek içi veri düzenleri (`strides`), ileri düzey tensör operasyonları, donanım/bellek sınırlarını aşan büyük veri yönetimi ve özel optimizasyon teknikleri sıfırdan oluşturulan örnekler üzerinde pratik edilmiştir[cite: 2].

---

## 🛠️ Bu Projede Neler Yapıldı?
* **Bellek Düzeni (`strides`, C-order, F-order):** Dizilerin bellekteki ardışık yapısı incelenmiş, `transpose` ve `reshape` gibi işlemlerin neden bellek kopyalamadan (ücretsiz) gerçekleştiği `strides` mantığıyla analiz edilmiştir[cite: 2].
* **Gelişmiş Broadcasting & `np.newaxis`:** Boyut ekleme teknikleri ve çok boyutlu diziler arasında otomatik uyumlandırma kurallarıyla ikili mesafe/fark matrisleri oluşturulmuştur[cite: 2].
* **Kayan Pencere İşlemleri (`Sliding Window`):** `sliding_window_view` kullanılarak döngü yazmadan zaman serisi üzerinde hareketli ortalama hesaplamaları yapılmıştır[cite: 2].
* **`einsum` ile Tensör İşlemleri:** Einstein toplama notasyonu ile matris çarpımı, iz (`trace`) ve nokta çarpım işlemleri tek bir esnek sözdizimiyle ifade edilmiştir[cite: 2].
* **Maskeli Array'ler (`np.ma`):** Geçersiz veya hatalı verilerin silinmeden, maskeleme mekanizmalarıyla hesaplamalardan nasıl hariç tutulacağı çalışılmıştır[cite: 2].
* **Modern Rastgelelik (`Generator` API):** Eski `seed` yöntemi yerine modern ve bağımsız `default_rng()` üreteci ile dağılımlar ve simülasyonlar gerçekleştirilmiştir[cite: 2].
* **Hızlı Fourier Dönüşümü (FFT):** Zaman serisi verilerinden `np.fft` kullanılarak gizli frekans bileşenleri ve baskın sinyaller çıkarılmıştır[cite: 2].
* **Polinom Uydurma (`Curve Fitting`):** `np.polyfit` ve `np.poly1d` ile gürültülü verilere en uygun eğri denklemi uydurulmuştur[cite: 2].
* **Tarih ve Zaman Aritmetiği:** `datetime64` ve `timedelta64` tipleriyle verimli tarih aralığı üretme ve zaman farkı hesaplamaları yapılmıştır[cite: 2].
* **Kısmi Sıralama (`argpartition`):** Tam sıralamaya (`sort`) kıyasla büyük dizilerde en büyük/küçük $k$ elemanı bulmada sağlanan büyük performans kazanımı incelenmiştir[cite: 2].
* **Eksen Bazlı Özel Fonksiyonlar:** `apply_along_axis` ile özel kullanıcı tanımlı fonksiyonların belirli eksenler boyunca nasıl koşturulacağı uygulanmıştır[cite: 2].
* **Bellek Sınırlarını Aşan Veriler (`memmap`):** RAM kapasitesine sığmayan devasa veri setlerinin `np.memmap` ile disk üzerinden parça parça ve güvenli bir şekilde işlenmesi sağlanmıştır[cite: 2].

---

## 💻 Kullanılan Teknolojiler
* **Python** (v3.12+)
* **NumPy** (v2.4.4+)
* **Geliştirme Ortamı:** Google Colab

---

## 📂 Dosya Yapısı
```text
03-numpy-uzman-duzey/
├── README.md               # Proje açıklama dosyası
└── numpy_uzman_duzey.ipynb # Satır satır açıklamalı uzman düzey NumPy kod notebook'u