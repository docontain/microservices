FROM postgres:13

ENV POSTGRES_DB users_db
ENV POSTGRES_USER postgres
ENV POSTGRES_PASSWORD password

COPY init.sql /docker-entrypoint-initdb.d/