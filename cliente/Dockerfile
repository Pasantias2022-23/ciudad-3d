FROM node:16.17.1-alpine3.15
WORKDIR /app
COPY . .
RUN corepack enable
RUN corepack prepare pnpm@latest --activate
RUN pnpm install
CMD ["pnpm","run","dev","--host"]