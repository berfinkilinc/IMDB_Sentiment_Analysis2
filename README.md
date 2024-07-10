#IMDB Sentiment Analysis With Tensorflow

Bu proje Trakya Üniversitesi Bilgisayar Mühendisliği bölümü Yapay Sinir Ağları dersi için yapılmıştır. Amacı 50.000 adet pozitif ve negatif yorumdan oluşan veri setini kullanarak anlam analizi yapmaktır. 
Veri temizleme, görselleştirme, binary hale getirme işlemlerini takip eden bir model kurma, modeli eğitme aşamalarından oluşur. Denenen birçok model ve tek bir başarılı modelin parametrelerinde 
yapılan değişiklikler göz önüne alındığında en başarılı sonuçları IMDB_sentiment_analysis_with_tensorflow_2_berfin.ipynb dosyası içerisindeki model vermektedir. 
Projenin kapsamında derin öğrenme modeliyle karşılaştırmak üzere bir makine öğrenmesi algoritması da anlam analizi yapmak için kullanılmıştır. Bu yöntem de doğruluk puanı açısından çok iyi sonuçlar verse de
gerçek hayat verileriyle test edildiğinde deep learning modeline göre daha başarısız kalmıştır. Ancak süre açısından bakıldığında makine öğrenmesi yönteminin çok daha hızlı olduğu ve dakikalar içinde sonuç döndürdüğü
gözlemlenmiştir. 


This project was completed for the Neural Networks course in the Computer Engineering Department at Trakya University. The goal is to perform sentiment analysis using a dataset of 50,000 positive and negative reviews.
The project includes the following stages: data cleaning, visualization, binarization, model building, and model training. Among the many models tested and the changes made to the parameters of a single successful model, the most successful results are provided by the model in the file IMDB_sentiment_analysis_with_tensorflow_2_berfin.ipynb.
As part of the project, a machine learning algorithm was also used for sentiment analysis to compare with the deep learning model. Although this method yielded very good results in terms of accuracy, it was less successful than the deep learning model when tested with real-world data. However, in terms of time efficiency, the machine learning method was observed to be much faster, producing results within minutes.
