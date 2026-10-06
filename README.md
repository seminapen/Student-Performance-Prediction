# Öğrenci Başarı Tahmini(Lineer_Regression)

Bu proje öğrenci çalışma saatlerinden yola çıkarak tahmini puanlarını belirlemek için Basit Doğrusal Regresyonu kullanır.

Bu projeyi çalıştırmak için aşağıdaki Python kütüphaneleri kullanılır:
- numpy
- pandas
- seaborn
- scikit-learn
- matplotlib

PROJENİN YAPISI
1.	Veri Yükleme:
    o	pandas kullanarak veri setini okuyoruz.
  	
3.	Veriyi Görselleştirme:
    o	seaborn ile öğrencilerin çalışma saatlerine göre puanlarını görselleştiriyoruz.
  	
5.	Veri Setini Ayırma:
    o	Veri setini eğitim ve test setlerine ayırıyoruz. (%80 eğitim, %20 test)

6.	Doğrusal Regresyon Modeli:
    o	scikit-learn kullanarak modeli eğitiyor ve test verisi üzerinde tahminler yapıyoruz.
  	
8.	Sonuçları Görselleştirme:
    o	Gerçek puanları ve tahmin edilen değerleri karşılaştıran bir grafik çiziyoruz.

VERİ SETİ :
Veri seti iki sütundan oluşmaktadır:
Hours: Öğrencilerin çalıştığı saatler.
Scores: Öğrencilerin aldıkları puanlar.
