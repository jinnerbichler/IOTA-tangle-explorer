FROM node:9.3.0
MAINTAINER Johannes Innerbichler <j.innerbichler@gmail.com>

WORKDIR /tangle-explorer/
COPY . .

EXPOSE 8080

RUN npm install
ENTRYPOINT ["npm", "run", "dev"]
