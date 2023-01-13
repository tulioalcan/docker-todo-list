FROM node:14
LABEL maintainer="Túlio Mendes"
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY ./ ./
ENTRYPOINT [ "npm", "start" ]