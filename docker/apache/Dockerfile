FROM httpd:2.4.51

COPY my.apache.conf /usr/local/apache2/conf/my.apache.conf

RUN echo "Include /usr/local/apache2/conf/my.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf