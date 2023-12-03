# Dockerfile

# MySQL 이미지를 기반으로 이미지 생성
FROM mysql:latest

# MySQL 설정
ENV MYSQL_ROOT_PASSWORD=1111
ENV MYSQL_DATABASE=DockerTest
ENV MYSQL_USER=luca
ENV MYSQL_PASSWORD=1111


# sql구문
COPY ./Scripts/ /docker-entrypoint-initdb.d/