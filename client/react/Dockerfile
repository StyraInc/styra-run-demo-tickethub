FROM node:21-alpine

ADD ./docker_entrypoint.sh /bin/entrypoint.sh
RUN chmod +x /bin/entrypoint.sh && mkdir -p /src/tickethub-ui-react

EXPOSE 3000
CMD ["/bin/sh", "/bin/entrypoint.sh"]
