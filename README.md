# Emalak invest

### Структура проекта
* config - модуль для чтения конфигурационного файла
* moex - модуль для получения данных Московской биржи через <a href="https://pypi.org/project/apimoex/">API</a>
* postgres - модуль для работы с СУБД PostgreSQL
* config.json - файл конфигурации проекта
* Dockerfile - файл для сборки Docker контейнера
* main.py - точка входа Frontend приложения
* markowitz.py - реализация модели Марковица
* optimizer.py - оптимизация портфеля

### Сборка и запуск проекта
docker build -t emalak .
docker run -p 28003:28003 emalak
