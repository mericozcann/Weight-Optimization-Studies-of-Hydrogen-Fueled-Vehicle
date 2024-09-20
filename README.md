Araç Ağırlık Optimizasyonu ve Performans Analizi
Bu repo, bir aracın bileşenlerine ait ağırlık optimizasyonu ve performans analizine yönelik üç farklı çalışmayı içermektedir. Bu çalışmalar, ağırlık optimizasyonu, boyut indirgeme, kümeleme algoritmaları ve performans katkısının dikkate alındığı optimizasyonlar üzerine odaklanmaktadır.

İçerik
Kümeleme ve Boyut İndirgeme
Ağırlık Optimizasyonu
Ağırlık ve Performans Optimizasyonu
Vehicle Weight Optimization and Performance Analysis
This repository contains three different studies focusing on the optimization of vehicle component weights and performance analysis. These studies cover weight optimization, dimensionality reduction, clustering algorithms, and optimizations that consider performance contribution.

Contents
Clustering and Dimensionality Reduction
Weight Optimization
Weight and Performance Optimization
1. Kümeleme ve Boyut İndirgeme
Bu çalışmada, araç bileşenlerinin ağırlıkları ve performans parametrelerine dayanarak K-Means ve DBSCAN kümeleme algoritmaları kullanılmıştır. Ayrıca PCA (Principal Component Analysis) ile boyut indirgeme yapılmıştır.

Adımlar:
Verilerin normalizasyonu (StandardScaler)
K-Means ile kümeleme (n_clusters=2)
DBSCAN algoritması ile kümeleme
PCA ile boyut indirgeme ve görselleştirme
Görselleştirme:
PCA sonuçları, K-Means küme etiketleri ile görselleştirilmiştir.

Kullanılan Kütüphaneler:
numpy, pandas, scikit-learn, matplotlib

1. Clustering and Dimensionality Reduction
In this study, K-Means and DBSCAN clustering algorithms are used based on the weights and performance parameters of vehicle components. PCA (Principal Component Analysis) is also employed for dimensionality reduction.

Steps:
Data normalization (StandardScaler)
Clustering with K-Means (n_clusters=2)
Clustering with DBSCAN algorithm
Dimensionality reduction and visualization with PCA
Visualization:
PCA results are visualized using K-Means cluster labels.

Libraries Used:
numpy, pandas, scikit-learn, matplotlib

2. Ağırlık Optimizasyonu
Bu çalışmada, aracın farklı bileşenlerine ait ağırlıkların minimize edilmesi amacıyla SLSQP optimizasyon yöntemi kullanılmıştır. Amaç, toplam ağırlık sınırına (225 kg) uygun çözümler üretmek ve belirlenen minimum ve maksimum sınırlar dahilinde ağırlıkları optimize etmektir.

Adımlar:
Başlangıç ağırlıklarının belirlenmesi
Minimum ve maksimum ağırlık sınırlarının tanımlanması
Toplam ağırlık sınırının dikkate alındığı optimizasyon
Bileşen bazında optimize edilmiş ağırlıkların hesaplanması
Sonuçlar:
Optimizasyon başarılı olduğunda, toplam ağırlık sınırı aşılmadan en uygun bileşen ağırlıkları elde edilmektedir.

Kullanılan Kütüphaneler:
numpy, scipy

2. Weight Optimization
In this study, the SLSQP optimization method is used to minimize the weights of different vehicle components. The objective is to provide solutions within the total weight limit (225 kg) and to optimize the weights within the defined minimum and maximum constraints.

Steps:
Defining initial weights
Defining minimum and maximum weight limits
Optimization considering the total weight limit
Calculating the optimized component weights
Results:
When the optimization is successful, the optimal component weights are obtained without exceeding the total weight limit.

Libraries Used:
numpy, scipy

3. Ağırlık ve Performans Optimizasyonu
Bu çalışmada, sadece ağırlıkları optimize etmekle kalmayıp, bileşenlerin araç performansına katkısı da dikkate alınmıştır. Performansa katkı katsayıları (negatif değerler) ile toplam ağırlık ve performans kazancı birlikte optimize edilmiştir.

Adımlar:
Ağırlıkların yanı sıra performans katsayılarının dahil edilmesi
Toplam ağırlık ve performans kazancına dayalı bir hedef fonksiyon
Ağırlık sınırları ve toplam ağırlık kısıtı ile optimizasyon
Bileşen bazında optimize edilmiş ağırlık ve performans analizleri
Sonuçlar:
Performans ve ağırlık optimize edilerek aracın verimliliği artırılmıştır.

Kullanılan Kütüphaneler:
numpy, scipy

3. Weight and Performance Optimization
In this study, not only the weights are optimized but also the contribution of components to vehicle performance is considered. Using performance contribution coefficients (negative values), total weight and performance gain are optimized together.

Steps:
Including performance contribution coefficients alongside weights
Objective function based on total weight and performance gain
Optimization with weight limits and total weight constraint
Optimized weight and performance analysis by component
Results:
Performance and weight are optimized, enhancing the vehicle's overall efficiency.

Libraries Used:
numpy, scipy

Kurulum ve Çalıştırma
Projeyi çalıştırmak için gerekli Python kütüphanelerini aşağıdaki gibi kurabilirsiniz:

bash
Kodu kopyala
pip install numpy pandas scikit-learn matplotlib scipy
Ardından, ilgili Python dosyalarını çalıştırarak sonuçları görebilirsiniz.

Installation and Running
You can install the required Python libraries for this project with the following command:

bash
Kodu kopyala
pip install numpy pandas scikit-learn matplotlib scipy
Then, you can run the relevant Python files to view the results.
