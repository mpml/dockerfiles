# R
# https://cran.r-project.org/
# v3.4.3

# base image: r-base:3.4.3
FROM r-base:3.4.3

# File Author / Maintainer
MAINTAINER Frederic Lemoine <frederic.lemoine@pasteur.fr>

RUN apt-get update && apt-get install -y procps && \
    mkdir /pasteur

ENTRYPOINT ["/usr/bin/R"]
