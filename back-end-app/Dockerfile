FROM node:18-alpine
LABEL org.opencontainers.image.source trp-ci-cd-app
WORKDIR /app
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "src/main.js"]
