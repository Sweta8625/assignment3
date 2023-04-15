Start an Nginx container -> docker run -d nginx

Port forward to local and check -> docker run -p 8080:8080 -d nginx

Check logs -> docker logs 19409cba17e8

Go inside the container -> docker exec -it 19409cba17e8 bash

Stop the container -> docker stop 19409cba17e8
