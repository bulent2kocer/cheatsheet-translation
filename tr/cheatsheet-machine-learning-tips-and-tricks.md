**1. Machine Learning tips and tricks cheatsheet**

&#10230;Makina Öğrenmesi İpuçları ve Tüyolar Notları

<br>

**2. Classification metrics**

&#10230;Sınıflandırma ölçütleri

<br>

**3. In a context of a binary classification, here are the main metrics that are important to track in order to assess the performance of the model.**

&#10230;İkili bir sınıflandırma durumunda, modelin performansının değerlendirilmesi için takip edilmesi önemli ana ölçütler şunlardır.

<br>

**4. Confusion matrix ― The confusion matrix is used to have a more complete picture when assessing the performance of a model. It is defined as follows:**

&#10230;Karışıklık matrisi bir modelin performansını değerlendirirken daha bütün bir resim elde etmek için kullanılır. Aşağıdaki şekilde tanımlanır:

<br>

**5. [Predicted class, Actual class]**

&#10230;[Beklenen, Gözlenen]

<br>

**6. Main metrics ― The following metrics are commonly used to assess the performance of classification models:**

&#10230;Ana Ölçütler - Aşağıdaki ölçütler yaygın olarak sınıflandırma modellerinin performansını değerlendirmek için kullanılır:

<br>

**7. [Metric, Formula, Interpretation]**

&#10230;[Ölçüt, Formül, Yorumlama]

<br>

**8. Overall performance of model**

&#10230;Modelin genel performansı

<br>

**9. How accurate the positive predictions are**

&#10230;Olumlu tahminler ne kadar yanlışsız

<br>

**10. Coverage of actual positive sample**

&#10230;Güncel olumlu örneğin kapsamı

<br>

**11. Coverage of actual negative sample**

&#10230;Güncel olumsuz örneğin kapsamı

<br>

**12. Hybrid metric useful for unbalanced classes**

&#10230;Dengelenmemiş sınıflar için kullanışlı olan hibrit ölçüt

<br>

**13. ROC ― The receiver operating curve, also noted ROC, is the plot of TPR versus FPR by varying the threshold. These metrics are are summed up in the table below:**

&#10230;Alıcı çalışma eğrisi, ROC olarak da bilinir, TPR'nin FPR'ye karş eşik değeri değiştirerek çizilen grafiğidir. Bu ölçütler aşağıdaki tabloda toplanmıştır:

<br>

**14. [Metric, Formula, Equivalent]**

&#10230;[Ölçüt, Formül, Eşdeğeri]

<br>

**15. AUC ― The area under the receiving operating curve, also noted AUC or AUROC, is the area below the ROC as shown in the following figure:**

&#10230;Alış çalışma eğrisinin (AÇE) altında kalan alan, AUC veya AUROC olarak da bilinir, aşağıdaki şekilde gösterilen AİE'nin altında kalan alandır.

<br>

**16. [Actual, Predicted]**

&#10230;[Gözlenen, Beklenen]

<br>

**17. Basic metrics ― Given a regression model f, the following metrics are commonly used to assess the performance of the model:**

&#10230;Temel ölçütler - Bir regresyon modeli f için aşağıdaki ölçütler model performansını değerlendirmek için yaygın olarak kullanılır. 

<br>

**18. [Total sum of squares, Explained sum of squares, Residual sum of squares]**

&#10230;[Kareler toplamının toplamı, Karelerin açıklanabilir toplamı, Karelerin kalıntılar toplamı]

<br>

**19. Coefficient of determination ― The coefficient of determination, often noted R2 or r2, provides a measure of how well the observed outcomes are replicated by the model and is defined as follows:**

&#10230;Belirleme katsayısı - Belirleme katsayısı, sıklıkla R2 veya r2 olarak görülür, model tarafından gözlenen çıktıların ne kadar doğru olarak türetildiğinin bir ölçüsünü sağlar ve aşağıdaki şekilde tanımlanır:

