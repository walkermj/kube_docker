# specify base image
FROM node:alpine

WORKDIR /usr/app 

# install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# set up default commmand
CMD ["npm", "start"]
