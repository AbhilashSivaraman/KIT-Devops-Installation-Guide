# Installation Guidelines

This document provides step-by-step instructions to install the necessary tools required for KIT Devops workshop session - 23/08/2024

## 1. Install JDK (Java Development Kit)
**Version:** JDK 11 or later  
**Purpose:** Required for Jenkins, as it's built on Java.

### Steps:
1. **Download the JDK:**
   - Visit the [Oracle JDK Download page](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or the [OpenJDK page](https://openjdk.java.net/install/).
   - Download the appropriate version for your operating system.

2. **Install the JDK:**
   - Follow the installation instructions provided on the download page.
   - Set the `JAVA_HOME` environment variable to point to your JDK installation directory.
   - Verify the installation by running `java -version` in your terminal.

### Video Guide:
[Click here for reference video for JDK Installation](https://www.youtube.com/watch?v=5LlfwQ4xzXc)

## 2. Install Jenkins
**Version:** Jenkins LTS version 2.387.1 or later

### Steps:
1. **Download Jenkins:**
   - Visit the [Jenkins LTS download page](https://www.jenkins.io/download/lts/).
   - Download the version compatible with your operating system.

2. **Install Jenkins:**
   - Follow the installation instructions provided on the Jenkins download page.
   - Start Jenkins by running the command appropriate for your OS for Windows ```java -jar jenkins.war```
   - Access Jenkins by navigating to `http://localhost:8080` in your browser.

### Video Guide:
[Click here for reference video for Jenkins Installation](https://www.youtube.com/watch?v=Zdxko2bPAAw&t=499s)

## 3. Install Docker
**Version:** Docker Desktop 4.24.2 or Docker Engine 24.0.5 (for Linux users)

### Steps:
1. **Download Docker:**
   - Visit the [Docker Desktop download page](https://www.docker.com/products/docker-desktop) for Windows and macOS.
   - Linux users can refer to the [Docker Engine installation guide](https://docs.docker.com/engine/install/).

2. **Install Docker:**
   - Follow the installation instructions provided on the Docker website.
   - Verify the installation by running `docker --version` in your terminal.

### Video Guide:
[Click here for reference video for Docker Installation](https://www.youtube.com/watch?v=ZyBBv1JmnWQ)

## 4. Install Docker Compose
**Version:** Docker Compose 2.20.2 or later

### Steps:
1. **Download Docker Compose:**
   - Docker Desktop includes Docker Compose by default.
   - Linux users can install Docker Compose separately by following the [Docker Compose installation guide](https://docs.docker.com/compose/install/).

2. **Verify Installation:**
   - Run `docker-compose --version` to check the installed version of Docker Compose.

## 5. Install Git
**Version:** Git 2.42.0 or later

### Steps:
1. **Download Git:**
   - Visit the [Git download page](https://git-scm.com/downloads) and download the appropriate version for your operating system.

2. **Install Git:**
   - Follow the installation instructions provided on the download page.
   - Verify the installation by running `git --version` in your terminal.

### Video Guide:
[Click here for reference video for Git Installation](https://www.youtube.com/watch?v=JgOs70Y7jew)

## 6. Install Maven (Optional but recommended)
**Version:** Maven 3.8.6 or later

### Steps:
1. **Download Maven:**
   - Visit the [Maven download page](https://maven.apache.org/download.cgi) and download the appropriate version for your operating system.

2. **Install Maven:**
   - Follow the installation instructions provided on the download page.
   - Verify the installation by running `mvn -version` in your terminal.

### Video Guide:
[Click here for reference video for Maven Installation](https://www.youtube.com/watch?v=XEphzGQz-nI)

---