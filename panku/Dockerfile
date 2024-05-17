# Use the official Nginx image as the base image
FROM nginx:latest

# Copy the custom Nginx configuration file from the host into the container
#COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80 to allow outside access to the Nginx server
EXPOSE 80

# Command to run Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]

