
# Recommendation-Systems
## Association Rule Learning
         1. Veri Ön İşleme
         2. ARL Veri Yapısını Hazırlama (Invoice-Product Matrix)
         3. Birliktelik Kurallarının Çıkarılması
         4. Çalışmanın Scriptini Hazırlama
         5. Sepet Aşamasındaki Kullanıcılara Ürün Önerisinde Bulunmak
## Armut Project
         1. Hizmet alan kullanıcıları ve bu kullanıcıların almış oldukları servis ve kategorileri içeren veri setini kullanarak Association Rule Learning ile ürün tavsiye sistemi oluşturulmak istenmektedir.
         ####### Veri setinin açıklanması ####### 
         2. UserId: Müşteri numarası
         3. ServiceId: Her kategoriye ait anonimleştirilmiş servislerdir. (Örnek : Temizlik kategorisi altında koltuk yıkama servisi)
         4. Bir ServiceId farklı kategoriler altında bulanabilir ve farklı kategoriler altında farklı servisleri ifade eder.
         5.(Örnek: CategoryId’si 7 ServiceId’si 4 olan hizmet petek temizliği iken CategoryId’si 2 ServiceId’si 4 olan hizmet mobilya montaj)
         6.CategoryId: Anonimleştirilmiş kategorilerdir. (Örnek : Temizlik, nakliyat, tadilat kategorisi)
         7.CreateDate: Hizmetin satın alındığı tarih
## Content Based Recommendation
         1. TF-IDF Matrisinin Oluşturulması
         2. Cosine Similarity Matrisinin Oluşturulması
         3. Benzerliklere Göre Önerilerin Yapılması
         4. Çalışma Scriptinin Hazırlanması
## Item Based Collaborative Filtering
         Veri seti: https://grouplens.org/datasets/movielens/
         1. Veri Setinin Hazırlanması
         2.User Movie Df'inin Oluşturulması
         3.Item-Based Film Önerilerinin Yapılması
         4. Çalışma Scriptinin Hazırlanması
## Model Based Matrix Factorization
         1. Veri Setinin Hazırlanması
         2. Modelleme
         3. Model Tuning
         4. Final Model ve Tahmin
## User Based Collaborative Filtering
         1. Veri Setinin Hazırlanması
         2. Öneri Yapılacak Kullanıcının İzlediği Filmlerin Belirlenmesi
         3. Aynı Filmleri İzleyen Diğer Kullanıcıların Verisine ve Id'lerine Erişmek
         4. Öneri Yapılacak Kullanıcı ile En Benzer Davranışlı Kullanıcıların Belirlenmesi
         5. Weighted Average Recommendation Score'un Hesaplanması
         6. Çalışmanın Fonksiyonlaştırılması

