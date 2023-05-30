FROM nginx
RUN rm -rf /usr/share/nginx/html/
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/defaul.conf
COPY defaul.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html