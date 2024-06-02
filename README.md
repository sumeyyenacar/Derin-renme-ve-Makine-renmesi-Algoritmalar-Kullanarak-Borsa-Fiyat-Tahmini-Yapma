# Derin-renme-ve-Makine-renmesi-Algoritmalar-Kullanarak-Borsa-Fiyat-Tahmini-Yapma
Derin Öğrenme ve Makine Öğrenmesi Algoritmaları Kullanarak Borsa Fiyat Tahmini Yapma

ÖZET
Bu çalışma, borsa fiyatlarının tahmin edilmesinde derin öğrenme ve makine öğrenimi tekniklerinin performansını değerlendirmeyi amaçlamaktadır. Bu anlamda çeşitli derin öğrenme ve makine öğrenmesi modelleri geliştirilerek performansları karşılaştırılmıştır.   İlk olarak, Uzun Kısa Süreli Bellek (LSTM) ve Çift Yönlü Uzun Kısa Süreli Bellek (Bidirectional LSTM) modelleri geliştirilerek tahminler gerçekleştirilmiştir. Bu modellerinin genel anlamda, hisse fiyatlarını tahmin etmede oldukça etkili oldukları görülmüştür. Özellikle Bidirectional LSTM modelinin, veriye hem ileri hem de geriye doğru bakması, yapılan tahminlerin daha doğru olmasını sağlamıştır. Ardından, Evrişimsel Sinir Ağları (CNN) modeli geliştirilmiş ve görsel veriler üzerinde başarılı tahminler elde edilmiştir. Evrişimsel Sinir Ağları modeli genel anlamda hem iyi tahminlerde bulunmuş, hem de LSTM ve Bidirectional LSTM algoritmalarına göre çok daha hızlı çalıştığı gözlemlenmiştir. Ancak bu modellere kıyasla, daha fazla oranda eğitim verisine ihtiyaç duyduğu görülmüştür. Ayrıca, Tekrarlayan Sinir Ağları’nın (RNN) uzun vadeli bağımlılıkları öğrenmede zorluk yaşadığı gözlemlenmiştir. Bu sorun, gradyanların kaybolması (vanishing gradient) veya patlaması (exploding gradient) gibi problemlerden kaynaklanır. Bu model ile yapılan hisse fiyat tahminlerinde, veri miktarı arttıkça tahminlerin kötüleştiği görülmüştür. Daha sonra, Yığınlanmış Topluluk Modeli (Stacked Ensemble) yöntemiyle modeller birleştirilerek daha güçlü bir tahmin modeli oluşturulmuştur. Kapılı Tekrarlayan Birim modeli (GRU) ve LSTM benzer bir yapıya sahip olmasına rağmen, daha basit bir mimariye sahip olduğundan dolayı ani iniş ve çıkışları tahmin etme konusunda diğer modellere kıyasla geride kaldığı görülmüştür. Ancak, daha basit bir mimariye sahip olması sayesinde daha hızlı çalışmaktadır. Aşırı Gradyan Artırma (XGBOOST) modelinde eğitim verisinin oranı azaltıldığında, tahminlerin tutarsızlaştığı gözlemlenmiştir. Bu model, büyük veri setlerinde daha etkili tahminler yapmaktadır. Stacked ensemble modeli ise tüm bu modellerin tahminlerini birleştirerek daha doğru tahminler elde etmiştir. Sonuç olarak, geliştirilen derin öğrenme ve makine öğrenmesi modellerinin, veristeleri doğru şekilde verildiğinde, hisse senedi kapanış fiyatlarını iyi şekilde tahmin edebildikleri görülmüştür. 
Anahtar kelimeler: LSTM, Bidirectional LSTM, RNN, CNN, GRU, XGBOOST, Stacked Ensemble, Derin Öğrenme, Makine Öğrenmesi, Borsa. 

ABSTRACT
This study aims to evaluate the performance of deep learning and machine learning techniques in predicting stock prices. In this regard, various deep learning and machine learning models have been developed and their performances have been compared. Stock price data of Amazon and other companies have been used as the dataset. Firstly, Uzun Kısa Süreli Bellek (LSTM) and Bidirectional Uzun Kısa Süreli Bellek (Bidirectional LSTM) models were developed and predictions were made. It was observed that these models were quite effective in predicting stock prices overall. Especially, the Bidirectional LSTM model, which looks at the data both forward and backward, ensured more accurate predictions. Then, a Convolutional Neural Network (CNN) model was developed and successful predictions were obtained on visual data. The CNN model generally made good predictions and was observed to work much faster compared to LSTM and Bidirectional LSTM algorithms. However, it was noted that this model required a larger amount of training data compared to these models. Additionally, Recurrent Neural Networks (RNN) faced difficulties in learning long-term dependencies. This issue arises from problems such as vanishing or exploding gradients. In stock price predictions made with this model, it was observed that as the amount of data increased, the predictions worsened. Subsequently, models were combined using the Stacked Ensemble method to create a stronger prediction model. Although the Gated Recurrent Unit (GRU) model has a similar structure to LSTM, it was observed to lag behind other models in predicting sudden ups and downs due to its simpler architecture. However, thanks to its simpler architecture, it works faster. In the Extreme Gradient Boosting (XGBOOST) model, it was observed that reducing the training data ratio led to inconsistent predictions. This model makes more effective predictions on large datasets. The Stacked Ensemble model, on the other hand, combined the predictions of all these models to obtain more accurate predictions. In conclusion, it was observed that the developed deep learning and machine learning models could predict stock closing prices well when given the right datasets.



