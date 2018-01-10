FROM debian:wheezy

MAINTAINER Aki Gotoh <agotoh@efficient.co.jp>
RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]