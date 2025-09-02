FROM nginx:latest

# Remove default index
RUN rm -rf /usr/share/nginx/html/index.html

# Copy your custom app code
COPY code /usr/share/nginx/html/

# If you have a custom nginx.conf, uncomment the next line
# COPY expense.conf /etc/nginx/nginx.conf

# Use default entrypoint & user (don’t override)
