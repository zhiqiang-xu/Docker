- docker build -t go-http-hello-world:0.3 -f Dockerfile-MultiStage .
- docker run -d -p 12345:8080 go-http-hello-world:0.3
- curl http://localhost:12345
- docker login
- docker tag go-http-hello-world:0.3 zhiqiang6677/go-web:0.3
- docker push zhiqiang6677/go-web:0.3

