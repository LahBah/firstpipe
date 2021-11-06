FROM ubuntu
RUN apt update && apt install -y nginx
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
RUN echo "Hello world" > file.txt
CMD nginx 

#test