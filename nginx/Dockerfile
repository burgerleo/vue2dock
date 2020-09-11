FROM nginx:latest

# Remove sym links from nginx image
RUN rm /var/log/nginx/access.log
RUN rm /var/log/nginx/error.log

# Install logrotate
RUN apt-get update && apt-get -y install logrotate

# install vim
RUN apt-get -y install vim

# Copy logrotate nginx configuration
COPY logrotate/nginx /etc/logrotate.d/