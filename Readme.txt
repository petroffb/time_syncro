Приложение работает в двух режимах:
1) Сервер
    time_syncro -s [port]
    где
    -s		- запуск в режиме сервера
    port	- локальный порт для подключения клиентов

2) Клиент 
    time_syncro -c [ip:port] [time interval]
    где
    -с			- запуск в режиме клиента
    ip:port		- адрес и порт сервера
    time interval	- интервал опроса сервера в минутах (по умолчанию 180)