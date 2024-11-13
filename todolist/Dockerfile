FROM node:20.13.1

WORKDIR /app

COPY package.json .

RUN npm cache clean --force && npm install && npm install @rollup/rollup-linux-x64-gnu

COPY . .

EXPOSE 5173

CMD [ "npm" , "run" , "dev" ]