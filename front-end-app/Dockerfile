FROM nginx:alpine
LABEL org.opencontainers.image.source trp-ci-cd-app
COPY dist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
