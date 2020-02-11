# Dockerize tutorial
[使用Docker包裝你的應用](http://jumper.thecodingday.com/?goto=aHR0cHM6Ly9ibG9nLnRoZWNvZGluZ2RheS5jb20vMjAyMC8wMi8lZTQlYmQlYmYlZTclOTQlYThkb2NrZXIlZTUlOGMlODUlZTglYTMlOWQlZTQlYmQlYTAlZTclOWElODQlZTYlODclODklZTclOTQlYTgtcHl0aG9uLWZsYXNrLw)

## Usage
```
docker build -t=flask-env . # 建立映像檔
docker run -itd -p 5000:5000 --name='flask-app' flask-env # 建立服務容器
```