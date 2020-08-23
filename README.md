# Alipay-automatically-fills-transfer-API

## Как установить

Загрузите все файлы на свой сайт

### как пользоваться

### Объяснение API

`https://example.com//?userid=999999999999999&amount=1.56&memo=For-whoring`

userid,Это идентификатор пользователя Alipay человека, получающего перевод

amount,Это сумма перевода

memo,Это примечания к передаче

### Использование на сайте

Создайте кнопку на веб-сайте и соедините ее с оператором, подобным следующему

`alipays://platformapi/startapp?saId=20000067&amp;url=https%3A%2F%2Fbank.cat%2Ftool%2Falipayautotrans%2F%3Fuserid%3D2088112119481680%26amount%3D1.56%26memo%3D123`

После `url=` должен быть URLURLencode.

Это пример

`[Pay](alipays://platformapi/startapp?saId=20000067&amp;url=https%3A%2F%2Fbank.cat%2Ftool%2Falipayautotrans%2F%3Fuserid%3D2088112119481680%26amount%3D1.56%26memo%3D123)`


