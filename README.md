# Intens API DevOps

**Practice assignment for DevOps learning.**

> This project is a forked assignment from [original source] for practice purposes.

---

## Steps

1. **Fork the repository**  
2. **Run the API locally**  
   - Use your preferred IDE (Eclipse, IntelliJ, VSCode, etc.)  
   - Set the environment variable `PORT` to `8080` or any available port  
3. **Create a Dockerfile** (5 points)  
4. **Deploy the API**  
   - Deploy to any cloud provider or locally using Docker/Kubernetes (5 points)  
5. **Implement CI/CD using GitHub Actions** (10 points)  
   - **Script 1:** Runs automatically on pull requests to the `master` branch and executes tests  
   - **Script 2:** Runs automatically on pushes to the `master` branch and:  
     - Builds the API  
     - Packages and uploads the Docker image to the chosen repository  
     - Replaces the old image with the new one on the selected cloud provider or local environment  
6. **Submit results**  
   - Send the URL of your GitHub repository and the deployed API URL (cloud or local) via email

---

## Useful Links

- [GitHub Actions: Building and Testing Java with Maven](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-java-with-maven)

---

## Required Tools

1. **Java 8** – [Oracle Java 8 Archive](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)  
2. **IDE of your choice** – Eclipse / IntelliJ / VSCode  
3. **Docker** – [Docker Desktop](https://www.docker.com/products/docker-desktop)  
