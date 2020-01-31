# docker-compose-apache-php
docker-composeでapacheを立ち上げた

# 使い方
### 開始時
pullしたディレクトリに移動して<br>
`~$ docker-compose up -d`
### 終了時
pullしたディレクトリに移動して<br>
`~$ docker-compose down`

# 説明
docker-composeを利用してapacheを立ち上げました。<br>
立ち上げたコンテナはwebサーバとdbサーバです。<br>
webはDockerfileをビルドしており、dbはimageから取ってきました。
