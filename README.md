# Electricity Price Prediction with Machine Learning

## Proje Hakkında
Bu proje, elektrik fiyatlarını tahmin etmek için makine öğrenmesi tekniklerini kullanmaktadır. Proje, bir CSV dosyasından elektrik fiyatı verilerini okuyarak veri analizi yapar ve çeşitli makine öğrenmesi modelleri kullanarak fiyat tahmini gerçekleştirir.

## İçerik
- Veri Seti: Elektrik fiyatları ve etkilileyen değişkenler hakkında bilgi içerir.
- Veri Analizi: Verinin temizlenmesi, görselleştirilmesi ve korelasyon analizi gibi işlemleri içerir.
- Makine Öğrenmesi Modelleri: Random Forest modeli ile elektrik fiyatı tahmini yapılır. Modelin optimizasyonu ve performans değerlendirmesi gerçekleştirilir.

## Kullanılan Kütüphaneler
- `pandas`: Veri işleme ve analizi için.
- `numpy`: Sayısal hesaplamalar için.
- `scikit-learn`: Makine öğrenmesi algoritmaları ve model değerlendirmesi için.
- `matplotlib` ve `seaborn`: Veri görselleştirmeleri için.

## Adımlar
1. **Veri Okuma**: CSV dosyasından veriyi okuyarak DataFrame oluşturma.
2. **Veri Temizleme**: Eksik verilerin kontrolü ve uygun şekilde işlenmesi.
3. **Özellik Mühendisliği**: Zaman bilgilerini ayrıştırma ve yeni özellikler ekleme.
4. **Veri Görselleştirme**: Elektrik fiyatlarının zaman içindeki değişimi ve değişkenler arası korelasyon analizi.
5. **Model Eğitimi**: Random Forest modelinin eğitilmesi ve optimizasyonu.
6. **Model Değerlendirmesi**: Model performansının RMSE, MAE ve R² skoru ile değerlendirilmesi.
7. **Model Kaydetme**: Eğitilen modelin ve scaler'ın kaydedilmesi.

## Sonuçlar
Proje sonunda, optimize edilmiş Random Forest modeli ile elektrik fiyatlarının tahmini yapılmış ve modelin performansı değerlendirilmiştir. En iyi sonuçlar RMSE: 22.99, MAE: 8.81 ve R² skoru: 0.5932 olarak elde edilmiştir.
