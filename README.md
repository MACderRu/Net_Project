### Описание протокола:

Реализован протокол Dictionary Server Protocol.

https://tools.ietf.org/html/rfc2229

Поддерживаемые комады:

    3.1 - Initial connection
    3.2 - DEFINE
    3.3 - MATCH
    3.5 - SHOW
    3.6 - CLIENT
    3.7 - STATUS
    3.8 - HELP
    3.9 - QUIT

### Cборка

    1. make all - собрать и клиент, и сервер.
    2. make client - собрать клиента.
    3. make server - собрать сервер.
    4. make run-client ADDRESS=address - запустить клиента, передав ему в качестве адреса сервера, 
    к которому он должен подключаться, address. Например, make run-client ADDRESS=127.0.0.1
    5. make run-server - запустить сервер.
    6. make clean - удалить из директории запускаемые и объектные файлы.

(Client-server/)
