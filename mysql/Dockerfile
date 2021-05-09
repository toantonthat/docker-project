FROM mysql:5.7
RUN chown -R mysql:root /var/lib/mysql/

RUN apt-get update && apt-get install -y wget && apt-get install -y vim

COPY conf/my.cnf /etc/mysql/my.cnf

EXPOSE 3306
