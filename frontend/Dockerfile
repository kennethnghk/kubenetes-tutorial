# Dockerfile
FROM nginx:alpine

# Copy frontend files to nginx default directory
COPY ./dist /usr/share/nginx/html

# Expose port 80 for nginx
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]