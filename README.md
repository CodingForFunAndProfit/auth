# auth

Authentication submodule of microservices

go mod init github.com/CodingForFunAndProfit/auth

go get github.com/spf13/viper
go get google.golang.org/grpc
go get gorm.io/gorm
go get gorm.io/driver/postgres
go get golang.org/x/crypto/bcrypt
go get github.com/golang-jwt/jwt

mkdir -p cmd pkg/config/envs pkg/db pkg/models pkg/pb pkg/services pkg/utils
touch Makefile cmd/main.go pkg/config/envs/dev.env pkg/config/config.go pkg/pb/auth.proto pkg/db/db.go pkg/models/auth.go pkg/services/auth.go pkg/utils/hash.go pkg/utils/jwt.go
