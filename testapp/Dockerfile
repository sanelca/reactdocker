FROM node:14

WORKDIR /app

COPY package.json yarn.lock /app/

RUN yarn install

EXPOSE 3000

CMD bash