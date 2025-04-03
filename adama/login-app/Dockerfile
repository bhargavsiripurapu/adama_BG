# Use an official lightweight web server image
FROM nginx:alpine

# Set working directory
WORKDIR /usr/share/nginx/html

# Copy the HTML file and image into the Nginx HTML directory
COPY adama/login-app/adama.html index.html
COPY adama/login-app/adama.svg .
COPY adama/login-app/Farmer_with_Sugar_Cane.webp .

# Expose the default Nginx port
EXPOSE 80
