# Marketing-Campaign
The final Project for Techcareer.net using Data Analysis and Science Tools
There is the Dataset's link inside the jupyter notebook.

The aim of this study is to estimate the probability of the customers coming to the market to say yes or no to the campaign to be created.
What has been done;
1. First of all, outliers and empty data in the data set were dealt with by using statistics. Empty data has been filled in or removed from the dataset.
2. Efforts were made to make the data set more meaningful by creating graphics.
3. Logical deductions were obtained by interpreting the generated graphs within the framework of logic.
4. It was decided on whom to focus more.
5. The imbalance in the dataset for machine learning algorithms has been fixed. First of all, while 85% of people answered no, this rate was reduced to 50% using the RandomUnderSamplier algorithm.
6. For the Machine Learning algorithms to be applied to the data set using CrossValidation, equal data were taken from the data set and the algorithms were applied to these data and the average of the estimates was taken. The reason for this was to obtain the predictions to be obtained after the algorithms were trained with the data set.
7. To make adjustments for the hyper parameters of some algorithms, these parameters were determined and the GridSearch Algorithm gave the optimum results from these parameters and used in the test set.
8. The rate from 50% was increased to 73%. In other words, if we know the determined characteristics of a person in the data set and test it, we can know with a rate of 73% that this person will say yes or no to the campaign.
9. Considering the classification report; We can see that the RECALL parameter is 86%.
It shows the proportion of people who are actually 1 in the dataset and which the algorithm predicts to be 1.
In other words, when we search for people that the algorithm predicts as 1, we get 86% success.

Conclusion,
If the market participates in a campaign at the rate of 86%, it will have a positive result in terms of the profit of this market. In addition, since he deliberately searches for these search operations, he will reach the numbers he has determined more quickly and will profit from time and money.


[TR]

Bu çalışmanın amaçı markete gelen müşterilerin oluşturulacak olan kampanyaya evet veya hayır deme olasılıklarını tahmin etmektir. 
Yapılanlar; 
1. Öncelikle istatistikten yararlanılarak veri setindeki aykırı ve boş veriler ile uğraşıldı. Boş veriler dolduruldu veya veri setinden atıldı. 
2. Grafikler oluşturularak veri setini daha anlamlı hale getirme çalışmaları yapıldı. 
3. Oluşturulan grafikler mantık çercevesinde yorumlanarak mantıksal çıkarılmalar elde edildi. 
4. Kimlere daha çok yoğunlaşılacağına karar verildi.
5. Makine öğrenmesi algoritmaları için veri setindeki dengesizlik giderildi. Öncelikle %85 gibi yüksek bir oranda insanlar hayır cevabı verirken bu oran RandomUnderSamplier algoritması kullanılarak %50'ye çekildi.
6. CrossValidation kullanılarak veri setine uygulanacak olan Makine Öğrenmesi algoritmaları için veri setinden eşit veriler alınarak bu verilere algoritmalar uygulanarak tahminlerin ortalaması alındı. Bunun sebebi ise algoritmaların veri seti ile eğitildikten sonra elde edilecek tahminleri elde etmek idi.
7. Bazı algoritmaların hyper parametreleri için ayarlamalar yapmak için bu parametreler belirlendi ve GridSearch Algoritması ile bu parametrelerin içinden optimum sonuçları verenler elde edildi ve test setinde kullanıldı.
8. %50 oranında olan oran %73 oranına çıkartıldı. Yani bir kişinin veri setindeki belirlenen özelliklerini biliyor ve bunu test edersek bu kişinin kampanyaya evet ya da hayır diyecegini %73 oranında bilebiliriz. 
9.  Sınıflandırma raporunu göz önüne alırsak; RECALL parametresinin %86 olduğunu görebiliriz. 
Gerçekte verisetinde 1 olan ve algoritmanın da 1 olarak tahmin ettiği kişilerin oranını gösterir. 
Yani algoritmanın 1 olarak tahmin ettiği kişileri aradığmızda %86 oranında bir başarı elde ederiz.

Sonuç,
Market %86 oranında bir kampanyaya katılım sağlamış olursa bu marketin kazancı acısından olumlu sonuçlanmış olacaktır. Ayrıca bu arama işlemlerini bilerek aradığı için belirlemiş olduğu rakamlara daha çabuk ulaşarak zamandan ve paradan kar elde etmiş olacaktır.

