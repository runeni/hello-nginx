# hello-nginx
Simple docker example


# Build image
docker build -t hello-nginx .

# Run container
docker run -d -p 8080:80 hello-nginx

# Open this url in browser
http://localhost:8080