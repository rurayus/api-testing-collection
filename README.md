# API Testing Collection

Bu repo Postman kullanılarak oluşturulmuş örnek bir API test koleksiyonunu içerir.  
Testler **Restful Booker** adlı herkese açık test API'si üzerinde çalışmaktadır.

## İçerik
- **GetBookingIds** → Tüm rezervasyon ID'lerini getirir.
- **GetBooking** → Belirli bir rezervasyon detayını getirir.
- **CreateBooking** → Yeni rezervasyon oluşturur.
- **UpdateBooking** → Mevcut rezervasyonu günceller.
- **PartialUpdateBooking** → Mevcut rezervasyonu kısmi olarak günceller.
- **CreateToken** → Kimlik doğrulama token’ı oluşturur.

## Güvenlik Notu
- Token, kullanıcı adı ve şifre gibi hassas bilgiler **environment değişkenleri** ile maskelenmiştir.
- Gerçek veriler bulunmamaktadır.

## Kullanım
1. Bu koleksiyonu Postman’e import edin.
2. İlgili environment değişkenlerini (`{{token}}`, `{{username}}`, `{{password}}`) doldurun.
3. Testleri çalıştırın.


**Kaynak API:** [Restful Booker](https://restful-booker.herokuapp.com/)
