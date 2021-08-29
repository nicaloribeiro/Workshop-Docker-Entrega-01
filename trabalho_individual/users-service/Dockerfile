FROM node:14

WORKDIR /users-services

COPY package.json /users-services/

COPY yarn.lock /users-services/

RUN yarn

COPY . /users-services/

EXPOSE 7101

CMD ["sh", "-c", "yarn db:migrate && yarn watch"]