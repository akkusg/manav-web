# manav-web

Uygulama `MANAV_SECRET_KEY` ve `MANAV_DB_URI` adında iki ortam değişkeni okur.
Bu değişkenler tanımlı değilse sırasıyla `bizim cok zor gizli sozcugumuz` ve
`mongodb://localhost:27017/` değerleri kullanılacaktır.

Kullanıcı tablosu oluşturulmalı
admin kullanıcısı için:

{
    "_id" : "admin@manavim.com",
    "ad" : "Admin Manavoğlu",
    "rol" : "yonetici",
    "sifre" : "1234"
}
