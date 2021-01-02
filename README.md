# docker-slim
docker学習中。実際にPHPフレームワークであるslimの開発環境を構築してみる
※DBコンテナも作成しているが、接続までは行っていない。

## Usage

```bash
$ git clone git@github.com:seki19/docker-slim.git
$ cd docker-slim
$ docker-compose build
$ docker-compose up -d
$ docker-compose exec web composer create-project slim/slim-skeleton slim
```

コマンド実行後、localhostにアクセスし、Hello world!が表示されることを確認。
