FROM alpine:3.19 AS builder

RUN apk --update --no-cache add \
  curl \
  iputils \
  busybox-extras \
  wget \
  net-tools \
  bind-tools \
  postgresql-client \
  mariadb-client \
  aws-cli

FROM alpine:3.19

COPY --from=builder /usr/bin/* /usr/bin/
