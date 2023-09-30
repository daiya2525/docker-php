# docker-php
I built an environment with php8.1-apache, mysql8.0, and phpmyadmin using docker.

## ディレクトリ・ファイル構造について
docker-php/
├── docker-compose.yml
├── mysql/
├── php/
│   └── (PHP関連の設定ファイル「php.ini」や「Dockerfile」など)
└── html/
    └── (PHPアプリケーションのファイル「index.php」など)

## Docker起動方法
ターミナルから、docker-phpフォルダに移動
```bash
$ cd docker-php
```

下記コマンドで、コンテナ起動
```bash
$ docker-compose up -d
```

下記コマンドで、現在立ち上がっているコマンドの状態を確認することができる。
```bash
$ docker ps
```

## 動作確認
http://localhost:8080
