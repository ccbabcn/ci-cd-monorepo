FROM node:18-alpine
LABEL rg.opencontainers.image.source="https://github.com/ccbabcn/ci-cd-monorepo"

WORKDIR /usr/app-back
COPY . .

RUN npm install
RUN npm run build

CMD [ "npm", "run", "start:dev" ]
