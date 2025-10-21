# ЭФМО-01-25 Буров М.А. ПР3

# Описание проекта
Данный проект предназначен для реализации простого HTTP-сервера на стандартной библиотеке net/http и обработки запросов GET/POST

# Требования к проекту
* Go 1.25+
* Git

# Версия Go
<img width="277" height="47" alt="image" src="https://github.com/user-attachments/assets/884936a9-b6aa-4b53-9b9c-88b324b9685d" />

# Сборка
Для сборки проекта необходимо выполнить команду из директории myapp:
```
go build -o executableFileName.exe ./cmd/myapp/main.go
```
# Запуск
Для запуска без компиляции выполняется команда из директории myapp:
```
go run ./cmd/myapp
```
<img width="695" height="197" alt="image" src="https://github.com/user-attachments/assets/badbe418-c798-4f26-b327-0792ea8e60d0" />

# Проверка работоспоcобности
Для проверки работоспособности необходимо обратиться к разворачиваему API с помощью:
```
curl -i http://localhost:8080/ping
```
При обращению результат должен быть такой:

<img width="639" height="186" alt="image" src="https://github.com/user-attachments/assets/a33e8b1f-8f1c-4302-8c87-05728b5d1ffc" />

# Структура проекта
Дерево структуры проекта: 

<img width="262" height="257" alt="image" src="https://github.com/user-attachments/assets/ea1ba31e-9685-4f3b-b625-8c96d3f299ec" />
