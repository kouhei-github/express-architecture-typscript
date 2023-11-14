FROM node:20
WORKDIR /app
COPY ./express /app
COPY ./express/package*.json /app
RUN npm install
EXPOSE 3000
#CMD [ "npm", "run", "start" ]
