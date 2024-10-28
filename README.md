# Saglik-Sigorta-Primleri-Dogrusal-Regresyon-
Proje Özeti
Bu proje, doğrusal regresyon kullanarak bireylerin yaşlarına göre sağlık sigortası primlerini tahmin etmeyi amaçlar. Sağlık sigortası verilerini kullanarak yaş ile prim maliyeti arasındaki ilişkiyi analiz ediyoruz.Basit düzeydedir bunun sebebi makine öğrenimine yeni girmiş bulunmaktayım ve konuyu anlamak için yaptığım basit bir projedir.

Veri Seti
Veri seti, yaş, cinsiyet, vücut kitle indeksi (BMI), çocuk sayısı, sigara kullanımı, bölge ve sigorta maliyetleri gibi özellikleri içermektedir. Bu çalışmada, yalnızca yaş ve sigorta maliyeti arasındaki ilişki basit doğrusal regresyon ile incelenmiştir.

Yaş (age): Bireyin yaşı
Sigorta Primi (charges): Bireyin yıllık sağlık sigortası maliyeti
Kullanılan Kütüphaneler
Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

pandas: Veri işleme ve analiz
scikit-learn: Model oluşturma ve değerlendirme
matplotlib: Görselleştirme
Adımlar
Veri Ön İşleme: Gerekli kütüphaneler yüklenmiş ve veri seti incelenmiştir. Eksik veriler kontrol edilip çıkarılmıştır.
Veri Ayırma: Veri seti eğitim ve test olarak ayrılmıştır (test boyutu %20 olarak ayarlanmıştır).
Model Eğitimi: Doğrusal regresyon modeli eğitilmiş ve yaş ile sigorta primi arasındaki ilişkiyi öğrenmiştir.
Tahmin Yapma: Test verileri ile sigorta primi tahmin edilmiştir.
Model Değerlendirme: Modelin performansı Mean Squared Error (MSE) ve R-Kare (R²) metrikleri ile değerlendirilmiştir.
MSE: Modelin tahminlerinin doğruluğunu ölçer, daha düşük değerler daha iyi sonuçları gösterir.
R²: Modelin bağımlı değişkenin (sigorta primi) varyansını ne kadar iyi açıkladığını gösterir, 1’e yakın değerler daha iyi performansı ifade eder.
