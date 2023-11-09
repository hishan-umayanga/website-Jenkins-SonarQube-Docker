# Use a small NGINX base image
FROM nginx:alpine

# Copy your website files into the NGINX html directory
COPY . /usr/share/nginx/html

# Expose port 3200
EXPOSE 3200

# Start NGINX when the container runs
CMD ["nginx", "-g", "daemon off;"]