<br>

**20. Main metrics ― The following metrics are commonly used to assess the performance of regression models, by taking into account the number of variables n that they take into consideration:**

&#10230;Ana ölçütler - Aşağıdaki ölçütler regresyon modellerinin performansını değerlendirmek için modele konu olan değişken sayısı n'i hesaba katarak yaygın olarak kullanılır. 

<br>

**21. where L is the likelihood and ˆσ2 is an estimate of the variance associated with each response.**

&#10230;L olasılık, ˆσ2 her bir cevaba ilişkin varyans tahmini olmak üzere.

<br>

**22. Model selection**

&#10230;Model seçimi

<br>

**23. Vocabulary ― When selecting a model, we distinguish 3 different parts of the data that we have as follows:**

&#10230; Sözlük - Bir model seçerken, elimizdeki verinin 3 parçasını ayrı tutarız. Bunlar:

<br>

**24. [Training set, Validation set, Testing set]**

&#10230;[Eğitim kümesi, Geçerli kılma kümesi, Test kümesi]

<br>

**25. [Model is trained, Model is assessed, Model gives predictions]**

&#10230;[Model eğitildi, Model değerlendirildi, Model öngörüleri hesapladı]

<br>

**26. [Usually 80% of the dataset, Usually 20% of the dataset]**

&#10230;[Genellikle veri kümesinin %80'i, Genellikle veri kümesinin %20'si]

<br>

**27. [Also called hold-out or development set, Unseen data]**

&#10230;[Hariç tutulan veya geliştirme kümesi, Görülmemiş veri]

<br>

**28. Once the model has been chosen, it is trained on the entire dataset and tested on the unseen test set. These are represented in the figure below:**

&#10230;Bir kere model seçildi mi, bütün bir veri kümesi üzerinde çalıştırılır ve görülmemiş test kümesi üzerinde test edilir. Bunlar aşağıdaki şekilde resmedilmiştir.

<br>

**29. Cross-validation ― Cross-validation, also noted CV, is a method that is used to select a model that does not rely too much on the initial training set. The different types are summed up in the table below:**

&#10230;Çapraz doğrulama - Çapraz doğrulama (CV) fazlaca başlangıçtaki eğitim veri kümesine dayanmayan bir model seçimi için kulllanılan bir yöntemdir. Çeşitli türleri aşağıdaki tabloda toplanmıştır:

<br>

**30. [Training on k−1 folds and assessment on the remaining one, Training on n−p observations and assessment on the p remaining ones]**

&#10230;[k-1 kat eğitim ve kalan bir tanesinin değerlendirmesi, n-p gözlem üzerinden eğitim ve p adet kalanın değerlendirilmesi]

<br>

**31. [Generally k=5 or 10, Case p=1 is called leave-one-out]**

&#10230;[Genellikle k=5 veya 10, p=1 olması halinde "birini dışarda bırak" durumu]

<br>

**32. The most commonly used method is called k-fold cross-validation and splits the training data into k folds to validate the model on one fold while training the model on the k−1 other folds, all of this k times. The error is then averaged over the k folds and is named cross-validation error.**

&#10230;En genel kullanılan yöntem, k-kat çapraz geçerleme olarak adlandırılır ve modeli bir katta geçerli kılıp, k-1 diğer katlarda eğitirken eğitim verisini k defa böler. Bunu k defa tekrar eder. Hatanın k kat boyunca ortalaması alınır ve bu çapraz geçerleme hatası olarak adlandırılır.
<br>

**33. Regularization ― The regularization procedure aims at avoiding the model to overfit the data and thus deals with high variance issues. The following table sums up the different types of commonly used regularization techniques:**

&#10230;Düzenlileştirme - Düzenlileştirme prosedürü modelin veriye aşırı uyum sağlamasına mani olmayı amaçlar ve bu nedenle yüksek varyans konularıyla ilgilenir. Aşağıdaki tabloda genel olarak kullanılan düzenlileştirme tekniklerinin farklı türleri toplanmıştır.

