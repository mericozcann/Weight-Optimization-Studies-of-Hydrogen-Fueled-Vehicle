Araç Ağırlık Optimizasyonu ve Performans Analizi
Bu repo, bir aracın bileşenlerine ait ağırlık optimizasyonu ve performans analizine yönelik üç farklı çalışmayı içermektedir. Bu çalışmalar, ağırlık optimizasyonu, boyut indirgeme, kümeleme algoritmaları ve performans katkısının dikkate alındığı optimizasyonlar üzerine odaklanmaktadır.

İçerik
Kümeleme ve Boyut İndirgeme
Ağırlık Optimizasyonu
Ağırlık ve Performans Optimizasyonu
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

Kurulum ve Çalıştırma
Projeyi çalıştırmak için gerekli Python kütüphanelerini aşağıdaki gibi kurabilirsiniz:

bash
Kodu kopyala
pip install numpy pandas scikit-learn matplotlib scipy
Ardından, ilgili Python dosyalarını çalıştırarak sonuçları görebilirsiniz
