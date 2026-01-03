FROM node:22-alpine

WORKDIR /app

COPY package*.json .

RUN npm install -g pnpm@latest-10

RUN pnpm config set registry https://registry.npmmirror.com

RUN pnpm install

COPY . .
