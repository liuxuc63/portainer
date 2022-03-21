FROM portainer/base

COPY dist /
COPY metadata.json /
COPY docker-extension/build/ /docker-extension

VOLUME /data
WORKDIR /

EXPOSE 9000
EXPOSE 9443
EXPOSE 8000

ENTRYPOINT ["/portainer"]
