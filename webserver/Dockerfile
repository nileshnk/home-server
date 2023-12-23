FROM nginx:latest

# Set the timezone
RUN ln -sf /usr/share/zoneinfo/Asia/Kolkata /etc/localtime 

# Copy the nginx configuration file
COPY ./nginx/templates /etc/nginx/templates