FROM ashwanthkumar/gocd-agent-jdk:16.2.1
MAINTAINER Ashwanth Kumar

RUN apk --update add python py-pip  \
    && pip install awscli \
    && pip install s3cmd  \
    && pip install s4cmd
    && rm -rf /var/cache/apk/* /tmp/*
