# ЭФМО-01-25 Буров М.А. ПР3

# Описание проекта
Данный проект предназначен для реализации простого HTTP-сервера на стандартной библиотеке net/http и обработки запросов GET/POST

# Требования к проекту
* Go 1.25+
* Git

# Версия Go
<img width="340" height="55" alt="image" src="https://github.com/user-attachments/assets/e7fec853-899d-442e-9d95-94d494a5cb46" />

# Сборка
Для сборки проекта необходимо выполнить команду из директории pz3-http:
```
go build -o .\bin\server.exe  .\cmd\server
```
# Запуск
Для запуска без компиляции выполняется команда из директории pz3-http:
```
go run ./cmd/server
```
<img width="446" height="66" alt="image" src="https://github.com/user-attachments/assets/889dd8a4-721e-4e4f-8b87-2ad47bdf9073" />

# Проверка работоспоcобности
Запрос GET /health

<img width="388" height="130" alt="image" src="https://github.com/user-attachments/assets/81a6d5e4-1372-4f6e-a7fa-5ca38ddfae62" />

Запрос GET /tasks

<img width="397" height="176" alt="image" src="https://github.com/user-attachments/assets/53a741ad-c385-4f82-a65c-8a4115088c79" />

Запрос POST /tasks

<img width="372" height="151" alt="image" src="https://github.com/user-attachments/assets/e51f95a6-dc2f-4077-bc7e-40bbd85da4f0" />

Запрос GET /tasks/{id}

<img width="390" height="171" alt="image" src="https://github.com/user-attachments/assets/7f495062-5c33-4f44-8fc2-89c726697d01" />

Коллекция Postman представлена в файле requests.md.

# Структура проекта
Дерево структуры проекта: 
```
pz3-http/
├── bin/
│   └── server.exe
├── cmd/
│   └── middleware/
│       ├── cors.go
│       └── logger.go
├── internal/
│   ├── api/
│   │   ├── handlers.go
│   │   ├── middleware.go
│   │   └── responses.go
│   └── storage/
│       └── memory.go
├── go.sum
└── main.go
```
