FROM httpd:2.4

RUN apt update && apt -y install \
    git \
 && apt clean \
 && rm -rf /var/lib/apt/lists/*

COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf
