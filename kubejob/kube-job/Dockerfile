FROM python:3.7-alpine

USER root

COPY job.py /job.py

COPY docker-entrypoint.sh /docker-entrypoint.sh

RUN chmod +x /docker-entrypoint.sh

ENTRYPOINT ./docker-entrypoint.sh
