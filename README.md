# Atificial-Neural-Network-SFS-Yapay-Sinir-Aglari

Artificial Neural Network yani Yapay Sinir Ağları uygulaması drive üzerinden Colab platformunda gerçekleştirilmiştir. Kodlar python dilindedir. Baştaki bağlantı kodlarını kullanmazsanız, spyder platformunda da kullanabilirsiniz. Fakat Colabda daha hızlı sonuç alınmaktadır.

Veriseti: 13611 satır, 17 sütundan oluşan sayılardan ibarettir. Dosya uzantısı .csv dir. ilk 16 sütun feature lardan oluşurken, son sütun class sütunudur. class 0-6 (categorical) arasındaki sayılardan oluşmaktadır.

Veriler önce min-max yöntemi kullanılarak normalize edilmiştir.

-------------
FEATURE AZALTMAK İÇİN BU PROJEDE 2 FARKLI YÖNTEM VERİLMİŞTİR. 2 FARKLI KOD BLOĞU ŞEKLİNDE YAZILMIŞTIR. HANGİSİ KULLANILMAK İSTENİRSE, DİĞER KOD BLOĞUNU ÇALIŞTIRILMAMASI GEREKİR.

1- SFS 
SFS (Sequential Feature Selection) yöntemi kullanılarak toplam 16 adet feaure sayısı istenilen feature sayısına indirgenerek, daha az sayıda feature ile daha anlamlı sonuçlar üretilmek istenilmiştir.
Bu projede istenilen feature sayısı 6 dır. 16 featuredan 6 featurea indirgenmiştir.

2- PCA 
PCA (Principle Component Analysis) yöntemi kullanılarak toplam 16 adet feaure sayısı istenilen feature sayısına indirgenerek, daha az sayıda feature ile daha anlamlı sonuçlar üretilmek istenilmiştir.
Bu projede istenilen feature sayısı 9 dur. 16 featuredan 9 featurea indirgenmiştir.
--------------

MLP yapısı kurularak model eğitilmiştir. 

Confusion matrix son olarak modelin çıktısını görebilmek için gösterilmektedir.
