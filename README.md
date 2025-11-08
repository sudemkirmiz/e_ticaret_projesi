#  Proje 1: E-Ticaret Satış Veri Analizi

Bu depo, veri analizi öğrenme yolculuğunun ilk projesi olan E-Ticaret Satış Veri Analizi projesine ait tüm kodları, veri setlerini, görselleri ve nihai raporu içermektedir.

##  Proje Amacı

Sağlanan e-ticaret satış ve müşteri veri setlerini analiz ederek; şirketin satış performansını, popüler ürünlerini ve bölgesel dağılımını (veri setinde şehir bilgisi olmadığı için müşteri segmenti olarak yorumlanmıştır) anlamak amaçlanmıştır.

##  Kullanılan Teknolojiler

* **Programlama Dili:** Python
* **Temel Kütüphaneler:** Pandas, Numpy, Matplotlib
* **Sürüm Kontrolü:** Git & GitHub

##  Analiz Özeti ve Temel Çıktılar

Analiz sırasında veri temizliği, Keşifsel Veri Analizi (EDA) ve görselleştirme adımları uygulanmıştır.

## Öne Çıkan Bulgular:

1.  **En Yoğun Satış Günleri:** Satış hacmi en yüksek günler **Pazartesi** ve **Cumartesi**'dir.
2.  **Müşteri Odak Noktası:** İşlemlerin **%80.6'sı Erkek** müşterilerden gelmektedir. Bu segment, pazarlama stratejisinin ana odağı olmalıdır.
3.  **Veri Temizliği:** Müşteri Yaşı (`customer_age`) sütunundaki hatalı aykırı değer (`2022`), temizlenerek ortalama yaşın **36** olduğu tespit edilmiştir.

### Proje Dosyaları:

| Dosya Adı | Açıklama |
| `ecommerce_analysis.ipynb` | Veri yükleme, temizlik, EDA ve görselleştirme adımlarının uygulandığı ana Python Notebook dosyası. |
| `ANALIZ_RAPORU.md` | Yönetime sunulan, bulguları ve önerileri özetleyen nihai rapor. |
| `cinsiyet_dagilimi.png` | Cinsiyet bazlı işlem sayılarının dağılımını gösteren görsel. |
| `gunluk_satis_dagilimi.png` | Haftanın günlerine göre toplam satış adedini gösteren görsel. |
