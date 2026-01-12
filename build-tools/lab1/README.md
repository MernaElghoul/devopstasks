# Lab 1: Java App with Gradle

**Objective:** Build, test, and run a Java application using Gradle.

**Steps:**

1️⃣ **Install Gradle**  
```bash
cd /opt
sudo wget https://services.gradle.org/distributions/gradle-8.5-bin.zip
sudo unzip gradle-8.5-bin.zip
![Repository Cloned]()
sudo vi /etc/profile.d/gradle.sh
export GRADLE_HOME=/opt/gradle-8.5
export PATH=$PATH:$GRADLE_HOME/bin
source /etc/profile.d/gradle.sh
gradle -v

