## grpc сервер + http gateway для rusprofile
___
### Запуск

```bigquery
make prepare
make start
```

### Проверка
#### http
```bigquery
make http-curl-test
```
#### grpc
```bigquery
go run cmd/grpcclient/main.go
```
