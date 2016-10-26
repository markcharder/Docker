FROM ubuntu:14.04
MAINTAINER Mark Derbyshire <mark.derbyshire@curtin.edu.au>

RUN mkdir /opt/bwa
WORKDIR /opt/bwa
ADD http://downloads.sourceforge.net/project/bio-bwa/bwakit/bwakit-0.7.12_x64-linux.tar.bz2?r=https%3A%2F%2Fsourceforge.net%2Fprojects%2Fbio-bwa%2F&ts=1477377649&use_mirror=internode /opt/bwa
RUN tar xvjf bwakit-0.7.12_x64-linux.tar.bz2 && rm *.bz2
ENV PATH /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/opt/bwa/bwa.kit
