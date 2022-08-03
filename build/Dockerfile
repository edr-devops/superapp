FROM alpine

RUN apk upgrade
RUN echo "hello!"

COPY script/my-superscript.sh /script/my-superscript.sh
RUN chmod +x /script/my-superscript.sh
ENTRYPOINT /bin/sh -c "sleep infinity"

