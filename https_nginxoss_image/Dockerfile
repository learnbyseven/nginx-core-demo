FROM nginx 
COPY ssl_nginx.conf /etc/nginx/conf.d/ssl_nginx.conf
COPY my* /etc/nginx/certs/
EXPOSE 80 443
CMD	/usr/sbin/nginx  -g "daemon off;"
