# laravel-docker
docker laravel starter pack with nginx and mysql \n
non ssl

# steps:
1.linux: 
      $ docker run --rm -v $(pwd):/app composer install 
  Windows: 
      docker run --rm -v (pwd):/app composer install 
      e.g. docker run --rm -v D:\test:/app composer install 
2. $ docker-compose build 
3. $ docker-compose up -d 
   
