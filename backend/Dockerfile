FROM node

WORKDIR /app

COPY package.json .

RUN yarn

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=haris
ENV MONGODB_PASSWORD=secret

CMD [ "yarn", "start" ]
