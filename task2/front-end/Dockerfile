# Install Nginx instead of Ubuntu
FROM nginx:latest

# Copying the softy-pinko-front-end to the Docker image
ADD softy-pinko-front-end /var/www/html/softy-pinko-front-end
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf