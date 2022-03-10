# mysql-phpmyadmin-quickstart

MySQL と phpMyAdmin をすぐ使うための設定ファイル

```bash
# 起動
docker-compose up -d
# 終了
docker-compose stop
```

## phpMyAdmin

1. 3000 番ポートにアクセス

```bash
http://localhost:3000
```

2. ログイン

- サーバ
  - `mysqldb`
- ユーザー名
  - `root`
- パスワード
  - `root`

## MySQL

```bash
docker exec -it mysql8_container mysql -u root -p
```

## 参考

- https://blog.hiros-dot.net/?p=10477
