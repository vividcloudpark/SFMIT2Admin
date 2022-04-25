#FROM mysql:5.7
FROM 495988863529.dkr.ecr.ap-northeast-2.amazonaws.com/mysql:5.7

ADD ./mysql-init-files /docker-entrypoint-initdb.d
## docker의 db구조에서 약속된 형태로 여기에 넣은 sql이나 sh는 시작하자마자 구동한다.

EXPOSE 3306

CMD ["mysqld"]

