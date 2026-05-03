# 🩺 SkinAI Pro: Akıllı Dermatolojik Analiz ve Klinik Karar Destek Paneli

Bu çalışma, dermatolojik görüntüleri yüksek doğrulukla sınıflandırmak ve kullanıcıya veri odaklı bir klinik ön rapor sunmak amacıyla geliştirilmiş kapsamlı bir **Klinik Karar Destek Sistemi** prototipidir. Proje, görüntü işleme algoritmalarını interaktif bir web arayüzü ile birleştirerek modern bir tıbbi analiz deneyimi sunar.

---

## 📈 Model Başarısı ve Doğruluk Analizleri
Modelin başarısı, akademik standartlara uygun metrikler kullanılarak titizlikle ölçülmüştür:

*   **Genel Doğruluk (Accuracy):** Model, test veri seti üzerinde **%92 - %94** arasında tutarlı bir doğruluk oranına ulaşmıştır[cite: 1].
*   **Hata Matrisi (Confusion Matrix):** Uygulama içerisinde yer alan bu matris, modelin hangi hastalıkları birbiriyle karıştırdığını şeffaf bir şekilde gösterir[cite: 1].
*   **Hassasiyet (Precision) ve Duyarlılık (Recall):** Özellikle hayati risk taşıyan **Melanom** vakaları için "Recall" değerleri optimize edilmiş, yanlış negatif oranları minimuma indirilmiştir[cite: 1].
*   **Eğitim Süreci:** Model, 10.015 görüntülük **HAM10000** veri seti ile eğitilmiş ve aşırı öğrenmeyi (overfitting) önlemek için doğrulama setleri üzerinde test edilmiştir[cite: 1].

---

## 📊 Görsel Analiz ve Grafik Paneli
Uygulama arayüzünde, verilerin anlamlandırılması için aşağıdaki grafikler dinamik olarak oluşturulmaktadır[cite: 1]:

*   **Hastalık Dağılımı (Bar Chart):** Veri setindeki 7 farklı hastalık sınıfının sayısal yoğunluğunu gösterir[cite: 1].
*   **Yaş Grubu Yoğunluk Haritası (KDE Plot):** Cilt hastalıklarının yaş gruplarına göre dağılımını ve risk artış bölgelerini görselleştirir[cite: 1].
*   **Cinsiyete Göre Risk Dağılımı (Pie Chart):** Hastalıkların cinsiyetler arasındaki dağılım oranlarını pasta grafiği ile sunar[cite: 1].
*   **Anatomik Konum Analizi:** Lezyonların vücut bölgelerine (sırt, yüz, eller vb.) göre görülme sıklığını gösteren frekans analizidir[cite: 1].

---

## 🖥️ Web Sitesi İçeriği ve Fonksiyonlar
**Streamlit** kütüphanesi ile geliştirilen web paneli şu özellikleri sunar[cite: 1]:

*   **İnteraktif Test Paneli:** Kullanıcıların `.jpg` veya `.png` formatındaki fotoğrafları sürükle-bırak yöntemiyle yükleyebileceği alan[cite: 1].
*   **Dinamik Tahmin Motoru:** Yüklenen görüntüyü saniyeler içinde analiz ederek en yüksek olasılıklı teşhisi ve "Güven Skoru"nu ekrana yansıtır[cite: 1].
*   **Klinik Bilgi Kartları:** Teşhis edilen hastalık hakkında genel tanım, belirtiler ve risk faktörlerini içeren bilgilendirme paneli sunar[cite: 1].

---

## 🔍 Hastalık Kütüphanesi Özeti
| Hastalık Sınıfı | Klinik Tanım |
| :--- | :--- |
| **Melanom (MEL)** | En agresif cilt kanseri türüdür; pigment hücrelerinden kaynaklanır[cite: 1]. |
| **Bazal Hücreli Karsinom (BCC)** | En yaygın görülen, yavaş seyirli ve genellikle lokal tedavi edilen kanser türüdür[cite: 1]. |
| **Aktinik Keratoz (AKIEC)** | Güneş hasarı kaynaklı, kanser öncesi (prekanseröz) lezyonlardır[cite: 1]. |
| **Benign Nevüs (NV)** | Toplumda yaygın görülen zararsız ve iyi huylu benlerdir[cite: 1]. |
| **Vasküler Lezyonlar (VASC)** | Damarsal kaynaklı, genellikle kırmızı veya mor renkli deri oluşumlarıdır[cite: 1]. |

---
HAZIRLAYAN
İsim Soyisim:Ayşenur Daştan-Esra ilban
## 🚀 Çalıştırma Talimatı
Projenin çalışması için gerekli kütüphaneleri yükledikten sonra ana dosyayı çalıştırabilirsiniz[cite: 1].
```bash
# Gerekli kütüphaneleri yükleyin
pip install streamlit pandas scikit-learn matplotlib seaborn

# Uygulamayı başlatın
streamlit run app.py
