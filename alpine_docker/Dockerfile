FROM alpine:3.12
MAINTAINER Iovets Mykola
RUN apk update && apk add git && mkdir data && cd data
ENTRYPOINT ["git", "clone"]
CMD ["https://github.com/IovetsNikolay/jmeter"]