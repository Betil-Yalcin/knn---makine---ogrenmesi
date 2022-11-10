# knn---makine---ogrenmesi
 
 ### KNN NEDİR?
 > K-NN (K-Nearest Neighbors) algoritması, model oluşturmaksızın; sınıflandırma ve regresyon problemlerinin her ikisi üzerinde de çalışabilen, 
 denetimli makine öğrenmesi algoritmasıdır. Veriler üzerinde basit denebilecek bir çıkarımla tahmin yapmaktır. 
 Bu çıkarıma göre; etiket değeri tahmin edilecek bir veri için, n-boyutlu bir uzayda, kendisine en yakın k komşunun etiket değerleri referans alınmalıdır.
 
 ### KNN ALGORİTMASI NASIL ÇALIŞIR?

1.	Öncelikle K değeri belirlenir.
2.	Durum için doğru uzaklık türü belirlenir
3.	Diğer nesnelerden hedef nesneye olan uzaklık hesaplanır.
4.	Uzaklıklar sıralanır ve en minimum uzaklığa bağlı olarak en yakın komşular bulunur.
5.	En yakın komşu kategorileri toplanır.
6.	En uygun komşu kategorisi seçilir.

### KNN ALGORİTMASI UZAKLIK TÜRLERİ

![uzaklık turleri](https://miro.medium.com/max/4800/1*tmVrNGuX9ncLrvbyfcEPew.png)

### K NEYE GÖRE SEÇİLMELİ?

![k secimi](https://miro.medium.com/max/4800/1*WMYPGr9F7YGwnlOodXl2BQ.png)

### K FAKTÖRÜNÜN DOĞRULUĞA ETKİSİ

![k dogruluk](https://miro.medium.com/max/720/1*mzC-Zh6dUrBuww9O_ZdJGw.jpeg)

### KNN AVANTAJLARI

- Basit algoritma olması sebebiyle yorumlaması, uygulaması kolaydır.
- Mesafe metriği istenildiği gibi seçilebilir.
- Regresyon ve sınıflandırma için kullanışlıdır.
  - Doğrusal olmayan karar sınırlarını öğrenebilir.
- Eğitim (Training) süresi kısadır.
  - Tüm iş tahmin sırasında gerçekleşir.
- Sürekli olarak gelişir.
  - Eğitim adımı olmadığından, veri kümesine her yeni veri eklediğimizde gelişmiş olur.
- Veriler üzerinde varsayımda bulunmaz (non-parametric). 
- Yüksek doğruluk (accuracy) ile sonuca varır.


### KNN DEZAVANTAJLARI

- Non-parametric olması sebebiyle her tahminde bütün eğitim verilerinin kullanılması gerekir.
- Tembel (lazy) öğrenme algoritmasıdır.
- Tüm veri seti eğitim seti olarak kullanılır.
  - Bu sebeple öğrenmek yerine ezberler (Overfitting).
- Yanlış etiketlenmiş bir veri sınıf sınırlarını değiştirebilir.
- Veri kalitesine göre doğruluk (accuracy) değişebilir.
- Gürültülü veya kullanılması mümkün olmayan veriler.
- Büyük veri ile çalışmalarda tahmin yavaş olabilir. Hesaplama maliyeti yönünden pahalı olabilir.
- Veri sayısı artınca, tahmin uzun sürebilir.
- Tüm eğitim (training) verilerini saklamak için yüksek bellek gerekir.

### KNN KULLANIM ALANLARI

- Genetik ve tıp bilimi
  -[[.](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-7-S1-S11)]
- Ekonomi
  -[[.](https://www.researchgate.net/publication/304826093_Application_of_K-nearest_neighbor_KNN_approach_for_predicting_economic_events_theoretical_background )]
- Tarım
  -[[.](https://ijisrt.com/assets/upload/files/IJISRT20MAY722.pdf)]
- Politika
  -[[.](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cit2.12046)]
- Tavsiye sistemleri
  -[[.](https://www.aurigait.com/blog/recommendation-system-using-knn/#:~:text=kNN%20is%20a%20machine%20learning,of%20top%2Dk%20nearest%20neighbors. )]
- Bankacılık
  -[[.](https://www.researchgate.net/publication/355346798_Performance_Analysis_of_K-Nearest_Neighbor_Classification_Algorithms_for_Bank_Loan_Sectors)]
- Yüz tanıma
  -[[.](https://www.researchgate.net/publication/340573794_Face_Identification_Based_on_K-Nearest_Neighbor)]
  
  
  Not: [.] simgesi kaynakça belirtir.
