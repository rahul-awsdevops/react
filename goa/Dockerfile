# Use the official Nginx image from Docker Hub
FROM nginx:latest

# Copy the local website files (index.html, style.css, images) into the container
COPY ./ /usr/share/nginx/html/

# Expose the port you want Nginx to run on (change to a custom port)
EXPOSE 8080

# Default command to run the Nginx server
CMD ["nginx", "-g", "daemon off;"]
