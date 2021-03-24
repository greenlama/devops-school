FROM alpine:3.12

COPY homework.sh /homework.sh

RUN chmod +x /homework.sh

VOLUME ["/tmp"]
ENTRYPOINT ["/homework.sh"]
