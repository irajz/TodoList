# base image
FROM node:20.13.1

RUN npm install -g nodemon

# working directory
WORKDIR /app

# copy the files
COPY . .

RUN npm install

EXPOSE 3001

CMD [ "npm" , "start"]