# About the postgresql version, it should match in the dockerfile of docker-imposm3
FROM camptocamp/postgres:9.5

COPY create-extension-postgis.sql /docker-entrypoint-initdb.d/
