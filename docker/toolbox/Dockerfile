FROM node
RUN mkdir /lab
WORKDIR /lab
COPY . /lab

RUN yarn install
RUN yarn build

CMD yarn start

EXPOSE 3000
