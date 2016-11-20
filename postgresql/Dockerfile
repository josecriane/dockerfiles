FROM postgres:alpine
MAINTAINER josecriane@gmail.com

RUN apk update
RUN apk upgrade

RUN apk add tzdata

ENTRYPOINT ["/docker-entrypoint.sh"]

EXPOSE 5432
CMD ["postgres"]