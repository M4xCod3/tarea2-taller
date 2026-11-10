FROM debian:12-slim

RUN apt-get update && \
    apt-get install -y --no-install-recommends lftp tcpdump iproute2 iputils-ping && \
    rm -rf /var/lib/apt/lists/*

CMD ["sleep", "infinity"]

