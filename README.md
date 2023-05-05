# code-server

Docker Compose 를 활용하여 Code Server HTTPs 구성하기
Blog : [Docker로 CodeServer 구축 및 인증서 설정하기](https://medium.com/@jbhunbb/docker로-codeserver-구축-및-인증서-설정하기-240712e18550) 

## 디렉터리 구조
    ├── docker-compose.yml
    └── volume
        ├── code-server
        │   └── config
        └── nginx
            ├── certs
            └── config

## 실행 방법
    docker-compose up -d
