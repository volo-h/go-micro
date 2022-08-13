  export GO111MODULE=on
  go mod tidy

front-end
  go run ./cmd/web/main.go

broker-service
  docker-compose up -d  // generate build
  docker-compose up     // start build

make up_build
make up
  make down

make stop

# start front-end
make start

# A simple example of how to create a reusable Go module with commonly used tools.
  https://github.com/tsawler/toolbox

https://www.mongodb.com/try/download/compass


mongodb://admin:password@localhost:27017/logs?authSource=admin&readPreference=primary&appname=MongoDB%20Compass&directConnection=true&ssl=false

# mailhog web ui
http://localhost:8025/

https://hub.docker.com/_/rabbitmq
