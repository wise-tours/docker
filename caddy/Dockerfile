FROM abiosoft/caddy

RUN apk update
RUN apk add mc

WORKDIR /etc

COPY . .

RUN touch Caddyfile
