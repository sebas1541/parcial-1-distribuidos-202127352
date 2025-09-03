FROM alpine:3.20
WORKDIR /app
RUN apt-get update && apt-get install -y curl
COPY file.txt .
EXPOSE 3000
CMD ["cat", "file.txt"]