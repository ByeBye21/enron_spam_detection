# enron_spam_detection

Bu proje, **Veri Madenciliği** dersi kapsamında **Enron E-Posta Veri Seti** kullanılarak geliştirilmiş bir makine öğrenmesi uygulamasıdır. Doğal Dil İşleme (NLP) teknikleri kullanılarak, e-postaların içeriğine göre "Spam" (Zararlı/İstenmeyen) veya "Ham" (Normal) olarak sınıflandırılması hedeflenmiştir.

## **🚀 Proje Özeti**

* **Amaç:** E-posta içeriklerini analiz ederek yüksek doğrulukla spam tespiti yapmak.  
* **Veri Seti:** Enron Corpus (33.000+ e-posta verisi).  
* **Yöntem:** Metin Ön İşleme, TF-IDF Vektörleştirme (N-Gram).  
* **Modeller:** Logistic Regression ve Multinomial Naive Bayes.

## **📊 Sonuçlar**

Yapılan testler sonucunda **Logistic Regression** modeli en yüksek performansı göstermiştir.

| Model | Accuracy | Precision | Recall | F1-Score |
| :---- | :---- | :---- | :---- | :---- |
| **Logistic Regression** | **%98.6** | 0.97 | **0.99** | 0.98 |
| Naive Bayes | %97.9 | 0.97 | 0.98 | 0.97 |

## **🛠️ Kurulum ve Kullanım**

Projeyi kendi bilgisayarınızda çalıştırmak için:

1. **Repoyu klonlayın:**  
   git clone [https://github.com/ByeBye21/enron_spam_detection.git\](https://github.com/ByeBye21/enron_spam_detection.git)

2. **Gerekli kütüphaneleri yükleyin:**  
   pip install pandas numpy scikit-learn matplotlib seaborn

3. **Projeyi çalıştırın:**
   Spam_Tespiti.ipynb dosyasını Jupyter Notebook ile açarak hücreleri sırasıyla çalıştırın.
