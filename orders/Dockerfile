FROM node:18

WORKDIR /usr/src/app

COPY . .
RUN npm install
RUN npm run build

EXPOSE 3100
CMD ["npm", "run", "start:prod"]