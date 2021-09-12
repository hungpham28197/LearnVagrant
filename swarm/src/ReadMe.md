docker build . -t iam:latest
docker run -d --name iam -p 8001:8001 iam:latest


docker image tag iam:latest manager02:5000/iam:latest
docker image push manager02:5000/iam:latest

Hiện đang gặp lỗi vì chưa hỗ trợ https
```
The push refers to repository [manager02:5000/iam]
Get https://manager02:5000/v2/: http: server gave HTTP response to HTTPS client
```