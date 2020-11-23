FROM local.harbor.com/library/nginx:latest
COPY nginx.conf /etc/nginx/nginx.conf
COPY dist /usr/share/nginx/html/onecity-bc-portal
RUN chmod -R 777 /usr/share/nginx/html
