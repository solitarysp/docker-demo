FROM nginx:latest

# Change Nginx config here...
RUN rm /etc/nginx/conf.d/default.conf
COPY ./default.conf /etc/nginx/conf.d/
COPY ./default.conf /etc/nginx/sites-enabled/default
