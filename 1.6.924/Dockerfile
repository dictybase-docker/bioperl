FROM perl:5.20
MAINTAINER Siddhartha Basu <siddhartha-basu@northwestern.edu>

RUN apt-get update && \
    apt-get -y install  libdb-dev libexpat1-dev 

RUN cpanm -n DBD::Pg Bio::Seq 
