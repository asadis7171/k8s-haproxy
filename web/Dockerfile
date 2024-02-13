# Use the official Nginx image as the base
FROM nginx

# Copy the custom Nginx configuration file into the image
COPY ./web.nginx.cfg /etc/nginx/nginx.conf
COPY ./html /usr/share/nginx/html

#CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80
