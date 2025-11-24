# CNN_Classification
Lung Disease Classification
# CNN ile Akciğer Hastalığı Tespiti (X-Ray)

Bu proje, derin öğrenme tabanlı CNN modeli kullanarak X-Ray görüntülerinden:

- Normal
- Akciğer Opaklığı
- Viral Pnömoni

sınıflarını otomatik olarak sınıflandırmayı amaçlamaktadır.

---

## 📌 Kullanılan Teknolojiler

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- PIL

---

## 📂 Dataset

Toplam görsel: **3475**

| Sınıf | Görsel Sayısı |
|------|---------------|
| Normal | 1250 |
| Lung Opacity | 1125 |
| Viral Pneumonia | 1100 |

Dataset:
Kaggle – Lung X-Ray 이미지 데이터세트

---

## 🧠 Model Mimarisi (CNN)

- 3 Convolution Layer
- ReLU aktivasyonu
- MaxPooling
- Fully Connected Layer
- Dropout (0.5)

---

## 🔥 Sonuçlar

- Test Doğruluğu: **%86.32**
- F1-score yüksekliği özellikle Viral Pneumonia sınıfında başarılıdır

---

## 📊 Eğitim Grafikleri

Eğitim sırasında loss ve accuracy değerleri takip edilmiştir.

