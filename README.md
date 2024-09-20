# Weight Optimization Studies of Hydrogen Fueled Electric City Vehicle
## Project 1: Weight Optimization of Hydrogen-Powered Electric Vehicle
### Overview
This project focuses on optimizing the weight of key components in a hydrogen-powered electric city vehicle, such as the motor, fuel cell, chassis, and hydrogen tank. The goal is to improve vehicle energy efficiency by minimizing the overall weight while respecting specific weight limits for each component.

### Objectives
* Minimize the total weight of critical components.
* Ensure the components meet their individual weight constraints.
* Analyze the impact of weight optimization on vehicle performance and efficiency.
### Methods
* Optimization with Constraints: Using SLSQP optimization, the weight of components is adjusted to meet the total vehicle weight limit and individual component constraints.
* Mathematical Model: The objective function minimizes the total weight of components while ensuring the constraints for minimum and maximum weights are respected.
### Results
* Optimized Weights: The motor, fuel cell, and chassis weights were reduced to meet the total weight limit of 225 kg while maintaining balance across other components.
### Analysis:
* The optimization reduced the weight distribution while keeping the total weight within permissible limits.
* Performance and efficiency were potentially enhanced due to the lighter overall vehicle weight, especially in the motor and fuel cell.
* Further material optimization can reduce costs and increase efficiency.
* Future work could explore aerodynamic improvements to further enhance energy efficiency.
## Project 2: Performance-Weighted Weight Optimization
### Overview
This project integrates both weight and performance into the optimization process for a hydrogen-powered electric vehicle. The goal is to find a balance between minimizing weight and maximizing performance.

### Objectives
* Minimize the total weight while considering performance contributions from different components.
* Optimize component weights to improve overall vehicle efficiency.
### Methods
* Optimization with Performance Contributions: A mathematical model was developed to minimize both the total weight and the performance penalties associated with the weight of different components.
* Objective Function: The function combined the weight penalty with the performance gain (in negative terms) to optimize the vehicle’s performance and weight balance.
### Results
* Optimized Weights: The motor, fuel cell, and chassis weights were optimized to enhance both the performance and overall efficiency of the vehicle.
### Analysis:
* The weight distribution was optimized to meet performance goals while staying within the overall weight limit.
* The performance of the vehicle was improved through careful weight distribution across critical components.
* Future optimizations could involve aerodynamic adjustments for further performance gains.
## Project 3: Data Normalization and Clustering for Vehicle Components
### Overview
This project utilizes clustering algorithms and data normalization to analyze the relationships between different vehicle components. It aims to identify patterns in the weight and performance data of components like the motor, fuel cell, and chassis.

### Objectives
* Normalize weight and performance data for consistent analysis.
* Apply clustering techniques to group components based on similarities in weight and performance.
* Use dimensionality reduction for effective visualization.
### Methods
* Data Normalization: StandardScaler was used to normalize component data for consistent comparisons.
* Clustering Techniques: K-Means and DBSCAN algorithms were applied to cluster components based on their characteristics.
* Principal Component Analysis (PCA): Used to reduce dimensionality and visualize the clustering results.
### Results
* Clustering Results: Both K-Means and DBSCAN effectively grouped similar components, identifying patterns in their weight and performance characteristics.
* Visualization: PCA was used to reduce the complexity of the data and create a 2D visualization of the component clusters.
### Analysis:
* Data normalization allowed for fair comparisons between components with varying weight and performance metrics.
* Clustering helped uncover relationships between different components, providing insights for further optimization.
* Future work could integrate additional vehicle parameters, like aerodynamics, into the clustering analysis for a more comprehensive view.
* This format retains the structure of your original projects while highlighting the technical processes and outcomes in a clear and concise manner.

# Hidrojen Yakıtlı Elektrikli Şehir Aracının Ağırlık Optimizasyon Çalışmaları
## Proje 1: Hidrojen Yakıtlı Elektrikli Araç İçin Ağırlık Optimizasyonu
### Genel Bakış
Bu proje, hidrojen yakıtlı elektrikli bir şehir aracının bileşenlerinin ağırlık dağılımını optimize etmeye odaklanmaktadır. Amacımız, motor, yakıt hücresi, şasi ve diğer kritik bileşenlerin ağırlıklarını göz önünde bulundurarak enerji verimliliğini artırmaktır.

