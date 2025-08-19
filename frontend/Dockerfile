FROM nginx 
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -f /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY code /usr/share/nginx/html/
#COPY code /usr/share/nginx/html/