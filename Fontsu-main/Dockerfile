FROM php:8.2-cli

# Install required extensions
RUN docker-php-ext-install curl

# Set working directory
WORKDIR /app

# Copy project files
COPY . .

# Expose Render port
EXPOSE 10000

# Start PHP built-in server
CMD ["php", "-S", "0.0.0.0:10000"]
# Note: Adjust the port number as needed for your application