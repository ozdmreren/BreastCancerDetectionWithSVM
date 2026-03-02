## Makine Öğrenmesi ile Meme Kanseri Sınıflandırması
 ### Projenin Amacı

Bu proje, meme kanseri verileri üzerinde makine öğrenmesi sınıflandırma tekniklerinin uygulanmasını amaçlamaktadır. Çalışmada veri analizi yapılmış, bir model eğitilmiş ve model performansı çeşitli doğrulama metrikleri ile değerlendirilmiştir.

Kullanılan veri seti:
Breast Cancer Wisconsin Dataset

### 📊 Veri Seti Hakkında

Veri seti, meme kitlelerinden elde edilen hücresel ölçümleri içermektedir.

Hedef değişken:

Malignant (M) → Kötü huylu tümör

Benign (B) → İyi huylu tümör

Bu problem bir ikili sınıflandırma (binary classification) problemidir.

🛠 Kullanılan Teknolojiler

- Python

- NumPy

- Pandas

- Scikit-learn

- Matplotlib

- Seaborn

### 📈 Model Değerlendirme Metrikleri

Model performansını değerlendirmek için aşağıdaki metrikler kullanılmıştır:

1. Accuracy (Doğruluk)

Modelin tüm tahminleri içerisindeki doğru tahmin oranını gösterir.

Formül:

Accuracy = (TP + TN) / (TP + TN + FP + FN)

TP → True Positive

TN → True Negative

FP → False Positive

FN → False Negative

Modelin genel başarı oranını gösterir ancak veri dengesiz ise tek başına yeterli değildir.

2. Precision (Kesinlik)

Modelin pozitif olarak tahmin ettiği örneklerin gerçekten pozitif olma oranını gösterir.

Formül:

Precision = TP / (TP + FP)

3. Recall (Duyarlılık)

Gerçek pozitiflerin ne kadarının doğru tahmin edildiğini gösterir.

Formül:

Recall = TP / (TP + FN)

4. F1 Score

Precision ve Recall değerlerinin dengeli ortalamasıdır.

Formül:

F1 Score = 2 × (Precision × Recall) / (Precision + Recall)

### 🔎 Confusion Matrix (Karışıklık Matrisi)

Confusion Matrix, modelin yaptığı doğru ve yanlış tahminleri tablo şeklinde gösterir:

Gerçek Pozitif	TP	FN
Gerçek Negatif	FP	TN

Bu matris sayesinde modelin hangi tür hataları yaptığı detaylı şekilde analiz edilebilir.

### 📊 Görselleştirme

Model performansı ve veri analizi sürecinde:

Korelasyon matrisi

Özellik dağılımları

Confusion matrix heatmap

Performans karşılaştırma grafikleri

Matplotlib ve Seaborn kütüphaneleri kullanılarak görselleştirilmiştir.

🚀 Sonuç

Bu proje kapsamında meme kanseri verileri üzerinde bir sınıflandırma modeli geliştirilmiş ve performansı accuracy, precision, recall ve F1 score metrikleri ile değerlendirilmiştir. Yapay Zekâ uygulamarında yalnızca doğruluk (accuracy) değerine bakmak yanıltabilir bundan dolayı; recall ve F1 score gibi metriklerin de dikkate alınmalıdır.
