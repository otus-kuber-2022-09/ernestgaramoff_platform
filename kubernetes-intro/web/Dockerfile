FROM nginx:1.22
RUN mkdir /app/
WORKDIR /app
COPY index.html /app/ 
COPY  nginx.conf /etc/nginx/nginx.conf
RUN usermod -u 1001 nginx
RUN chown -R  nginx:nginx /app