<br>

**34. [Shrinks coefficients to 0, Good for variable selection, Makes coefficients smaller, Tradeoff between variable selection and small coefficients]**

&#10230;[Katsayıyı 0'a çeker, Değişken seçimi için iyi, Katsayıyı küçültür, Değişken seçimi ve küçük katsayı arasında değiş-tokuş tercihi yapma]

<br>

**35. Diagnostics**

&#10230;Teşhisler

<br>

**36. Bias ― The bias of a model is the difference between the expected prediction and the correct model that we try to predict for given data points.**

&#10230;Ön eğilim - Ön eğilim bir modelin beklenen tahmini ve eldeki veri noktalarından tahmin etmeye çalıştığımız doğru model arasındaki farktır.

<br>

**37. Variance ― The variance of a model is the variability of the model prediction for given data points.**

&#10230;Varyans - Bir modelin varyansı modelin eldeki veri noktaları için değişebilirliğidir. 

<br>

**38. Bias/variance tradeoff ― The simpler the model, the higher the bias, and the more complex the model, the higher the variance.**

&#10230;Ön eğilim/Varyans değiş-tokuş tercihi - Model basitleştikçe ön eğilim artar, model karmaşıklaştıkça varyans artar.

<br>

**39. [Symptoms, Regression illustration, classification illustration, deep learning illustration, possible remedies]**

&#10230;[Belirtiler, Regresyon çizimi, sınıflandırma çizimi, derin öğrenme çizimi, olası çözüm]

<br>

**40. [High training error, Training error close to test error, High bias, Training error slightly lower than test error, Very low training error, Training error much lower than test error, High variance]**

&#10230;[Yüksek eğitim haası, Eğitim hatası test hatasına yakın, Yüksek ön eğilim, Eğitim hatası test hatasından biraz daha az, Çok az eğitim hatası, Eğitim hatası test hatasından çok daha az, Yüksek varyans ]

<br>

**41. [Complexify model, Add more features, Train longer, Perform regularization, Get more data]**

&#10230;[Modeli karmaşıklaştır, Başka özellik ekleme, Daha uzun eğitme, Düzenlileştirme uygulama, Daha fazla veri]

<br>

**42. Error analysis ― Error analysis is analyzing the root cause of the difference in performance between the current and the perfect models.**

&#10230;Hata analizi - Hata analizi mevcut ve hatasız modellerin performansları arasındaki farkın kök nedeninin analiz edilmesidir. 

<br>

**43. Ablative analysis ― Ablative analysis is analyzing the root cause of the difference in performance between the current and the baseline models.**

&#10230;Ayrılma analizi - Ayrılma analizi mevcut ve hatasız anahat modellerin performansları arasındaki farkın kök nedeninin analiz edilmesidir. 

<br>

**44. Regression metrics**

&#10230;Regresyon ölçütleri

<br>

**45. [Classification metrics, confusion matrix, accuracy, precision, recall, F1 score, ROC]**

&#10230;[Sınıflandırma ölçütleri, karmaşıklaştırma matrisi, Kesinlik, Keskinlik, Hatırlama, F1 skoru, Alıcı Çalışma Eğrisi]

<br>

**46. [Regression metrics, R squared, Mallow's CP, AIC, BIC]**

&#10230;[Regresyon ölçütleri, R kare, Mallow CP, Akaike Bilgi Ölçütü, Bayesian Bilgi Ölçütü]

<br>

**47. [Model selection, cross-validation, regularization]**

&#10230;[Model seçimi, çapraz geçerleme, düzenlileştirme]

<br>

**48. [Diagnostics, Bias/variance tradeoff, error/ablative analysis]**

&#10230;[Teşhisler, Ön eğilim / varyans değiş tokuşu, hata/ayrılma analizi]
