# laravel-docker
docker laravel starter pack with nginx and mysql + non ssl

# steps:
1.linux: 
    ```sh
    $ docker run --rm -v $(pwd):/app composer install 
    ```
  Windows:
    ```sh
    docker run --rm -v (pwd):/app composer install 
    ```
    ```sh
    e.g. docker run --rm -v D:\test:/app composer install 
    ```
2. $ docker-compose build 
3. $ docker-compose up -d 
   
