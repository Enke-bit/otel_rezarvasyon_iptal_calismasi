# Lead Time Tahmini

Bu proje, otel rezervasyon verileri kullanarak yıllara göre lead time (rezervasyon öncesi süre) dağılımını görselleştirmekte ve 2017 ile 2019 yılları arasındaki lead time değerlerini tahmin etmekte kullanılmıştır. Lineer regresyon modeli kullanılarak tahminler gerçekleştirilmiştir.

## İçindekiler

- [Projeyi Kurma](#projeyi-kurma)
- [Veri Seti](#veri-seti)
- [Model Eğitimi](#model-eğitimi)
- [Görselleştirme](#görselleştirme)
- [Sonuçlar](#sonuçlar)
- [Yapılandırma](#yapılandırma)

## Projeyi Kurma

Projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. **Gerekli Kütüphanelerin Kurulumu**

   Projeyi çalıştırabilmek için gerekli kütüphaneleri kurmanız gerekmektedir. Aşağıdaki komutu çalıştırarak gerekli kütüphaneleri yükleyin:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn


2. **Veri Setini Yükleme**

Verilerinizi bir CSV dosyasından yüklemek için pandas kütüphanesini kullanabilirsiniz. Veri setinizi data.csv olarak adlandırarak aynı klasöre koyun.

## Veri Seti
Veri seti, otel rezervasyonlarına ait bilgileri içermektedir. Başlıca sütunlar şunlardır:

- arrival_date_year: Rezervasyonun yapıldığı yıl
- lead_time: Rezervasyon öncesi süre

 ##  Sonuçlar
Bu model, 2017, 2018 ve 2019 yılları için lead time tahminlerini başarıyla gerçekleştirmiştir. Gerçek ve tahmin edilen değerler grafikte karşılaştırılabilir.

## Yapılandırma
Projeyi özelleştirmek veya genişletmek için aşağıdaki adımları takip edebilirsiniz:

- Veri Setini Güncelleme: Yeni verilerle modelinizi yeniden eğitebilirsiniz.
- Modeli İyileştirme: Daha karmaşık modeller veya farklı regresyon teknikleri deneyebilirsiniz.

  ## Yazarlar
İbrahim Püsküllü
## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.
