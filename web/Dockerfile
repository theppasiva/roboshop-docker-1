FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/

# FROM nginx 
# RUN rm -f /usr/share/nginx/html/index.html
# COPY roboshop.conf /etc/nginx/default.droboshop.conf
# ADD static /usr/share/nginx/html/
