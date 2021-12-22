FROM node:12

WORKDIR /core

COPY  entrypoint.sh /

RUN apt-get update && \
    apt-get -y install --no-install-recommends \
    build-essential \
    jq \
    iptables \
    python \
    vim && \
    rm -rf /var/lib/apt/lists/*

EXPOSE 6001 6002 6003 6012 6022 4040
