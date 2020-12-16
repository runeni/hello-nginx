[![Board Status](https://amendeinhouse.visualstudio.com/379f3696-7225-4468-9f8a-639ff302ff6b/a692c86c-415e-4614-9fa7-59915a218680/_apis/work/boardbadge/9d274719-c2e9-4100-9e02-8d738578d350)](https://amendeinhouse.visualstudio.com/379f3696-7225-4468-9f8a-639ff302ff6b/_boards/board/t/a692c86c-415e-4614-9fa7-59915a218680/Microsoft.RequirementCategory)
# hello-nginx
Simple docker example


# Build image
docker build -t hello-nginx .

# Run container
docker run -d -p 8080:80 hello-nginx

# Open this url in browser
http://localhost:8080