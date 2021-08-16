FROM node:16.5.0
RUN yarn global add expo-cli
WORKDIR /app
COPY package.json ./
RUN yarn install
COPY . .
CMD [ "yarn", "run", "start" ]
