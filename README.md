# Calculator Webapp project using Flask 

Dockerize Calculator webapp flask application .

    - Develop web application and make docker file .
    - Build the docker file .
    - ** Run to check the application .
    - Push to docker registry : Docker hub

## Project Structure

1. Make the Flask web application project structure .

2. Make a Dockerfile and write code into it .

3. In Gitbash terminal of VSCode :

```bash
docker build . -t calc
docker images
docker run -p 8080:5000 calc
```

4. Open any web browser : `http://localhost:8080/`

5. Dockerization of Calculator web application is completed .

## Next Step

1. Open another Gitbash terminal .

2. Open any web browser : `docker login`

3. Build again :

```bash
docker build . -t jateendra/calcapp
docker images
docker push jateendra/calcapp
```

4. Login to `https://hub.docker.com/` and check your repository .

5. Now the docker image `jateendra/calcapp` is available to tht whole world and they can download from docker hub registry .

