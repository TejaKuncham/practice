FROM nginx
COPY code /usr/share/nginx/html 
RUN rm -f /etc/nginx/nginx.conf \
    rm -f /etc/nginx/conf.d/default.conf 
COPY nginx.conf /etc/nginx/nginx.conf 
#COPY nginx.conf /etc/nginx/conf.d/default.conf