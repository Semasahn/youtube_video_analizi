# 🎓 SisterLab Bootcamp 6. Ders Ödevi – YouTube API ile Veri Analizi

Bu proje, SisterLab Bootcamp kapsamında verilen 6. ders ödevidir.  
Proje kapsamında, YouTube Data API kullanılarak bir kanalın (Barış Özcan) videoları analiz edilmiş ve temel istatistikler görselleştirilmiştir.

---

## 📌 Projede Ne Yaptım?

- **Google Cloud Console** üzerinden bir API anahtarı oluşturdum.
- **YouTube Data API v3** servisini aktif hale getirdim.
- Python'da `googleapiclient` kütüphanesini kullanarak YouTube API'ye bağlandım.
- Barış Özcan kanalının ID’si ile kanal bilgilerine eriştim.
- Kanalın videolarının yer aldığı **"uploads" oynatma listesinin ID’sini** aldım.
- Bu liste üzerinden kanalın en güncel **50 videosunun başlığı, yayın tarihi ve video ID'sini** çektim.
- Ardından bu video ID’lerini kullanarak:
  - Her videonun **izlenme sayısı**
  - **beğeni sayısı**
  - **yorum sayısı** gibi istatistikleri aldım.
- Tüm bu verileri `pandas` kullanarak bir tabloya dönüştürdüm.
- Sayısal verileri `int` tipine dönüştürerek analiz edilebilir hale getirdim.
- `matplotlib` ile en çok izlenen 10 videoyu **yatay bar grafik** şeklinde görselleştirdim.

---

## 🎯 Amaç Ne?

Bu ödevle birlikte:

- Gerçek bir API’den veri çekmeyi,
- Bu veriyi yapılandırmayı (veri ön işleme),
- Analiz etmeyi ve anlamlı hale getirmeyi,
- Görsel olarak sunmayı öğrendim.

Tüm işlemler boyunca Python’un veri analizi kütüphanelerini (pandas, matplotlib) kullandım ve YouTube API’nin nasıl çalıştığını adım adım deneyimledim.
