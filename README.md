# Veri Manipülasyonu ve Görselleştirme Pratikleri (Pandas, Matplotlib, Seaborn)

Bu proje, Python'da veri bilimi süreçlerinin temelini oluşturan tablo birleştirme/şekillendirme işlemleri ile bu verilerden anlamlı grafikler çıkarma (görselleştirme) üzerine oluşturulmuş kapsamlı bir çalışma dizisidir. Çalışmalarda hem sentetik veriler hem de popüler "Olimpiyat Oyunları" (`athlete_events.csv`) veri seti kullanılmıştır.

## 📂 Dosya Yapısı ve İçerikler

Çalışmalar, odaklandıkları konulara göre farklı Jupyter Notebook dosyalarına ayrılmıştır:

### 1. Veri Manipülasyonu (Pandas)
* **`4-DataFrameConcatMerge.ipynb`:** Pandas kütüphanesi kullanılarak farklı veri setlerinin (Örn: Çalışanlar, Departmanlar ve Maaşlar) birleştirilmesi işlemleri yapılmıştır.
  * Alt alta veya yan yana veri ekleme (`pd.concat`).
  * SQL benzeri tablo birleştirme işlemleri: `Inner Join`, `Left Join`, `Right Join` ve `Outer Join` kullanımları (`pd.merge`).

### 2. Veri Görselleştirme (Matplotlib & Seaborn)
* **`Matplotlib.ipynb`:** Matplotlib kütüphanesinin temel mantığını anlamak için NumPy dizileri (arrays) üzerinden oluşturulan temel grafik (çizgi, saçılım vb.) çizimlerini ve figür/eksen (figure/axes) ayarlarını içerir.
* **`Matplotlib_data.ipynb`:** `athlete_events.csv` (Olimpiyat Verisi) veri seti içeriye aktarılarak, gerçek veriler üzerinden Matplotlib ile frekans, dağılım ve trend görselleştirmeleri yapılmıştır.
* **`1--VisualizationSeaborn..ipynb`:** Aynı Olimpiyat veri seti üzerinde, istatistiksel görselleştirme kütüphanesi olan Seaborn kullanılarak daha gelişmiş ve estetik grafikler çizilmiştir. Özellikle sayısal değişkenler arasındaki ilişkiyi gösteren **Korelasyon Isı Haritası (Correlation Heatmap)** `sns.heatmap()` kullanılarak incelenmiştir.

## 📈 Çıktılar ve Görseller
Depo içerisinde, analizler sonucunda üretilmiş çeşitli grafiklerin `.png` formatındaki çıktıları yer almaktadır. Bu görseller, verilerin dağılımını, trendleri ve değişkenler arası korelasyonları sunmak için kaydedilmiştir.

## 🛠️ Kullanılan Teknolojiler

Bu projede aşağıdaki Python kütüphanelerinden yararlanılmıştır:
* **Veri İşleme ve Analiz:** `pandas`, `numpy`
* **Veri Görselleştirme:** `matplotlib.pyplot`, `seaborn`

## ⚙️ Kurulum ve Çalıştırma

Notebook'ları kendi ortamınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install pandas numpy matplotlib seaborn
   
