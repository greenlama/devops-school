FROM alpine:3.12

ENV sample-text

COPY homework.sh /homework.sh

RUN chmod +x /homework.sh

VOLUME ["/tmp"]
ENTRYPOINT ["/homework.sh"]
