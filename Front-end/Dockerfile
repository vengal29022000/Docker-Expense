FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY Code /usr/share/nginx/html/