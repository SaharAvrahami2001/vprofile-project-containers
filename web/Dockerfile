FROM nginx
RUN rm -rf /etc/nginx/conf.d/default.conf
ADD nginvproapp.conf /etc/nginx/conf.d
RUN systemctl restart nginx 
