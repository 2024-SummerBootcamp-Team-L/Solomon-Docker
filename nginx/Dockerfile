FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.d

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]