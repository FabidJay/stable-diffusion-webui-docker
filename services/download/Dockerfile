FROM bash:alpine3.15@sha256:463b668dccc38f32a5bb5a5d59a3e1b787be432eb69b853fe4ad49cdce9a37d5

RUN apk add parallel aria2
COPY . /docker
RUN chmod +x /docker/download.sh
ENTRYPOINT ["/docker/download.sh"]
