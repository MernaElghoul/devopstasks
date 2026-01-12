# Lab 2: Building and Packaging Java Applications with Maven

## Steps

1. **Install Maven**  
   ```bash
   sudo apt update
   sudo apt install maven -y
   mvn -v
   ```
   ![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab2/screenshots/maven%20install.png?raw=true)
**clone**
```bash
git clone https://github.com/Ibrahim-Adel15/build2.git
cd build2
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab2/screenshots/clone.png?raw=true)

**run unit tests**
```bash
mvn test
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab2/screenshots/testapp.png?raw=true)

**build app**
```bash
mvn package
```
mvn package

**run app**
```bash
mvn package

