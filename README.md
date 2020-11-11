# junit-appium-app-browserstack-parallel

This repository demonstrates how to run Appium tests in [JUnit4](http://junit.org/junit4/)  on BrowserStack App Automate.

![BrowserStack Logo](https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780)

## Setup

### Requirements

1. Java 8+

    - If Java is not installed, follow these instructions:
        - For Windows, download latest java version from [here](https://java.com/en/download/) and run the installer executable
        - For Mac and Linux, run `java -version` to see what java version is pre-installed. If you want a different version download from [here](https://java.com/en/download/)

2. Maven
   - If Maven is not downloaded, download it from [here](https://maven.apache.org/download.cgi)
   - For installation, follow the instructions [here](https://maven.apache.org/install.html)

### Run parallel

In order to test the apps of Android and IOS parallelly, run following commands after you change the files of run_parallel_test  directory refer to https://github.com/kevinlee2020/junit-appium-app-browserstack

    
    mvn clean
    mvn test -P parallel
    

