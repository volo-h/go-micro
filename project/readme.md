  export GO111MODULE=on
  go mod tidy

front-end
  go run ./cmd/web/main.go

broker-service
  docker-compose up -d  // generate build
  docker-compose up     // start build

make up_build

make stop
make down
