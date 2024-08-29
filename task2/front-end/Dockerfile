# Use the official Nginx image
FROM nginx:latest

# Copy front-end files into Nginx's default location
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy custom Nginx configuration
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

