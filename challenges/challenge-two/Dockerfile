FROM fedora

RUN dnf -y install httpd

ADD website.tar.gz /var/www/html/

EXPOSE 80

CMD [ "-D", "FOREGROUND" ]

ENTRYPOINT [ "/usr/sbin/httpd" ]
