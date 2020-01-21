# smart-chat-sample
Реализовать решение smart-chat.  Стек: ruby 2.5.5, Action Cable, фронт любой.

1)Реализовать echo  чат(чат на web-sockets(Action Cable) где под каждого пользователя создается канал и сервер отвечает тем же сообщением что получил)
2)Реализовать в рамках чата команду конвертации валюты(из гривны в нужную величину) на базе privat bank publik API( https://api.privatbank.ua/p24api/exchange_rates?json&date=%s - брем текущую или произвольную дату https://api.privatbank.ua/#p24/exchangeArchive). Следующую команду
 /convert(value,to)  example /convert(100,USD)
Пример работы системы:
User: Hello
Server: Hello
User:/convert(100,USD)
Server: 4,11
3)Тест конвертации на базе rspec
Дизайн не принципиален. 
