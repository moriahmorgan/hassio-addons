FROM homeassistant/aarch64-base:3.10

# Setup base
RUN apk add nginx openssl

# Copy data
COPY data/run.sh /
COPY data/nginx.conf /etc/

CMD [ "/run.sh" ]
