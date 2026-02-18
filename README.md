# Jenkins & Maven CI Practice Project

This project is a hands-on exercise for setting up a **Continuous Integration (CI)** pipeline. It demonstrates how to automate the compilation, testing, and packaging of a Java application.

## 🚀 Features
* **Automated Builds:** Triggered by code commits.
* **Testing:** Automated unit testing via Maven Surefire.
* **Artifact Management:** Generates versioned `.jar` files.
* **Reporting:** Jenkins console output for real-time debugging.

---

## 🛠 Tech Stack
* **Java:** The core programming language.
* **Maven:** For dependency management and build automation.
* **Jenkins:** The automation server orchestrating the pipeline.
* **Git:** Version control.

---

## 📋 Prerequisites
Ensure you have the following installed:
* [Java JDK 11+](https://www.oracle.com/java/technologies/downloads/)
* [Apache Maven](https://maven.apache.org/download.cgi)
* [Jenkins](https://www.jenkins.io/download/)

---

## 🏗 Setup & Configuration

### 1. Local Verification
Run the following commands to ensure the project is healthy before moving to Jenkins:
```bash
# Clone the repository
git clone <your-repo-url>

# Build the project
mvn clean install
