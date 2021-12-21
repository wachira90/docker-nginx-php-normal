# docker nginx php normal
docker nginx php normal

## change php version 
```
image: wachira90/php:7.1
image: wachira90/php:7.2
image: wachira90/php:7.3
image: wachira90/php:7.4    
```

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

