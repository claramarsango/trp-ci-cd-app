FROM node:18-alpine
LABEL org.opencontainers.image.source trp-ci-cd-app
WORKDIR /app
COPY package.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["node", "dist/main.js"]
