FROM node:18-alpine 

RUN mkdir /app

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run 

WORKDIR /app 

CMD ["npm" , "start"]