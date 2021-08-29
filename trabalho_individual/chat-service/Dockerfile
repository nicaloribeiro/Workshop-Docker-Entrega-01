FROM node:14

WORKDIR /chat-service

COPY package.json /chat-service/

COPY yarn.lock /chat-service/

RUN yarn

COPY . /chat-service/

EXPOSE 7100

CMD ["yarn", "watch"]