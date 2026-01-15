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
