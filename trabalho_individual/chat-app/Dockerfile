FROM node:14

WORKDIR /chat-app

COPY package.json /chat-app/

COPY yarn.lock /chat-app/

RUN yarn

COPY . /chat-app/

EXPOSE 7001

CMD ["yarn", "watch"]