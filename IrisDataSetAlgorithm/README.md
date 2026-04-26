# Iris Dataset ML Project

Bu proje, klasik **Iris veri seti** üzerinde farklı makine öğrenimi algoritmalarının uygulanmasını ve karşılaştırılmasını içerir.  
Çalışmada **EDA (Exploratory Data Analysis)**, **Feature Engineering** ve **Label Encoding** adımları gerçekleştirilmiş, ardından çeşitli algoritmalar denenmiştir.

---

## 🔍 Proje Adımları

1. **EDA (Exploratory Data Analysis)**  
   - Veri setinin genel yapısı incelendi.  
   - Sınıf dağılımları, özelliklerin istatistiksel özetleri ve görselleştirmeler yapıldı.  

2. **Feature Engineering**  
   - Gerekli ön işleme adımları uygulandı.  
   - **Label Encoding** ile kategorik değişkenler sayısal değerlere dönüştürüldü.  

3. **Kullanılan Algoritmalar**  
   - Naive Bayes Teoremi  
   - Support Vector Classifier (SVC)  
   - GridSearchCV (hiperparametre optimizasyonu için)  
   - Logistic Regression  

---
## 📊 Sonuçlar

| Algoritma            | Doğruluk (Accuracy) |
|----------------------|---------------------|
| Naive Bayes          | 100%                |
| SVC (GridSearchCV ile)| 100%                |
| Logistic Regression  | 96%                 |

### Confusion Matrix
- **Naive Bayes:** Tüm sınıflar doğru tahmin edildi (tam isabet).
- **SVC:** Tüm sınıflar doğru tahmin edildi (tam isabet).
- **Logistic Regression:** Bazı sınıflarda küçük hatalar mevcut.