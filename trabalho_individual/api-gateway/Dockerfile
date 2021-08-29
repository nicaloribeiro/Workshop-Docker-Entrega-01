FROM node:14

WORKDIR /api-gateway

COPY package.json /api-gateway/

COPY yarn.lock /api-gateway/

RUN yarn

COPY . /api-gateway/

EXPOSE 7000

CMD ["yarn", "watch"]