FROM hklement/ubuntu-exec
MAINTAINER Hauke Klement <dev@hklement.de>
RUN apt-get install -y g++ make wget
RUN wget -O /tmp/python.tgz https://www.python.org/ftp/python/3.4.3/Python-3.4.3.tgz
RUN mkdir /tmp/python
RUN tar xfz /tmp/python.tgz -C /tmp/python --strip-components=1
RUN cd /tmp/python && ./configure && make && sudo make install
