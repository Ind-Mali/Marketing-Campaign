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

Bu ??al????man??n ama???? markete gelen m????terilerin olu??turulacak olan kampanyaya evet veya hay??r deme olas??l??klar??n?? tahmin etmektir. 
Yap??lanlar; 
1. ??ncelikle istatistikten yararlan??larak veri setindeki ayk??r?? ve bo?? veriler ile u??ra????ld??. Bo?? veriler dolduruldu veya veri setinden at??ld??. 
2. Grafikler olu??turularak veri setini daha anlaml?? hale getirme ??al????malar?? yap??ld??. 
3. Olu??turulan grafikler mant??k ??ercevesinde yorumlanarak mant??ksal ????kar??lmalar elde edildi. 
4. Kimlere daha ??ok yo??unla????laca????na karar verildi.
5. Makine ????renmesi algoritmalar?? i??in veri setindeki dengesizlik giderildi. ??ncelikle %85 gibi y??ksek bir oranda insanlar hay??r cevab?? verirken bu oran RandomUnderSamplier algoritmas?? kullan??larak %50'ye ??ekildi.
6. CrossValidation kullan??larak veri setine uygulanacak olan Makine ????renmesi algoritmalar?? i??in veri setinden e??it veriler al??narak bu verilere algoritmalar uygulanarak tahminlerin ortalamas?? al??nd??. Bunun sebebi ise algoritmalar??n veri seti ile e??itildikten sonra elde edilecek tahminleri elde etmek idi.
7. Baz?? algoritmalar??n hyper parametreleri i??in ayarlamalar yapmak i??in bu parametreler belirlendi ve GridSearch Algoritmas?? ile bu parametrelerin i??inden optimum sonu??lar?? verenler elde edildi ve test setinde kullan??ld??.
8. %50 oran??nda olan oran %73 oran??na ????kart??ld??. Yani bir ki??inin veri setindeki belirlenen ??zelliklerini biliyor ve bunu test edersek bu ki??inin kampanyaya evet ya da hay??r diyecegini %73 oran??nda bilebiliriz. 
9.  S??n??fland??rma raporunu g??z ??n??ne al??rsak; RECALL parametresinin %86 oldu??unu g??rebiliriz. 
Ger??ekte verisetinde 1 olan ve algoritman??n da 1 olarak tahmin etti??i ki??ilerin oran??n?? g??sterir. 
Yani algoritman??n 1 olarak tahmin etti??i ki??ileri arad????m??zda %86 oran??nda bir ba??ar?? elde ederiz.

Sonu??,
Market %86 oran??nda bir kampanyaya kat??l??m sa??lam???? olursa bu marketin kazanc?? ac??s??ndan olumlu sonu??lanm???? olacakt??r. Ayr??ca bu arama i??lemlerini bilerek arad?????? i??in belirlemi?? oldu??u rakamlara daha ??abuk ula??arak zamandan ve paradan kar elde etmi?? olacakt??r.

