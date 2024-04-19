FROM node:alpine
WORKDIR /app
COPY package* /app
RUN npm i
COPY index.js /app
CMD ["node", "index.js"]