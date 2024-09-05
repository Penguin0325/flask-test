# Dockerコンテナ起動
`docker-compose build`
`docker-compose up`

`docker-compose up -d`
でも可
buildなしでcompose upだけでも多分動く

# flask操作
`docker exec -it flask-test-app-1 /bin/bash`
<!-- bashに入る -->

`flask run`
<!-- flask起動 -->

http://localhost:8000/
<!-- ここにアクセスすると表示される -->