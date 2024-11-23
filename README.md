# Steam-Games-Data-Analysis

![Steam Logo](https://upload.wikimedia.org/wikipedia/commons/8/83/Steam_icon_logo.svg)  

Bu proje, Steam oyunlarına dair kapsamlı bir veri analizi çalışmasını içerir. Veriler, oyunların kullanıcı puanları, çıkış tarihleri, geliştiriciler, yayıncılar ve inceleme metinleri gibi bilgilerini kapsamaktadır. Çalışmada, oyun dünyasında trendleri anlamak ve ileriye dönük stratejiler geliştirmek için çeşitli analiz ve görselleştirmeler yapılmıştır.  

---

## Proje Özeti  

- **Popüler Oyunlar:** En yüksek puanlı oyunlar analiz edilmiştir.  
- **Çıkış Tarihi Analizleri:** Oyunların hangi dönemlerde daha fazla yayımlandığı incelenmiştir.  
- **Geliştirici ve Yayıncı İncelemeleri:** Başarıya en çok katkı sağlayan geliştirici ve yayıncılar belirlenmiştir.  
- **Kullanıcı İncelemeleri:** İnceleme metinlerinden önemli kelimeler ve ifadeler görselleştirilmiştir.  

---

## Verinin Genel Yapısı  

**Veri Setinin Sütunları (Öne Çıkanlar):**  

| Sütun Adı                      | Veri Sayısı (Non-Null) | Veri Tipi  |  
|--------------------------------|------------------------|------------|  
| Ad                             | 637                    | Object     |  
| Çıkış Tarihi                   | 634                    | Object     |  
| Geliştirici                    | 636                    | Object     |  
| Yayıncı                        | 643                    | Object     |  
| Genel Puan (rank)              | 637                    | Float64    |  
| Kullanıcı İnceleme Sayısı      | 641                    | Int64      |  
**Veri tipi dagilimi:** `float64(1)`, `int64(1)`, `object(4)` 
**Bellek Kullanımı:** ~3.9+ MB  

---

## Öne Çıkan Bulgular  

- **Çıkış Tarihi Trendleri:** En fazla oyun, özellikle **Ekim** ayında yayımlanmıştır.  
- **Popüler Türler:** Aksiyon ve macera türleri, kullanıcılar arasında en popüler kategoriler olarak öne çıkmaktadır.  
- **Geliştirici ve Yayıncı Etkisi:** Büyük geliştiriciler (örneğin Valve), oyun puanlarını önemli ölçüde etkilerken küçük stüdyoların yüksek başarıya ulaşma oranı daha düşüktür.  
- **Kelime Bulutu Çalışması:** Kullanıcı incelemelerinde en çok kullanılan kelimeler; "amazing", "boring", ve "fun" gibi güçlü ifadeleri içermektedir.  

---

## Projenin Amacı ve Yöntemi  

Bu projede, oyun geliştirme sürecine dair değerli içgörüler elde edilmesi amaçlanmıştır. Veriler, **Kesifsel Veri Analizi (EDA)** yöntemleriyle detaylı bir şekilde incelenmiştir. İleride bu analizlerin daha ileri düzeye taşınarak makine öğrenmesi uygulamaları ile desteklenmesi hedeflenmektedir.  

**Hedefler:**  

1. **Kullanıcıların Tercihlerini Anlamak:** Hangi türlerin ve temaların daha fazla ilgi çektiğini analiz etmek.  
2. **Başarının Faktörlerini Belirlemek:** Yüksek kullanıcı puanlarına ulaşan oyunların ortak noktalarını bulmak.  
3. **Gelecek İçin Strateji Geliştirme:** İleride çıkacak oyunların maksimum başarıya ulaşabilmesi için veri odaklı öneriler geliştirmek.  

---

## Kullanılan Araçlar ve Kütüphaneler  

- **Python:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `WordCloud`  
- **Veri Seti:** [Steam Games Reviews and Rankings](https://www.kaggle.com/datasets/mohamedtarek01234/steam-games-reviews-and-rankings)  
- **IDE:** Jupyter Notebook  

---

## İlerleyen Çalışmalar  

1. **Sentiment Analysis:** Kullanıcı incelemelerindeki yorumların duygu analizi yapılması.  
2. **Makine Öğrenmesi ile Öngörü:** Yeni oyunların başarı şansını tahmin edebilecek bir model geliştirilmesi.  
3. **Pazar Analizleri:** Oyun dünyasındaki trendlerin tespiti için veri bilimi yöntemlerinin kullanılması.  

---

## Kaggle Linki  

[Steam Games Data Analysis on Kaggle]([https://www.kaggle.com/datasets/mohamedtarek01234/steam-games-reviews-and-rankings](https://www.kaggle.com/code/batude/steam-games-data-analysis))  

**Not:** Bu proje, hem oyun geliştirme sürecine katkıda bulunmak hem de veri analizi alanında yetkinlik kazanmak için tasarlanmıştır.  
