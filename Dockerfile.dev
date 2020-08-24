FROM strapi/strapi
WORKDIR "/app"
COPY ./package.json ./
COPY ./yarn.lock ./

RUN yarn install
COPY . .
EXPOSE 1337
CMD [ "yarn", "develop" ]