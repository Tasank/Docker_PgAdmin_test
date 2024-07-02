# Docker Projects

## Docker_pgadmin

### Описание
Этот проект позволяет запустить PgAdmin через Docker. PgAdmin - это веб-интерфейс для управления PostgreSQL базами данных.

### Видео-инструкция
Вы можете посмотреть видео-инструкцию автора идеи по настройке и запуску PgAdmin через Docker по следующей ссылке: [Видео-инструкция](https://www.youtube.com/watch?v=NkPvabFLKsg&t=30s).

### Репозиторий с инструкцией
Полная инструкция по запуску PgAdmin через Docker доступна в репозитории автора: [Инструкция запуска](https://github.com/Kishinskiy/postgres-compose).

## first_docker_project

### Описание
Этот проект позволяет запустить сервер PostgreSQL через Docker.

### Запуск 

1. Клонируйте репозиторий:
    

    ```git clone https://github.com/Tasank/Docker_PgAdmin_test.git```
    cd your-repository/first_docker_project
   

2. Запустите Docker Compose:
    

    ```docker-compose up --build```
   

3. Сервер PostgreSQL будет доступен на порту `5432`.



### Примечание
Для подключения к базе данных используйте следующие параметры:
- **Host**: `127.0.0.1`
- **Port**: `5432`
- **User**: `admin`
- **Password**: `root`
- **Database**: `db_auth`

### Выход
Ctrl + C в терминале или ```docker-compose down```
