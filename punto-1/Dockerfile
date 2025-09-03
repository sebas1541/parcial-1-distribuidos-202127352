FROM alpine:3.20
WORKDIR /app
RUN apk update && apk add curl
COPY file.txt .
CMD ["cat", "file.txt"]