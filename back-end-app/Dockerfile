FROM node:18-alpine
LABEL org.opencontainers.image.source trp-ci-cd-app
WORKDIR /app
COPY dist .
EXPOSE 3000
CMD ["node", "dist/main.js"]

