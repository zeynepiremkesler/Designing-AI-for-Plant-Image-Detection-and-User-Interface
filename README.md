# Designing-AI-for-Plant-Image-Detection-and-User-Interface
Recognizing plant images and presenting the results via a simple Swagger interface.

Her iki modelin de sonuçlarına baktığımızda, CNN modelinin eğitim doğruluk oranının oldukça yüksek olduğunu görüyoruz (%96.34). Bununla birlikte, ResNet modeli eğitim doğruluk oranı daha düşük (%51.59). Bu durumda, CNN modeli daha iyi performans gösteriyor diyebiliriz.

Ancak sadece eğitim doğruluğuna dayanarak bir modelin performansını değerlendirmek yeterli değildir. Overfitting olup olmadığını kontrol etmek için, modelin validation setindeki performansına da bakmak oldukça önemlidir.

CNN modelinin doğrulama validation %66.48 iken, ResNet modelinin doğrulama kaybı ve doğruluğu daha karmaşıktır. Ancak, ResNet modelinin doğrulama kaybı artarken, doğrulama doğruluğu düşmektedir, bu da overfitting belirtisi diyebiliriz.

Sonuç olarak, eğitim ve doğrulama performanslarına dayanarak, CNN modeli daha iyi sonuç veriyor diyebiliriz.
