FROM publiocavalcante/php82

ARG UID=1000
ARG GID=1000

USER root:root
COPY start /usr/local/bin/start
RUN chmod a+x /usr/local/bin/start

# Switch to user
USER "${UID}":"${GID}"

CMD ["/usr/local/bin/start"]

