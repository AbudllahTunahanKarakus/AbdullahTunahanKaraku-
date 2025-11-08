### 👋 Merhaba!

## 👨‍💻 Hakkımda

Bilgisayar Mühendisliği 4. sınıf öğrencisi olarak, kariyerimi **Veri Analistliği**, **Yapay Zeka** ve **Derin Öğrenme** üzerine inşa ediyorum. Teorik bilginin ötesine geçerek, **Python** ile derin öğrenme algoritmalarını kullanan pratik çözümler geliştiriyorum.

Eş zamanlı olarak, bir ekip çalışması kapsamında **MATLAB** ortamında Evrişimli Sinir Ağları (CNN) tabanlı bir proje yürüterek bu alandaki yetkinliğimi pekiştiriyorum.

Beni motive eden şey, yeni teknolojileri hızla öğrenip bunları gerçek dünya problemlerine uygulamaktır. Çalışma prensibim; detaylara hakim, düzenli ve titiz bir yaklaşımla, başladığım her işi en yüksek kalite standartlarında tamamlamaktır.

Projelerde sonuç odaklı bir tutum sergiler, hedeflere ulaşmak için proaktif olarak **inisiyatif alırım** ve takım sinerjisine güçlü bir katkı sağlarım. Hedefim, Yapay Zeka ve Derin Öğrenme alanlarında uzmanlaşarak, karşılaşılan zorlu problemlere yenilikçi ve verimli çözümler üreten bir mühendis olmaktır.

---

## 🚀 Kullandığım Diller ve Teknolojiler

#### Programlama Dilleri
<p align="left">
  <img src="https://img.shields.io/badge/Python-İleri_Seviye-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-Orta_Seviye-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C%23-Orta_Seviye-512BD4?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
</p>

#### Veri, Yapay Zeka & Mobil
<p align="left">
  <img src="https://img.shields.io/badge/MATLAB-Orta_Seviye-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-Orta_Seviye-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Android-Başlangıç-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
</p>

#### Yabancı Dil
<p align="left">
  <img src="https://img.shields.io/badge/İngilizce-B1_Seviye-007FFF?style=for-the-badge" alt="İngilizce B1" />
</p>

---
# 🧠 Python & Keras ile Beyin Tümörü Tespiti (Xception Modeli)

Bu proje, bir derin öğrenme modeli kullanarak beyin MR görüntülerinde tümörlü ve sağlıklı dokuları sınıflandırmak amacıyla geliştirilmiştir. Model, **Xception** mimarisi temel alınarak ve **Transfer Learning (Aktarımlı Öğrenme)** tekniği kullanılarak Python ve Keras kütüphaneleri ile eğitilmiştir.

---

## 🚀 Projenin Amacı ve Kapsamı

Bu modelin temel amacı, tıbbi görüntüleri analiz ederek radyologlara ve tıp uzmanlarına yönelik bir **karar destek sistemi** için bir prototip oluşturmaktır.

Model, kendisine verilen bir 2D MR görüntüsünü **3 farklı sınıftan** biri olarak sınıflandırmak üzere eğitilmiştir:

* **[Sınıf 1: örn: brain_glioma]**
* **[Sınıf 2: örn: brain_menin]**
* **[Sınıf 3: örn: brain_tumor]**
---
## 🛠️ Kullanılan Teknolojiler

* **Dil:** Python
* **Derin Öğrenme:** TensorFlow, Keras
* **Temel Mimari:** Xception (Transfer Learning)
* **Veri İşleme & Analiz:** NumPy, Pandas, Scikit-learn (Veri setini bölmek için)
* **Görüntü İşleme:** OpenCV (cv2)
* **Görselleştirme:** Matplotlib

---

## 📊 Sonuçlar ve Performans

Model, **Xception** mimarisi ve aktarımlı öğrenme tekniği sayesinde test veriseti (validation set) üzerinde olağanüstü bir başarı göstermiştir.

Modelin ulaştığı en yüksek doğruluk oranı:
**%99.67**

Aşağıda, modelin eğitim ve doğrulama (validation) setleri üzerindeki doğruluk/kayıp (accuracy/loss) grafiği yer almaktadır.

*(Bu grafiği projenin klasörüne `sonuclar/grafik.png` olarak eklersen, aşağıdaki kod onu otomatik olarak gösterecektir)*

![Model Performans Grafiği](sonuclar/grafik.png)

Aşağıda modelin bir test görüntüsü üzerinde yaptığı örnek bir tahmin yer almaktadır:

*(Tahmin yapılan bir görüntünün ekran resmini `sonuclar/ornek-tahmin.png` olarak eklersen harika olur)*

![Örnek Tahmin](sonuclar/ornek-tahmin.png)

---

## 📁 Veri Seti

Bu projede kullanılan veri seti, **Kaggle** platformundan temin edilmiş, beyin kanseri teşhisine yönelik 3 sınıflı (Glioma, Meningioma, Pituitary) etiketlenmiş MR görüntülerinden oluşmaktadır.

---

## 🏃‍♀️ Nasıl Çalıştırılır?

Bu projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1.  Depoyu klonlayın:
    ```bash
    git clone [https://github.com/](https://github.com/)[Senin-GitHub-Adın]/[Proje-Depo-Adın].git
    ```
2.  Proje dizinine gidin:
    ```bash
    cd [Proje-Depo-Adın]
    ```
3.  Gerekli kütüphaneleri yükleyin:
    *(Proje klasörüne `requirements.txt` adında bir dosya oluşturup `tensorflow`, `numpy`, `opencv-python` vb. kütüphaneleri içine yazmalısın)*
    ```bash
    pip install -r requirements.txt
    ```
4.  Modeli eğitmek için:
    *(Senin kodundaki dosya adını temel aldım)*
    ```bash
    python Xception.py
    ```

## 📫 Bana Ulaşın

<p align="left">

  <a href="https://www.linkedin.com/in/abdullah-tunahan-karakuş-aa541a2a1" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profili" />
  </a>
  
  <a href="mailto:tunahankarakus37@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-posta Gönder" />
  </a>
</p>
