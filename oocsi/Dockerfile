FROM openjdk:11.0.11-jre-slim as mainstage
LABEL MAINTAINER="m.funk@tue.nl"
WORKDIR /opt/docker
COPY --chown=daemon:root 1/opt /opt
COPY --chown=daemon:root opt /opt
EXPOSE 9000 4444
USER daemon
RUN chmod +x /opt/docker/bin/oocsi-web
ENTRYPOINT ["/opt/docker/bin/oocsi-web"]
CMD []
