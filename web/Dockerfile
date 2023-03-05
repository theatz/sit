FROM python:3.8.10

ENV TZ="Europe/Moscow"

ARG APP_DIR=/source
ARG PY_VERSION=3.10

RUN mkdir ${APP_DIR}
WORKDIR ${APP_DIR}
ADD . ${APP_DIR}

RUN pip3 install -r web/requirements.txt