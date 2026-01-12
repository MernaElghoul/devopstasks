# Lab 1: Java App with Gradle

**Objective:** Build, test, and run a Java application using Gradle.

**Steps:**

1️⃣ **Install java**  
```bash
cd /opt
sudo wget https://services.gradle.org/distributions/gradle-8.5-bin.zip
sudo unzip gradle-8.5-bin.zip
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab1/screenshots/install%20java.png?raw=true)
**Install gradle** 
```bash
sudo vi /etc/profile.d/gradle.sh
export GRADLE_HOME=/opt/gradle-8.5
export PATH=$PATH:$GRADLE_HOME/bin
source /etc/profile.d/gradle.sh
gradle -v
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab1/screenshots/install%20gradle.png?raw=true)
**clone**
```bash
git clone https://github.com/Ibrahim-Adel15/build1.git
cd build1
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab1/screenshots/clone%20app.png?raw=true)

**test app**
```bash
gradle test
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab1/screenshots/test.png?raw=true)

**build app**
```bash
gradle build
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab1/screenshots/build%20app.png?raw=true)
**run app**
```bash
java -jar build/libs/ivolve-app.jar
```
![Repository Cloned](https://github.com/MernaElghoul/devopstasks/blob/main/build-tools/lab1/screenshots/run.png?raw=true)






