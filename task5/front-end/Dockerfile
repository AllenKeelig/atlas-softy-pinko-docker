# Use the latest version of Nginx
FROM nginx:latest

# Copy the softy-pinko-front-end files to the appropriate directory
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the Nginx configuration file to the appropriate location
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

# Expose port 9000 to be able to access the web server
EXPOSE 9000
