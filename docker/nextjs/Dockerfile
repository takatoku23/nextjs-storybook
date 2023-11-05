
# ローカルで動作させる build stage
FROM node:18.17-slim as dev
ENV NODE_ENV=development
WORKDIR /app

COPY ./app/package*.json ./app/yarn.lock ./
RUN yarn install

CMD ["yarn", "run", "dev"]
