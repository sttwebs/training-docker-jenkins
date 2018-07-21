FROM nginx:latest

#-Add allows for Links and unzips ZIPs files
ADD webapp.html /www/
#-COPY is a simple compy
#COPY
ADD nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80
EXPOSE 443

CMD nginx -g "daemon off;"