FROM postgres:16-alpine

LABEL maintaner="Henrique Zani"

ARG TIMEZONE

RUN ln -snf /usr/share/zoneinfo/$TIMEZONE /etc/localtime && echo $TIMEZONE > /etc/timezone