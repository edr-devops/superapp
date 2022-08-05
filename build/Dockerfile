FROM alpine

RUN apk upgrade
RUN apk add curl  
RUN echo "hello!"
ENV my_super_var "is super"
COPY script/my-superscript.sh /script/my-superscript.sh
RUN chmod +x /script/my-superscript.sh
ENTRYPOINT /script/my-superscript.sh

