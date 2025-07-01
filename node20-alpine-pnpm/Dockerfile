FROM node:20-alpine

RUN npm install --global corepack@latest
RUN corepack enable && corepack prepare pnpm@10.12.1 --activate
RUN pnpm config set store-dir .pnpm-store