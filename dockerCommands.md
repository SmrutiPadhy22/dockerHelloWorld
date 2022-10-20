# Docker commands

- docker images
   ```sh
   docker images
```

- docker pull  
   ```sh
   docker pull hello-world
```

![image](https://user-images.githubusercontent.com/109865260/196842118-ca73fcf5-7ccf-42d5-9ae7-3815925d2893.png)

- docker version
```sh
docker --version
```
![image](https://user-images.githubusercontent.com/109865260/196843464-432e226e-b1db-483e-9703-b855ade061f5.png)

- docker run
```sh
docker run -d -p 5000:5000 smrutipadhy90/welcomeapp
```
![image](https://user-images.githubusercontent.com/109865260/196843641-0a9f936a-beb5-47ec-94ac-c8960a1fc7da.png)

- docker pull
```sh
docker pull hello-world
```
![image](https://user-images.githubusercontent.com/109865260/196844650-a9fdb809-b91a-4440-b293-e4b5325ba8ac.png)

- docker ps
```sh 
docker ps
```
![image](https://user-images.githubusercontent.com/109865260/196844762-935fea53-f1cb-4c49-aebd-71fbd3b79ca2.png)


- docker build
```sh
docker build -t smrutipadhy90/welcomeapp
```
![image](https://user-images.githubusercontent.com/109865260/196844983-32e6bb5c-f075-41e2-83d0-0c442df0d682.png)


- docker start
```sh
docker start <containerid>
```
![image](https://user-images.githubusercontent.com/109865260/196845829-ed601d98-33a3-42d6-8761-2a74bf48459c.png)


- docker stop
```sh
docker stop <containerid>
```
![image](https://user-images.githubusercontent.com/109865260/196846099-7c22d9a1-f3fa-469d-b028-0b19e4562b04.png)


- docker rmi(remove images)
```sh
docker rmi <imageid>
```
![image](https://user-images.githubusercontent.com/109865260/196846203-535afe04-23fb-450b-8df8-fbcf2f77ea78.png)


- docker push
```sh
docker push smrutipadhy90/welcomeapp:latest
```
![image](https://user-images.githubusercontent.com/109865260/196846502-014907f6-7777-4104-a7d1-79bb7e6436c3.png)


- docker history
```sh
docker history <imageid>
```
![image](https://user-images.githubusercontent.com/109865260/196846661-09f06426-df39-4402-9595-915e708b8f11.png)


- docker search <text>
```sh
docker search <text>
```
![image](https://user-images.githubusercontent.com/109865260/196846773-5da48365-8215-4b6c-b0d2-108fbf0c27a3.png)


- docker load
```sh
docker load
```
![image](https://user-images.githubusercontent.com/109865260/196846870-8c9fe3d3-5b72-47e2-8d61-5f571a771ddb.png)


- docker logs
```sh
docker logs
```
![image](https://user-images.githubusercontent.com/109865260/196846952-10128de9-7600-4541-b388-b5560bcc5f53.png)


- docker system prune
```sh
docker system prune
```
![image](https://user-images.githubusercontent.com/109865260/196847173-3a5618eb-e007-4a6b-80f7-560de2229d1c.png)


- docker volume
```sh
docker volume ls
```
![image](https://user-images.githubusercontent.com/109865260/196847276-c9adafd1-7fce-41b2-bc0e-2fe722d05f7d.png)

- docker exec 
```sh
docker exec -it <containerid>
```
![image](https://user-images.githubusercontent.com/109865260/196847422-bb92b3f2-337d-4dd9-b7cc-32794f0c25fb.png)


- docker inspect
```sh
docker inspect <imageid>
```
![image](https://user-images.githubusercontent.com/109865260/196847555-73706011-f0d3-482e-a055-b9e1d035a119.png)


- docker images
```sh
docker images
```
![image](https://user-images.githubusercontent.com/109865260/196847635-8b039c55-3330-4192-a948-3c83415d0366.png)
