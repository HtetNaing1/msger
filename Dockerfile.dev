FROM node:18.16.0-alpine3.16

WORKDIR /msger

COPY package.json ./

RUN npm install

COPY postcss.config.js ./postcss.config.js

COPY next.config.js ./next.config.js

COPY tailwind.config.js ./tailwind.config.js

COPY tsconfig.json ./tsconfig.json

EXPOSE 3000

CMD [ "npm", "run", "dev" ]