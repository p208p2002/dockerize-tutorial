# dockerize-tutorial
```
docker build -t=flask-env . # build imgae
docker run -itd -p 5000:5000 --name='flask-app' flask-env # start app
```