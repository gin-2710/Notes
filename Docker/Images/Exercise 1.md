![[Pasted image 20250517180157.png]]

`docker build -f web-server.Dockerfile .`

`docker run -d --rm -p 8080:5000 -v ./website:/usr/share/nginx/html/nginx/h -t website`