### Hedefler
* Bileşenlerin ağırlığını optimize ederek enerji verimliliğini artırmak.
* Performans ve yakıt tüketimi üzerinde etkili kritik bileşenleri belirlemek.
* Makine öğrenimi algoritmalarını kullanarak bileşenler arasındaki ilişkileri analiz etmek.
### Yöntemler
* Minimize Optimizasyonu: Araç bileşenlerinin ağırlıklarını minimize etmek amacıyla kullanılan yöntem.
* Kısıtlı Optimizasyon (SLSQP): Minimum ve maksimum ağırlık sınırları altında bileşen ağırlıklarını optimize etmek.
### Sonuçlar
* Optimize edilmiş ağırlıklarla toplam ağırlık sınırına başarıyla ulaşıldı.
* Motor ve yakıt hücresi gibi kritik bileşenlerin ağırlıkları etkili bir şekilde azaltıldı.
* Araç performansı ve enerji verimliliği açısından olumlu sonuçlar elde edildi.
* İleriye dönük olarak daha hafif malzemeler ve aerodinamik geliştirmeler önerildi.
## Proje 2: Performans Katkı Optimizasyonu
### Genel Bakış
Bu proje, araç bileşenlerinin ağırlığını optimize etmekle kalmayıp, aynı zamanda performans üzerindeki etkilerini de göz önüne alarak kapsamlı bir analiz sunmaktadır. Amaç, bileşen ağırlıklarını hem verimliliği artıracak şekilde optimize etmek hem de toplam ağırlığı sınırlandırmaktır.

### Hedefler
* Ağırlık ve performans dengesi sağlanarak optimum verimliliği elde etmek.
* Bileşenler arasında performansa katkı yapan kritik unsurları belirlemek.
### Yöntemler
* Performansa Dayalı Optimizasyon: Ağırlıkların performansa olan etkisini de minimize eden bir optimizasyon yöntemi.
* Kısıtlı Optimizasyon (SLSQP): Toplam ağırlık sınırı altında bileşenleri optimize ederken performans katkılarını da hesaba katan yöntem.
### Sonuçlar
* Performans katkılarını dikkate alarak yapılan optimizasyon, aracın verimliliğini artırdı.
* Motor ve yakıt hücresindeki ağırlık azaltmaları, performans üzerindeki olumlu etkileri destekledi.
* İleriye dönük olarak, aerodinamik performansı artırarak daha yüksek yakıt verimliliği elde edilebileceği gözlemlendi.
## Proje 3: Bileşen Analizi İçin Veri Normalizasyonu ve Kümeleme
### Genel Bakış
Bu projede, araç bileşenlerinin ağırlık ve performans verileri normalize edilerek K-Means ve DBSCAN gibi makine öğrenimi algoritmaları ile analiz edilmiştir. Amaç, bileşenleri kümelere ayırarak verinin daha net bir şekilde analiz edilmesini sağlamaktı

### Hedefler
* Farklı bileşenler arasında tutarlı karşılaştırmalar yapmak için veri normalizasyonu uygulamak.
* Araç bileşenlerini ağırlık ve performans değerlerine göre kümelere ayırmak.
* PCA kullanarak boyut indirgeme yapıp, verileri daha iyi görselleştirmek.
### Yöntemler
* StandardScaler: Bileşenlerin verilerini normalize ederek karşılaştırılabilir hale getirme.
* K-Means ve DBSCAN Kümeleme: Bileşenleri ağırlık ve performanslarına göre gruplamak için kullanılan algoritmalar.
* PCA (Temel Bileşen Analizi): Kümeleme sonuçlarını iki boyuta indirerek görselleştirme.
### Sonuçlar
* Normalizasyon, veriler arasındaki farklılıkları ortadan kaldırarak tutarlı bir analiz sağladı.
* K-Means ve DBSCAN ile belirgin bileşen grupları ortaya çıkarıldı.
* PCA kullanılarak, bileşenler arasında gizli desenler ve ilişkiler tespit edilerek daha iyi bir görselleştirme sağlandı.
