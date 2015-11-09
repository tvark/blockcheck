blockcheck
==========

Утилита для определения типа блокировок сайтов из единого реестра запрещенной информации на стороне провайдера.

Данная утилита позволяет определить:

* Подмену DNS-ответов
* Перенаправление DNS-серверов
* Блокировку DNS-серверов
* "Обычный" DPI (фильтрация URL на определенных IP-адресах и портах)
* "Полный" DPI (фильтрация URL на всех IP-адресах и/или портах)
* Подмену SSL(HTTPS)-сертификата (прослушивание HTTPS-трафика)
* Блокировку по IP-адресу

Приложение автоматически отправляет статистику об используемом типе блокировки на сервер.

http://habrahabr.ru/post/229377/ — статистика по провайдерам

### Установка
Для работы скрипта требуется модуль dnspython3. Установить его можно из репозитория вашего дистрибутива, или используя pip:
`pip install -r requirements.txt`
