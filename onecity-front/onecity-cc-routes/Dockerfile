FROM local.harbor.com/library/nginx:latest
COPY nginx.conf /etc/nginx/nginx.conf
COPY dist /usr/share/nginx/html/onecity-cc-routes
RUN chmod -R 777 /usr/share/nginx/html
