# Prepared project set-up for laravel with docker

- CD into project
  ```console
  cd laravel-docker
   ```
- Make directory with the name of 'app'
     ```console
   mkdir app
   ```
- COPY all from laravel project into /app
   ```console
   cp -a LARAVEL_PROJECT/. app
   ```
- UPDATE .env value in /docker/.env
  ```console
   cd docker 
   vim .env
   ```
- RUN in docker directory
   ```console
    docker-compose up -d --build
    ```



