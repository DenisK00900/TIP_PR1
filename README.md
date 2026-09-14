# Практическое занятие №1 
по дисциплине «Технологии индустриального программирования».

# Требования
- Go 1.22 или выше
- Git

# Структура проекта
```text
helloapi/
├── cmd/
│   └── server/
│       └── main.go
├── .gitignore
├── go.mod
├── go.sum
└── README.md
```

# Скачивание и запуск
```text
git clone https://github.com/DenisK00900/TIP_PR1.git
cd TIP_PR1
go mod tidy
go run ./cmd/server
```

# Запросы
```text
curl http://localhost:5015/hello
curl http://localhost:5015/user
curl http://localhost:5015/health
```
(или другой порт, если он был изменён)

# Конфигурация
```text
set APP_PORT=5015
```
