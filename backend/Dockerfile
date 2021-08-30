FROM node:14.17.3
LABEL email = "brownhare0221@gmail.com"
LABEL name = "Jaeho Cha"
LABEL version = "0.0.0"

RUN mkdir -p /app

WORKDIR /app
ADD ./ /app/

RUN npm install

ENV NODE_ENV=production

CMD node index.js