# MariaDBの構築
```bash
docker compose up -d 
docker compose exec db -u testuser -D testdb -p
```

## 環境変数
|環境変数名|設定した変数|
|--------|----------|
|MARIADB_ROOT_PASSWORD|rootpass|
|MARIADB_DATABASE|testdb|
|MARIADB_USER|testuser|
|MARIADB_PASSWORD|testpass|