# HTTP ve REST API Temelleri

1. HTTP Nedir?
HTTP (HyperText Transfer Protocol), istemci (browser, mobil uygulama) ile sunucu arasındaki iletişim kurallarıdır.
İsteği (request) frontend gönderir
Cevabı (response) backend döndürür
Get veri getirir
Post yeni veri ekler
Put veriyi tamamen günceller
Patch verinin sadece bir kısmını günceller
2. REST API Nedir?
REST (Representational State Transfer), API tasarlamak için kullanılan yaygın bir yaklaşımdır. HTTP metotlarını (GET, POST, PUT, DELETE vb.) kullanarak kaynaklara erişmeyi sağlayan mimari yaklaşımdır. REST API'lerde veri genellikle JSON formatında taşınır ve frontend ile backend arasındaki iletişim bu yapı üzerinden gerçekleştirilir.
Örneğin doktorlar için /doctors bizim kaynağımız olsun. 
Tüm doktorları getirmek için GET/doctors 
Tek doktor getirmek için GET/doctors/5  yazarız
Doktor eklemek için POST /doctors   yazarız

Client ve Server arasındaki iletişimi sağlayan HTTP protokolünü detaylıca inceledim. GET, POST, PUT, DELETE gibi HTTP metodlarının ne işe yaradığını ve 200, 404, 500 gibi HTTP durum kodlarının anlamlarını öğrendim. RESTful mimari prensiplerinin standartlarını kavradım.