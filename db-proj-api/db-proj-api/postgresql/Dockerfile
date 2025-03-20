
FROM library/postgres


ENV POSTGRES_USER scott
ENV POSTGRES_PASSWORD tiger
ENV POSTGRES_DB dbproj

COPY dbproj.sql /docker-entrypoint-initdb.d/

EXPOSE 5432
