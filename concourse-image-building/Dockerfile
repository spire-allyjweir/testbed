FROM alpine

RUN apk add curl

RUN curl -o google-homepage.html https://google.com

COPY ./test_script.sh ./

ENTRYPOINT ["/bin/ash"]
