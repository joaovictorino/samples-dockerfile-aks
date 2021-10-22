FROM alpine

LABEL "Company" "João Ltda"
LABEL maintainer="João"

RUN apk update

RUN mkdir /teste

EXPOSE 5000

ARG PORT

ENV PORT_AULA=${PORT}

RUN echo ${PORT} >> /teste/teste.txt

COPY teste2.txt /teste/teste2.txt

VOLUME /volume1

WORKDIR /volume1