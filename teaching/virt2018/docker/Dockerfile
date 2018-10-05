FROM ubuntu

# Update apt database and install nginx
RUN apt-get update
RUN apt-get install -y nginx

# Expose ports
EXPOSE 80

# Define default command
CMD ["nginx", "-g", "daemon off;"]
