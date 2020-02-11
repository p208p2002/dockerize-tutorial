# Dockerize tutorial
[使用Docker包裝你的應用](https://blog.thecodingday.com/2020/02/%e4%bd%bf%e7%94%a8docker%e5%8c%85%e8%a3%9d%e4%bd%a0%e7%9a%84%e6%87%89%e7%94%a8-python-flask/)

## Usage
```
docker build -t=flask-env . # 建立映像檔
docker run -itd -p 5000:5000 --name='flask-app' flask-env # 建立服務容器
```