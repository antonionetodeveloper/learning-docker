FROM golang:1.22rc1-alpine3.18
WORKDIR /app-go
EXPOSE 8080
COPY . .
RUN go mod tidy
ENTRYPOINT go run src/main.go