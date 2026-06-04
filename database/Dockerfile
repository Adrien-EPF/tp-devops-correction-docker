FROM postgres:17.2-alpine

COPY sql docker-entrypoint-initdb.d

ENV POSTGRES_DB=db \
   POSTGRES_USER=usr
