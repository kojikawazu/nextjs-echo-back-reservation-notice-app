# Goコマンド一覧

## モジュールインストール一覧

```bash
go get github.com/labstack/echo/v4
go get github.com/labstack/echo/v4/middleware
go get github.com/joho/godotenv
go get github.com/spf13/viper
go get github.com/jackc/pgx/v4/pgxpool
go get github.com/redis/go-redis/v9

go get github.com/gorilla/websocket
go get github.com/dgrijalva/jwt-go

go get github.com/stretchr/testify/assert
```

## モジュールの整理

```bash
go mod tidy
```

## サーバーの起動

```bash
go run main.go
```

## テストコードの実行

```bash
JWT_SECRET_KEY=xxxxxx go test -count=1 ./...
```