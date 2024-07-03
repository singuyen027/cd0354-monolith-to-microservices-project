## Build
FROM beevelop/ionic:v2021.06.1 AS ionic
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
COPY package*.json ./
RUN npm i ci
# Bundle app source

EXPOSE 8080
CMD [ "npm", "run", "prod" ]