# Use Golang 1.16 image
FROM golang:1.16

# Set the working directory inside the container
WORKDIR /usr/src/myapp

COPY . .

RUN go build

RUN go test ./...

CMD ["./server"]
