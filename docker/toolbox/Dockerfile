FROM node
RUN mkdir /tetris
WORKDIR /tetris
COPY . /tetris

RUN yarn install
RUN yarn build

CMD yarn start

EXPOSE 3000
