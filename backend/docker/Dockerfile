FROM golang:1.21.4-alpine3.18
ENV GO111MODULE on

RUN apk update && \
    apk --no-cache add git && \
    apk add bash

RUN mkdir /backend
WORKDIR /backend

# CMD ["go", "run", "main.go"]