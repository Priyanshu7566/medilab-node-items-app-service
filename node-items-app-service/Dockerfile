FROM node:latest
RUN mkdir /opt/items-app-service1
WORKDIR /opt/items-app-service1
COPY . $WORKDIR
RUN npm install
CMD ["npm","start"]
