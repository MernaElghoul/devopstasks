**lab 3**
## Steps to Run the Application

### 1. Build Docker Image
```bash
docker build -t app1 .
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/Docker-File/lab3/screenshots/dockerbuild.png?raw=true)
### 2. Run Docker Container
```bash
docker run -d -p 8080:8080 --name container1 app1
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/Docker-File/lab3/screenshots/dockerruncon.png?raw=true)

### 3. Check Running Container
```bash
docker ps
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/Docker-File/lab3/screenshots/dockerruncon.png?raw=true)
### 4. Test the Application
```bash
http://localhost:8080
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/Docker-File/lab3/screenshots/dockerrun.png?raw=true)
### 5. Stop and Remove Container
```bash
docker stop container1
docker rm container1
```
![Repository Cloned]()
