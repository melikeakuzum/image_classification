# 🐾 Hayvan Sınıflandırma Modeli

Bu proje, 10 farklı hayvan sınıfını sınıflandırmayı amaçlayan bir derin öğrenme modeli geliştirme sürecini içerir. Modelimiz, çeşitli görsel manipülasyonlara karşı test edilerek dayanıklılığı değerlendirilmiştir. 🎯

## 📖 İçerik

- [🔍 Proje Hakkında](#-proje-hakkında)
- [🛠️ Kullanılan Teknolojiler](#️-kullanılan-teknolojiler)
- [📊 Veri Seti](#-veri-seti)
- [📈 Model Eğitimi ve Test Sonuçları](#-model-eğitimi-ve-test-sonuçları)
- [🚀 Geliştirme Süreci](#-geliştirme-süreci)
- [💡 Yapılacak İyileştirmeler](#-yapılacak-iyileştirmeler)

---

## 🔍 Proje Hakkında

**Hayvan Sınıflandırma Modeli**, derin öğrenme teknikleri kullanarak görsel veriler üzerinden 10 farklı hayvan türünü sınıflandırmayı hedefler. Modelimiz, manipüle edilmiş veri setleri üzerinde test edilerek görsel değişimlere dayanıklılığı değerlendirilmiştir.



## 🛠️ Kullanılan Teknolojiler

Bu projede kullanılan temel araç ve kütüphaneler şunlardır:

- **🧠 TensorFlow/Keras**: Derin öğrenme modelini oluşturmak için.
- **📊 NumPy**: Veri işleme ve manipülasyon için.
- **📈 Matplotlib & Seaborn**: Sonuçların görselleştirilmesi için.
- **🎨 OpenCV**: Görsel verilerin manipülasyonu ve analizi için.

---

## 📊 Veri Seti

Modelin eğitimi, 10 farklı hayvan sınıfından oluşan görsellerden faydalanarak yapılmıştır. Veri seti; normal, manipüle edilmiş ve renk sabitliği uygulanmış olmak üzere üç farklı test setine ayrılmıştır.

### 🔄 Manipülasyon Türleri

- **Işık Koşulları Değişiklikleri**: Modelin farklı ışıklandırma ortamlarına karşı dayanıklılığı test edilmiştir.
- **Renk Sabitliği**: Renk manipülasyonları ile modelin dayanıklılığı ölçülmüştür.

---

## 📈 Model Eğitimi ve Test Sonuçları

Modelin test sonuçları aşağıdaki gibi değerlendirilmiştir:

1. **🌟 Normal Test Seti Başarısı**: `0.1108` (yaklaşık %11)  
   - Modelin temel doğruluğu.  

2. **💡 Manipüle Edilmiş Test Seti Başarısı**: `0.1026` (yaklaşık %10)  
   - Işık koşulları değiştikten sonraki doğruluk.

3. **🎨 Renk Sabitliği Uygulanmış Test Seti Başarısı**: `0.0995` (yaklaşık %10)  
   - Renk manipülasyonu sonrası doğruluk.

Sonuçlar, modelin başlangıç seviyesinde olduğunu ve iyileştirmelerle çok daha iyi performans gösterebileceğini ortaya koymaktadır.

---

## 🚀 Geliştirme Süreci

Proje geliştirme süreci şu adımlardan oluşmaktadır:

1. **📂 Veri Hazırlığı**: 10 hayvan sınıfından oluşan görsel veri setinin toplanması ve ön işlenmesi.  
2. **🛠️ Model Eğitimi**: CNN (Convolutional Neural Network) modeli kullanılarak eğitim sürecinin tamamlanması.  
3. **🔄 Manipülasyon ve Test**: Işık koşulları ve renk manipülasyonları gibi değişikliklerle modelin test edilmesi.  
4. **📊 Sonuçların Görselleştirilmesi**: Elde edilen sonuçların grafiklerle değerlendirilmesi.

---

## 💡 Yapılacak İyileştirmeler

Modelin doğruluğunu artırmak ve genel performansı iyileştirmek için yapılması planlanan çalışmalar:

- **📈 Veri Artırma**: Veri setine çeşitlilik kazandırarak modelin genelleme yeteneğini artırmak.  
- **🧪 Model Optimizasyonu**: Modelin hiperparametrelerini optimize ederek daha iyi sonuçlar elde etmek.  
- **🎨 Manipülasyon Direnci**: Görsel manipülasyonlara karşı daha dayanıklı bir model geliştirmek.  

---

💻 **Hayvan sınıflandırma projesi**, makine öğrenimi ve derin öğrenmeye ilgi duyan herkes için öğretici ve geliştirilmesi eğlenceli bir başlangıç projesi olmayı hedeflemektedir. 🐾  
