# Use an existing image as a base
FROM nginx:latest

# Set the working directory to the Nginx document root
WORKDIR /usr/share/nginx/html

# Copy everything from the current directory to the working directory
COPY . .

# Expose port 80 to allow outside access
EXPOSE 80
