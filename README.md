Örnekleme Simülasyonu: Sayıların Gücü
Hiç merak ettiniz mi; bir ankette 10 kişiyle konuşmak neden yetmez de binlerce kişiye ulaşmaya çalışırız? Bu proje, "Daha fazla veri, daha az hata" ilkesini Python kullanarak görsel bir kanıta dönüştürüyor.

🔍 Neyi İnceledim?
İstatistikte Basit Rastgele Örnekleme yaparken, küçük gruplar bizi yanıltabilir. Şans eseri hep uç değerleri (çok yaşlılar veya çok zenginler gibi) seçebiliriz. Ben bu "şans faktörünün" (varyans) veri boyutu arttıkça nasıl etkisiz hale geldiğini simüle ettim.

🛠️ Ne Yaptım? (Hokus Pokus Kısmı)
Ham Veri: Önce 10.000 kişilik hayali bir topluluk oluşturdum.

Zikzakları Silmek: Tek bir çekim yapıp "tamam oldu" demedim. Her örneklem boyutu için 100 farklı deneme yapıp bunların ortalamasını aldım. Buna "gürültü temizleme" diyoruz.

Sonuç: Ortaya çıkan grafik, rastgeleliğin içindeki o mükemmel düzeni; yani veri arttıkça hatanın nasıl sıfıra süzüldüğünü gösteriyor.

💡 Bana Ne Öğretti?
Bu çalışma sadece bir grafik değil; Büyük Sayılar Yasası'nın (Law of Large Numbers) çalışan bir örneği. Veri biliminde "yeterli örneklem" kavramının neden hayati olduğunu ve küçük verilerle karar vermenin ne kadar riskli olduğunu bu sayede koda dökmüş oldum.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🌍 (English Version)
🎯 Sampling Simulation: The Power of Numbers
Have you ever wondered why talking to 10 people in a survey isn't enough, but reaching thousands is? This project provides a visual proof of the "More data, less error" principle using Python.

🔍 What Did I Investigate?
In statistics, when using Simple Random Sampling, small groups can be misleading. By chance, we might only pick outliers (like only the very old or very wealthy). I simulated how this "chance factor" (variance) becomes insignificant as the sample size increases.

🛠️ What Did I Do? (The Magic Behind the Scenes)
Raw Data: I generated a synthetic population of 10,000 individuals.

Cleaning the Noise: I didn't just take a single sample and call it a day. For each sample size, I performed 100 different trials and calculated their average. This is known as "noise reduction."

The Result: The resulting graph shows the perfect order within randomness; specifically, how the error smoothly glides toward zero as the data grows.

💡 Key Takeaway
This study is more than just a chart; it is a working demonstration of the Law of Large Numbers. Through this simulation, I’ve coded the fundamental reason why "adequate sample size" is vital in data science and why making decisions based on small datasets is highly risky.


