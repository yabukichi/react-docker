# react/Next用dockerサンプル

react/Nextの環境をdockerで用意しました。

## 初回構築
```
git clone https://github.com/yabukichi/react-docker.git
cd react-docker
docker-compose build
docker-compose up
```

## 運用中に使いそうなコマンド

docker起動
```
docker-compose up
```

dockerイメージを裏側で起動する。（デーモンで起動）
```
docker-compose up -d
```

dockerイメージを停止・削除する。
```
docker-compose down
```

dockerイメージを削除せずに停止する。
```
docker-compose stop
```

dockerイメージを再起動。停止（stop）した時に使う。
```
docker-compose start
```
