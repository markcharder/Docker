FROM markderbyshire/bwa
MAINTAINER Mark Derbyshire <mark.derbyshire@curtin.edu.au>

RUN mkdir /opt/stampy
WORKDIR /opt/stampy
ADD http://www.well.ox.ac.uk/bioinformatics/Software/Stampy-latest.tgz
RUN tar xvzf Stampy-latest.tgz && rm *.tgz && cd Stampy* && make
ENV PATH /opt/stampy/Stampy*/:$PATH
