FROM ubuntu:18.04
RUN apt-get update && apt-get install -y nodejs npm
RUN npm install -g http-server
WORKDIR /usr/app
COPY . .
EXPOSE 8000
CMD ["http-server", "-p", "8000"]
