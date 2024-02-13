FROM ubuntu
RUN /bin/bash -c "touch nick > /tmp/nick"
WORKDIR /tmp
CMD echo "nicky is checking docker file"
COPY file1 /tmp
ADD new.tar.gz /tmp
VOLUME ["/volume"]
