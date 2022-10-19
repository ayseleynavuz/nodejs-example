# nodejs-example

Bu ödevde postman kullanılmıştır.
 
## Ödev için istenen senaryo

- /hello şeklinde path tanımlaması yapılacak.
- /hello path'ine GET, POST, PUT ve DELETE istekleri atılmalıdır. 
- Atılan her istekte bir middleware çalışıp konsola "Yeni bir istek geldi." diye log basmalı.


- GET isteği atıldığı zaman "Merhaba, GET isteği attınız" diye bir mesaj dönmeli.
- POST isteği atıldığı zaman "Merhaba, POST isteği attınız" diye bir mesaj dönmeli.
- Yanıtı dönmeden önce bir middleware çalışmalı ve "Post iseği için istek gönderildi" diye log atması gerekmektedir. 
- PUT isteği atıldığı zaman "Merhaba, PUT isteği attınız" diye bir mesaj dönmeli.
- DELETE isteği atıldığı zaman "Merhaba, DELETE isteği attınız" diye bir mesaj dönmeli.


## Kullanılan komutlar
```
npm install express
npm install cors
npm install body-parser
npm install -g nodemon

```
