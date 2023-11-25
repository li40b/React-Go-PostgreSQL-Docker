FROM golang:1.19.2-alpine
ENV GO111MODULE on

RUN apk update && \
    apk --no-cache add git && \
    apk add bash

RUN mkdir /backend
WORKDIR /backend

CMD ["go", "run", "main.go"]
