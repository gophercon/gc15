FROM ubuntu:trusty
MAINTAINER Feng Honglin <hfeng@tutum.co>

RUN apt-get update && \
	apt-get install --no-install-recommends -y -q curl build-essential ca-certificates git mercurial bzr && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

RUN mkdir /goroot && curl https://storage.googleapis.com/golang/go1.4.2.linux-amd64.tar.gz | tar xvzf - -C /goroot --strip-components=1
RUN mkdir /gopath

ENV GOROOT /goroot
ENV GOPATH /gopath
ENV PATH $PATH:$GOROOT/bin:$GOPATH/bin

RUN go get -u -v github.com/spf13/hugo
RUN go install github.com/spf13/hugo
RUN go get -v -u github.com/mholt/caddy
RUN go install github.com/mholt/caddy

RUN which caddy

ADD . /site-source

WORKDIR /site-source
EXPOSE 2015

CMD ["caddy"]

