FROM postgres:15-alpine
ENV POSTGRES_DB=axion
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres
COPY *.sql /docker-entrypoint-initdb.d/
EXPOSE 5432
