FROM publiocavalcante/php81

#ARG uid=1000
#ARG gid=1000

COPY start /usr/local/bin/start
RUN #chmod u+x /usr/local/bin/start
RUN chmod a+x /usr/local/bin/start

# Switch to user
USER ${uid}:${gid}

# Building process
#COPY html/ /var/www/html/
#RUN composer install # --no-dev
#RUN chown -R www-data:www-data /var/www/html/
#RUN chmod -R 777 /var/www/html/storage/logs
#RUN chmod -R 777 /var/www/html/storage/framework

CMD ["/usr/local/bin/start"]
