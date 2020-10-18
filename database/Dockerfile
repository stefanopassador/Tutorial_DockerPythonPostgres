FROM postgres:latest
ENV POSTGRES_PASSWORD=secret
ENV POSTGRES_USER=username
ENV POSTGRES_DB=database
ADD create_fixtures.sql /docker-entrypoint-initdb.d/
