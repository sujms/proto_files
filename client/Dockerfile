FROM golang:1.18.1
RUN mkdir /app
ADD . /app
WORKDIR /app
RUN go build -o client .
CMD ["/app/client"]