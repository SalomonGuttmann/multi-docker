#FROM node:14.14.0-alpine
FROM node:24-alpine.21
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]