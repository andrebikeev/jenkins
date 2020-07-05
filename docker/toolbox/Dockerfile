FROM alpine
RUN apk add --no-cache curl wget bash && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
