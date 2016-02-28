FROM ashwanthkumar/gocd-agent:latest
MAINTAINER Ashwanth Kumar

RUN apt-get update \
    && apt-get install -y \
        jq \
        libxml2-utils \
        python-openssl \
        python-pip  \
        python2.7 \
        xmlstarlet \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* \
    && pip install awscli \
    && pip install s3cmd  \
    && pip install s4cmd
