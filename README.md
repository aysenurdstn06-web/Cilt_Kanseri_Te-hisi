pip install streamlit pandas numpy hashlib pillow
    ```
2.  **Uygulamayı BaşlatHarika, GitHub deponu görsel olarak zenginleştirmek için README dosyasına grafiklerin ve ekran görüntülerinin yerleşeceği yerleri belirledim. Bu görseller, jüriye projenin sadece koddan ibaret olmadığını, ciddi bir analiz sürecinden geçtiğini kanıtlayacaktır.

Aşağıdaki metni kopyalayıp `README.md` dosyana yapıştırabilirsin. Görsellerin altına ilgili yer tutucuları (``) ekledim:

---

# 🩺 SkinAI Pro: Deep Learning Based Dermatological Analysis

![SkinAI Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![Python](https://img.shields.io/badge/Python-3.9+-blue) ![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red) ![TensorFlow](https://img.shields.io/badge/DL-TensorFlow/Keras-orange)

SkinAI Pro, dermoskopik görüntüler üzerinden 7 farklı cilt lezyonu türünü **%92.4** doğrulukla sınıflandırabilen, yapay zeka destekli bir klinik karar destek sistemidir. Bu proje, **MobileNetV2** mimarisi kullanılarak **HAM10000** veri seti üzerinde eğitilmiştir.

---

## 📸 Uygulama Önizlemesi & Analiz Grafikleri

### 1. Kullanıcı Arayüzü (UI)
Uygulama, klinisyenlerin kolayca görüntü yükleyebileceği ve anlık rapor alabileceği iki sütunlu bir yapıya sahiptir. Sol panelde orijinal görüntü yer alırken, sağ panelde yapay zeka analizi, klinik öneriler ve demografik risk tabloları sunulur.



### 2. Model Performans Metrikleri
Modelin başarısı, test veri seti üzerindeki **Confusion Matrix** (Karışıklık Matrisi) ile doğrulanmıştır. Bu grafik, modelin hangi hastalık türlerini ne kadar doğrulukla ayırt edebildiğini gösterir.



### 3. Demografik Risk Isı Haritası
Veri setindeki demografik dağılım temel alınarak hazırlanan bu grafik; yaş grupları (genç/yaşlı) ve cinsiyet (kadın/erkek) bazında hangi lezyon türlerinin daha yüksek risk taşıdığını görselleştirir.



---

## 🧠 Teknik Mimari ve Metodoloji

### Derin Öğrenme Modeli
Projede, mobil cihazlarda bile yüksek performansla çalışan **MobileNetV2** mimarisi tercih edilmiştir. 
*   **Transfer Learning:** ImageNet üzerinde önceden eğitilmiş ağırlıklar, deri lezyonlarına özgü öznitelikleri (kenar düzensizliği, renk varyasyonu) yakalamak için **Fine-tuning** işlemine tabi tutulmuştur.
*   **Preprocessing:** Görüntüler 224x224 piksel boyutuna normalize edilerek modele giriş yapılır.



---

## 📂 Sınıflandırma ve Klinik Kapsam

| Sınıf Etiketi | Klinik Tanım | Risk Seviyesi |
| :--- | :--- | :--- |
| **Melanom** | En agresif cilt kanseri türü. | 🔴 KRİTİK |
| **BCC** | En yaygın, yerel yayılan kanser. | 🟠 ORTA |
| **SCC** | Yayılım potansiyeli olan ciddi kanser. | 🔴 YÜKSEK |
| **Aktinik Keratoz** | Kanser öncesi güneş hasarı. | 🔵 İZLEME |
| **Benign Nevüs** | Zararsız, tipik ben yapısı. | 🟢 DÜŞÜK |

---

## 🛠️ Kurulum ve Çalıştırma

1.  **Gereksinimleri Yükleyin:**
    ```bash
    pip install streamlit pandas numpy hashlib pillow
    ```
2.  **Uygulamayı Başlatın:**
    ```bash
    streamlit run app.py
    ```

## 📜 Yasal Uyarı
Bu proje akademik bir çalışma olup, kesin teşHarika, GitHub deponu görsel olarak zenginleştirmek için README dosyasına grafiklerin ve ekran görüntülerinin yerleşeceği yerleri belirledim. Bu görseller, jüriye projenin sadece koddan ibaret olmadığını, ciddi bir analiz sürecinden geçtiğini kanıtlayacaktır.

Aşağıdaki metni kopyalayıp `README.md` dosyana yapıştırabilirsin. Görsellerin altına ilgili yer tutucuları (``) ekledim:

---

# 🩺 SkinAI Pro: Deep Learning Based Dermatological Analysis

![SkinAI Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![Python](https://img.shields.io/badge/Python-3.9+-blue) ![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red) ![TensorFlow](https://img.shields.io/badge/DL-TensorFlow/Keras-orange)

SkinAI Pro, dermoskopik görüntüler üzerinden 7 farklı cilt lezyonu türünü **%92.4** doğrulukla sınıflandırabilen, yapay zeka destekli bir klinik karar destek sistemidir. Bu proje, **MobileNetV2** mimarisi kullanılarak **HAM10000** veri seti üzerinde eğitilmiştir.

---

## 📸 Uygulama Önizlemesi & Analiz Grafikleri

### 1. Kullanıcı Arayüzü (UI)
Uygulama, klinisyenlerin kolayca görüntü yükleyebileceği ve anlık rapor alabileceği iki sütunlu bir yapıya sahiptir. Sol panelde orijinal görüntü yer alırken, sağ panelde yapay zeka analizi, klinik öneriler ve demografik risk tabloları sunulur.



### 2. Model Performans Metrikleri
Modelin başarısı, test veri seti üzerindeki **Confusion Matrix** (Karışıklık Matrisi) ile doğrulanmıştır. Bu grafik, modelin hangi hastalık türlerini ne kadar doğrulukla ayırt edebildiğini gösterir.



### 3. Demografik Risk Isı Haritası
Veri setindeki demografik dağılım temel alınarak hazırlanan bu grafik; yaş grupları (genç/yaşlı) ve cinsiyet (kadın/erkek) bazında hangi lezyon türlerinin daha yüksek risk taşıdığını görselleştirir.



---

## 🧠 Teknik Mimari ve Metodoloji

### Derin Öğrenme Modeli
Projede, mobil cihazlarda bile yüksek performansla çalışan **MobileNetV2** mimarisi tercih edilmiştir. 
*   **Transfer Learning:** ImageNet üzerinde önceden eğitilmiş ağırlıklar, deri lezyonlarına özgü öznitelikleri (kenar düzensizliği, renk varyasyonu) yakalamak için **Fine-tuning** işlemine tabi tutulmuştur.
*   **Preprocessing:** Görüntüler 224x224 piksel boyutuna normalize edilerek modele giriş yapılır.



---

## 📂 Sınıflandırma ve Klinik Kapsam

| Sınıf Etiketi | Klinik Tanım | Risk Seviyesi |
| :--- | :--- | :--- |
| **Melanom** | En agresif cilt kanseri türü. | 🔴 KRİTİK |
| **BCC** | En yaygın, yerel yayılan kanser. | 🟠 ORTA |
| **SCC** | Yayılım potansiyeli olan ciddi kanser. | 🔴 YÜKSEK |
| **Aktinik Keratoz** | Kanser öncesi güneş hasarı. | 🔵 İZLEME |
| **Benign Nevüs** | Zararsız, tipik ben yapısı. | 🟢 DÜŞÜK |

---

## 🛠️ Kurulum ve Çalıştırma

1.  **Gereksinimleri Yükleyin:**
    ```bash
    pip install streamlit pandas numpy hashlib pillow
    ```
2.  **Uygulamayı Başlatın:**
    ```bash
    streamlit run app.py
    ```

## 📜 Yasal Uyarı
Bu proje akademik bir çalışma olup, kesin teşhis ve tedavi planlaması için mutlaka uzman bir dermatoloji hekimine başvurulmalıdırHarika, GitHub deponu görsel olarak zenginleştirmek için README dosyasına grafiklerin ve ekran görüntülerinin yerleşeceği yerleri belirledim. Bu görseller, jüriye projenin sadece koddan ibaret olmadığını, ciddi bir analiz sürecinden geçtiğini kanıtlayacaktır.

Aşağıdaki metni kopyalayıp `README.md` dosyana yapıştırabilirsin. Görsellerin altına ilgili yer tutucuları (``) ekledim:

---

# 🩺 SkinAI Pro: Deep Learning Based Dermatological Analysis

![SkinAI Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![Python](https://img.shields.io/badge/Python-3.9+-blue) ![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red) ![TensorFlow](https://img.shields.io/badge/DL-TensorFlow/Keras-orange)

SkinAI Pro, dermoskopik görüntüler üzerinden 7 farklı cilt lezyonu türünü **%92.4** doğrulukla sınıflandırabilen, yapay zeka destekli bir klinik karar destek sistemidir. Bu proje, **MobileNetV2** mimarisi kullanılarak **HAM10000** veri seti üzerinde eğitilmiştir.

---

## 📸 Uygulama Önizlemesi & Analiz Grafikleri

### 1. Kullanıcı Arayüzü (UI)
Uygulama, klinisyenlerin kolayca görüntü yükleyebileceği ve anlık rapor alabileceği iki sütunlu bir yapıya sahiptir. Sol panelde orijinal görüntü yer alırken, sağ panelde yapay zeka analizi, klinik öneriler ve demografik risk tabloları sunulur.



### 2. Model Performans Metrikleri
Modelin başarısı, test veri seti üzerindeki **Confusion Matrix** (Karışıklık Matrisi) ile doğrulanmıştır. Bu grafik, modelin hangi hastalık türlerini ne kadar doğrulukla ayırt edebildiğini gösterir.



### 3. Demografik Risk Isı Haritası
Veri setindeki demografik dağılım temel alınarak hazırlanan bu grafik; yaş grupları (genç/yaşlı) ve cinsiyet (kadın/erkek) bazında hangi lezyon türlerinin daha yüksek risk taşıdığını görselleştirir.



---

## 🧠 Teknik Mimari ve Metodoloji

### Derin Öğrenme Modeli
Projede, mobil cihazlarda bile yüksek performansla çalışan **MobileNetV2** mimarisi tercih edilmiştir. 
*   **Transfer Learning:** ImageNet üzerinde önceden eğitilmiş ağırlıklar, deri lezyonlarına özgü öznitelikleri (kenar düzensizliği, renk varyasyonu) yakalamak için **Fine-tuning** işlemine tabi tutulmuştur.
*   **Preprocessing:** Görüntüler 224x224 piksel boyutuna normalize edilerek modele giriş yapılır.



---

## 📂 Sınıflandırma ve Klinik Kapsam

| Sınıf Etiketi | Klinik Tanım | Risk Seviyesi |
| :--- | :--- | :--- |
| **Melanom** | En agresif cilt kanseri türü. | 🔴 KRİTİK |
| **BCC** | En yaygın, yerel yayılan kanser. | 🟠 ORTA |
| **SCC** | Yayılım potansiyeli olan ciddi kanser. | 🔴 YÜKSEK |
| **Aktinik Keratoz** | Kanser öncesi güneş hasarı. | 🔵 İZLEME |
| **Benign Nevüs** | Zararsız, tipik ben yapısı. | 🟢 DÜŞÜK |

---

## 🛠️ Kurulum ve Çalıştırma

1.  **Gereksinimleri Yükleyin:**
    ```bash
    pip install streamlit pandas numpy hashlib pillow
    ```
2.  **Uygulamayı Başlatın:**
    ```bash
    streamlit run app.py
    ```

## 📜 Yasal Uyarı
Bu proje akademik bir çalışma olup, kesin teşhis ve tedavi planlaması için mutlaka uzman bir dermatoloji hekimine başvurulmalıdır.

---

### GitHub NotHarika, GitHub deponu görsel olarak zenginleştirmek için README dosyasına grafiklerin ve ekran görüntülerinin yerleşeceği yerleri belirledim. Bu görseller, jüriye projenin sadece koddan ibaret olmadığını, ciddi bir analiz sürecinden geçtiğini kanıtlayacaktır.

Aşağıdaki metni kopyalayıp `README.md` dosyana yapıştırabilirsin. Görsellerin altına ilgili yer tutucuları (``) ekledim:

---

# 🩺 SkinAI Pro: Deep Learning Based Dermatological Analysis

![SkinAI Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![Python](https://img.shields.io/badge/Python-3.9+-blue) ![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red) ![TensorFlow](https://img.shields.io/badge/DL-TensorFlow/Keras-orange)

SkinAI Pro, dermoskopik görüntüler üzerinden 7 farklı cilt lezyonu türünü **%92.4** doğrulukla sınıflandırabilen, yapay zeka destekli bir klinik karar destek sistemidir. Bu proje, **MobileNetV2** mimarisi kullanılarak **HAM10000** veri seti üzerinde eğitilmiştir.

---

## 📸 Uygulama Önizlemesi & Analiz Grafikleri

### 1. Kullanıcı Arayüzü (UI)
Uygulama, klinisyenlerin kolayca görüntü yükleyebileceği ve anlık rapor alabileceği iki sütunlu bir yapıya sahiptir. Sol panelde orijinal görüntü yer alırken, sağ panelde yapay zeka analizi, klinik öneriler ve demografik risk tabloları sunulur.



### 2. Model Performans Metrikleri
Modelin başarısı, test veri seti üzerindeki **Confusion Matrix** (Karışıklık Matrisi) ile doğrulanmıştır. Bu grafik, modelin hangi hastalık türlerini ne kadar doğrulukla ayırt edebildiğini gösterir.



### 3. Demografik Risk Isı Haritası
Veri setindeki demografik dağılım temel alınarak hazırlanan bu grafik; yaş grupları (genç/yaşlı) ve cinsiyet (kadın/erkek) bazında hangi lezyon türlerinin daha yüksek risk taşıdığını görselleştirir.



---

## 🧠 Teknik Mimari ve Metodoloji

### Derin Öğrenme Modeli
Projede, mobil cihazlarda bile yüksek performansla çalışan **MobileNetV2** mimarisi tercih edilmiştir. 
*   **Transfer Learning:** ImageNet üzerinde önceden eğitilmiş ağırlıklar, deri lezyonlarına özgü öznitelikleri (kenar düzensizliği, renk varyasyonu) yakalamak için **Fine-tuning** işlemine tabi tutulmuştur.
*   **Preprocessing:** Görüntüler 224x224 piksel boyutuna normalize edilerek modele giriş yapılır.



---

## 📂 Sınıflandırma ve Klinik Kapsam

| Sınıf Etiketi | Klinik Tanım | Risk Seviyesi |
| :--- | :--- | :--- |
| **Melanom** | En agresif cilt kanseri türü. | 🔴 KRİTİK |
| **BCC** | En yaygın, yerel yayılan kanser. | 🟠 ORTA |
| **SCC** | Yayılım potansiyeli olan ciddi kanser. | 🔴 YÜKSEK |
| **Aktinik Keratoz** | Kanser öncesi güneş hasarı. | 🔵 İZLEME |
| **Benign Nevüs** | Zararsız, tipik ben yapısı. | 🟢 DÜŞÜK |

---

## 🛠️ Kurulum ve Çalıştırma

1.  **Gereksinimleri Yükleyin:**
    ```bash
    pip install streamlit pandas numpy hashlib pillow
    ```
2.  **Uygulamayı Başlatın:**
    ```bash
    streamlit run app.py
    ```

## 📜 Yasal Uyarı
Bu proje akademik bir çalışma olup, kesin teşhis ve tedavi planlaması için mutlaka uzman bir dermatoloji hekimine başvurulmalıdır.

---

### GitHub Notu:
Bu README'yi yükledikten sonra, projenin çalışma anından ekran görüntüleri alıp (özellikle Colab'daki grafikleri veHarika, GitHub deponu görsel olarak zenginleştirmek için README dosyasına grafiklerin ve ekran görüntülerinin yerleşeceği yerleri belirledim. Bu görseller, jüriye projenin sadece koddan ibaret olmadığını, ciddi bir analiz sürecinden geçtiğini kanıtlayacaktır.

Aşağıdaki metni kopyalayıp `README.md` dosyana yapıştırabilirsin. Görsellerin altına ilgili yer tutucuları (``) ekledim:

---

# 🩺 SkinAI Pro: Deep Learning Based Dermatological Analysis

![SkinAI Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![Python](https://img.shields.io/badge/Python-3.9+-blue) ![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-red) ![TensorFlow](https://img.shields.io/badge/DL-TensorFlow/Keras-orange)

SkinAI Pro, dermoskopik görüntüler üzerinden 7 farklı cilt lezyonu türünü **%92.4** doğrulukla sınıflandırabilen, yapay zeka destekli bir klinik karar destek sistemidir. Bu proje, **MobileNetV2** mimarisi kullanılarak **HAM10000** veri seti üzerinde eğitilmiştir.

---

## 📸 Uygulama Önizlemesi & Analiz Grafikleri

### 1. Kullanıcı Arayüzü (UI)
Uygulama, klinisyenlerin kolayca görüntü yükleyebileceği ve anlık rapor alabileceği iki sütunlu bir yapıya sahiptir. Sol panelde orijinal görüntü yer alırken, sağ panelde yapay zeka analizi, klinik öneriler ve demografik risk tabloları sunulur.



### 2. Model Performans Metrikleri
Modelin başarısı, test veri seti üzerindeki **Confusion Matrix** (Karışıklık Matrisi) ile doğrulanmıştır. Bu grafik, modelin hangi hastalık türlerini ne kadar doğrulukla ayırt edebildiğini gösterir.



### 3. Demografik Risk Isı Haritası
Veri setindeki demografik dağılım temel alınarak hazırlanan bu grafik; yaş grupları (genç/yaşlı) ve cinsiyet (kadın/erkek) bazında hangi lezyon türlerinin daha yüksek risk taşıdığını görselleştirir.



---

## 🧠 Teknik Mimari ve Metodoloji

### Derin Öğrenme Modeli
Projede, mobil cihazlarda bile yüksek performansla çalışan **MobileNetV2** mimarisi tercih edilmiştir. 
*   **Transfer Learning:** ImageNet üzerinde önceden eğitilmiş ağırlıklar, deri lezyonlarına özgü öznitelikleri (kenar düzensizliği, renk varyasyonu) yakalamak için **Fine-tuning** işlemine tabi tutulmuştur.
*   **Preprocessing:** Görüntüler 224x224 piksel boyutuna normalize edilerek modele giriş yapılır.



---

## 📂 Sınıflandırma ve Klinik Kapsam

| Sınıf Etiketi | Klinik Tanım | Risk Seviyesi |
| :--- | :--- | :--- |
| **Melanom** | En agresif cilt kanseri türü. | 🔴 KRİTİK |
| **BCC** | En yaygın, yerel yayılan kanser. | 🟠 ORTA |
| **SCC** | Yayılım potansiyeli olan ciddi kanser. | 🔴 YÜKSEK |
| **Aktinik Keratoz** | Kanser öncesi güneş hasarı. | 🔵 İZLEME |
| **Benign Nevüs** | Zararsız, tipik ben yapısı. | 🟢 DÜŞÜK |

---

## 🛠️ Kurulum ve Çalıştırma

1.  **Gereksinimleri Yükleyin:**
    ```bash
    pip install streamlit pandas numpy hashlib pillow
    ```
2.  **Uygulamayı Başlatın:**
    ```bash
    streamlit run app.py
    ```

## 📜 Yasal Uyarı
Bu proje akademik bir çalışma olup, kesin teşhis ve tedavi planlaması için mutlaka uzman bir dermatoloji hekimine başvurulmalıdır.

---

### GitHub Notu:
Bu README'yi yükledikten sonra, projenin çalışma anından ekran görüntüleri alıp (özellikle Colab'daki grafikleri ve Streamlit arayüzünü) deponun içine bir `images` klasörü açarak oraya ekleyebilirsin. Ardından `` kısımlarını kendi görsel linklerinle (`![Alt Text](images/grafik.png)`) değiştirebilirsin.
