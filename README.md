# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Андрющенко Вячеслав`


---

### Задание 1  Кеширование  


Приведите примеры проблем, которые может решить кеширование.

Приведите ответ в свободной форме.


### Решение 1  


Кеширование позволяет увеличить скорость доступ к данным, не делая каждый раз полные запросы. Так же это снижает нагрузку на сервер, засчет того что данные уже будут в кеше сервера.
С помощью кеширования можно снизить нагрузку на сетевой трафик, ведь повторно запросы в сеть не нужно будет делать.





### Задание 2 Memcached


Установите и запустите memcached.

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.



### Решение 2  

![memcached](/pic/1.png) 


### Задание 3 Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.


### Решение 3


Внесение в кеш ключа с TTL 5, и проверка его через 5 секунд.  

![memcached](/pic/2.png) 


### Задание 4 Запись данных в Redis 


Запишите в Redis несколько ключей с любыми именами и значениями. 

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.



### Решение 4  

![redis](/pic/3.png) 
