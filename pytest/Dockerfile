FROM python:3.8.0-alpine3.10

RUN apk update \
    && apk upgrade

RUN apk add git \
    	alpine-sdk \
	libffi-dev \
	openssl-dev

RUN pip install pytest-cov

ENTRYPOINT ["sh"]
