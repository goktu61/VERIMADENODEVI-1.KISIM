📊 Telco Customer Churn Analysis – Orange Data Mining

Bu çalışma, bir telekomünikasyon şirketinde müşterilerin hizmeti bırakma olasılığını incelemek amacıyla Orange Data Mining kullanılarak gerçekleştirilmiştir. Analizde müşteri davranışları incelenmiş, veri ön işleme adımları uygulanmış ve farklı makine öğrenmesi modellerinin performansları karşılaştırılmıştır.

🚀 Projenin Amacı

Telekomünikasyon sektöründe müşteri kaybı (churn), şirketlerin gelirini doğrudan etkileyen önemli bir problemdir. Bu projenin temel amacı, geçmiş müşteri verilerini analiz ederek hangi müşterilerin hizmeti bırakma ihtimalinin daha yüksek olduğunu belirlemektir.

Bu kapsamda yapılan çalışmalar:

Veri setindeki eksik değerler tespit edilip uygun yöntemlerle tamamlanmıştır.
Veri seti modelleme için uygun formata getirilmiştir.
Logistic Regression, Random Forest ve Decision Tree algoritmaları uygulanmıştır.
Modellerin performansları çeşitli değerlendirme metrikleri kullanılarak karşılaştırılmıştır.
Churn riski yüksek müşteri segmentleri belirlenmiştir.
🛠 Analiz Süreci (Workflow)

Proje sürecinde Orange platformunda oluşturulan analiz akışı aşağıdaki temel adımlardan oluşmaktadır:

Veri setinin sisteme aktarılması
Değişkenlerin düzenlenmesi ve veri tiplerinin kontrol edilmesi
Eksik değerlerin doldurulması
Analizde kullanılacak değişkenlerin seçilmesi
Veri örneklemesi yapılması
Farklı sınıflandırma algoritmalarının eğitilmesi
Model performanslarının karşılaştırılması

Workflow diyagramı aşağıda gösterilmektedir.

<img width="1883" height="906" alt="1Ekran Alıntısı" src="https://github.com/user-attachments/assets/ca0ae86a-db6a-4c4c-a597-e9b53acc06ca" />


📈 Model Performans Analizi

Kurulan modeller 5-Fold Cross Validation yöntemi ile değerlendirilmiştir. Bu yöntem, veri setini farklı parçalara bölerek modelin daha güvenilir bir şekilde test edilmesini sağlar.

Performans değerlendirmesinde kullanılan metrikler:

AUC (Area Under Curve) – Modelin sınıfları ayırt etme başarısını ölçer.
CA (Classification Accuracy) – Modelin doğru tahmin oranını gösterir.
F1 Score – Precision ve Recall değerlerinin dengeli ortalamasını ifade eder.

Sonuçlara göre modeller arasında performans farklılıkları gözlemlenmiş ve en başarılı algoritma belirlenmiştir.

🔍 Analiz Sonuçları
Sözleşme Türüne Göre Churn Davranışı

Yapılan analizler sonucunda aylık sözleşmeye sahip müşterilerin, uzun süreli sözleşme yapan müşterilere göre hizmeti bırakma olasılığının daha yüksek olduğu görülmüştür. Taahhüt süresinin kısa olması müşterilerin alternatif hizmetlere geçmesini kolaylaştırmaktadır.

<img width="1137" height="738" alt="2Ekran Alıntısı" src="https://github.com/user-attachments/assets/a29b2d2e-691c-416f-b247-5b4432ff1c7b" />


Yüksek Riskli Müşteri Segmenti

Karar ağacı modeli incelendiğinde en yüksek churn riskine sahip müşteri grubunun şu özellikleri taşıdığı görülmüştür:

Month-to-Month sözleşme kullanımı
Şirkette 6 aydan daha az süredir bulunma
Fiber Optic internet hizmeti kullanma

Bu segmentte yer alan müşterilerin kaybedilme olasılığı diğer müşteri gruplarına göre daha yüksektir.
