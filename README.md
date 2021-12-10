# docker nginx-1.18.0 php72 normal
docker nginx-1.18.0 php72 normal

## run 
````
  docker-compose up -d
````
## stop 
````
  docker-compose stop 
````
## restart
````
  docker-compose restart
````
## shutdown
````
  docker-compose down
````
## log
````
  docker-compose logs -ft
````
### URL
````
http://localhost:7000
http://localhost:7000/info.php
````

## change images version
````
image: wachira90/nginx:1.21.4
image: wachira90/nginx:1.18.0
````
modby => wachira90@yahoo.com

