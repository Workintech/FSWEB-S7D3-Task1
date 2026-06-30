# Görev 1: GDPR/KVKK Onayı

Yeni çıkan kanunlar veya regulasyonlar sonucunda uygulamalarımızda bazı kurallara dikkat etmemiz gerekiyor.
Avrupa ve Amerika'daki GDPR, Türkiye'deki KVKK ve Rıza metni onayı buna örnek verilebilir.
Kullanıcılardan izin almadan kişisel verilerin kullanımını yasaklayan bu kurallardan dolayı uygulamalarda onay almak gerekiyor.

Sen de bunu kendi sitene eklemek istiyorsun.

İlk olarak görevin,
[ ] tasarımdaki(https://i.ibb.co/nktxBV8/s7d3-task1.png) gibi "I agree to terms of service and privacy policy" onayını bir checkbox kullanarak almak.
[ ] Bunu seçmeden Sign In butonu aktif olmamalı.
[ ] checkbox'ın name ve id'sini `terms` yapmalısın.
[ ] checkbox için kullandığın label'da `htmlFor="terms"` eklemeyi unutmamalısın.

- İpucu: handleChange'de checkbox için value değerini checked'den almasını sağlayabilirsin.
- İpucu: Test için erdem.guntay@wit.com.tr adresini 9fxIH0GXesEwH_I şifresini kullanabilirsin.

## Önemli Notlar

- Proje dizinindeki `user.json` dosyasını bulun ve `user_id` alanını NextGen proje ekranında görünen kendi `user_id` değeriniz ile güncelleyin.
- Geliştirme sırasında testleri izlemek için `npm test` komutunu kullanın.
- Testleri çalıştırıp skoru NextGen'e kaydetmek için `npm run sendresults` komutunu kullanın.
