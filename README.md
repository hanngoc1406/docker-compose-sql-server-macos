1. Run docker
```
docker-compose up
```

2. Tạo connect bằng Azure Data Studio với thông tin:
```
Server: 127.0.0.1, 1433
User nam: SA
Password: SA_PASSWORD (trong file docker-compose)
Trust server certificate: True
```