# Poderia ter outros nomes como: node.dockerfile, se vc tivesse vários Dockerfiles
FROM node:14
LABEL maintainer="Luciano Cordeiro-lacsousa@gmail.com"
WORKDIR /app-node
ARG PORT=6000
ENV PORT=$PORT
EXPOSE $PORT
COPY . .
RUN npm install
ENTRYPOINT npm start
