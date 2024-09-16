Перед началом убедитесь, что у вас установлены:

- [Docker](https://www.docker.com/)
- [Git](https://git-scm.com/)

1. Собираем Dockerfile "sudo docker build -t tender_service ."
2. Запускаем Dockerfile с портами 8080 "sudo docker run -p 8080:8080 tender_service"
3. Проверяем "http://localhost:8080/ping" или "curl -i http://localhost:8080/ping"

Должен вывести:

HTTP/1.1 200 OK
Content-Type: text/plain; charset=utf-8
Date: Mon, 16 Sep 2024 09:08:03 GMT    
Content-Length: 2