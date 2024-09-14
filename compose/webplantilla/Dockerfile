# Use an official Nginx image as the base image
FROM nginx:alpine

# Copy your static website files to the appropriate directory in the Nginx container
COPY . /usr/share/nginx/html

# Expose the port that Nginx uses
EXPOSE 81

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
