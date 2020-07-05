# -RU-WildRhoades - Core
Это Diasant Comp. для RedM, написанный на C#, совместимый с LUA.

Основа - VORP с доработкой [https://github.com/VORPCORE/VORP-Core], чтобы взять и использовать у себя, то вам надо спросить разрешения на использования доработанной версии VORP.

# -RU- Требования
1. Получить разрешение на использование доработанной версией VORP. (На эти файлы действует лицензия)
2. Чтобы у вас все работало надо скачать - https://github.com/GHMatti/ghmattimysql/releases

# -RU- Как установить?

Скачать ghmattimysql

Скопируйте и вставьте ghmattimysqlпапку в `resources/ghmattimysql`

Удалить файл `resources/ghmattimysql/config.json`

Добавить `set mysql_connection_string "mysql://mysqluser:password@localhost/vorp"` в свой server.cfg файл

Добавить `ensure ghmattimysql` в свой server.cfg файл

Скопируйте и вставьте wr_core папку в `resources/wr_core`

Добавить `ensure vorp_core` в свой server.cfg файл

Чтобы изменить язык, перейдите `resources/vorp_core/Config` и измените язык по умолчанию

Пример Server.cfg
