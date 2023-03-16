## LATEST version 
## Base Docker Image
FROM node:14.15.0-alpine3.12

## Set home folder that keep source code 
WORKDIR /usr/src/app/

## Copy source code to docker image
COPY src/ /usr/src/app/

## Dependency each language
RUN npm install

## config
EXPOSE 8080

## run command with foreground
CMD [ "node", "/usr/src/app/ratings.js", "8080" ]