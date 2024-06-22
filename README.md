# MNIST El Yazısı Rakam Sınıflandırma Projesi
Bu proje, MNIST veri setini kullanarak el yazısı rakamların sınıflandırılması için Convolutional Neural Network (CNN) modelinin TensorFlow ve PyTorch kütüphaneleri ile nasıl oluşturulacağını ve eğitileceğini göstermektedir.

## Proje İçeriği

- MNIST Veri Seti:

28x28 piksel boyutunda 70,000 el yazısı rakam görüntüsünden oluşur.
60,000 eğitim ve 10,000 test görüntüsü içerir.

- CNN Modeli:

İki farklı derin öğrenme kütüphanesi kullanılarak oluşturulmuştur:

- TensorFlow (Keras API'si ile)
- PyTorch

### Performans Metrikleri:

- F1 Skoru
- ROC AUC
- Mean Absolute Error (MAE)
- Doğruluk

### Eğitim ve Değerlendirme:

- Model eğitimi ve doğrulama süreci
- Eğitim ve doğrulama kaybı ile doğruluk grafikleri
- Rastgele tahminlerin görselleştirilmesi

## Gereksinimler
- Python 3.x
- TensorFlow
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn

## Sonuçlar ve Gelecek Çalışmalar

### Modelin Genel Performansı ve Elde Edilen Sonuçlar:

- Model, MNIST veri setinde yüksek performans göstermiştir.
- F1 skoru, ROC AUC ve doğruluk gibi metriklerde başarılı sonuçlar elde edilmiştir.

### Gelecek Çalışmalar İçin Öneriler ve Geliştirme Alanları:

- Modelin daha karmaşık veri setlerinde test edilmesi.
- Veri artırma (data augmentation) teknikleri kullanarak modelin genelleme yeteneğinin artırılması.
- Daha derin ve karmaşık CNN mimarileriyle performansın karşılaştırılması.
- Hiperparametre optimizasyonu için daha geniş bir arama alanı kullanılması.
