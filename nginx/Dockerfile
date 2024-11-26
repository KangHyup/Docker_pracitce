FROM nginx:1.27.2-alpine
COPY ./nginx_practice.conf /etc/nginx/conf.d/nginx_practice.conf
RUN rm -f /etc.nginx/conf.d/default.conf

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]