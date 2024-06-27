# Jenkins CI/CD Pipeline Project

This project demonstrates a CI/CD pipeline using Jenkins to build, test, and deploy a simple Python application. The pipeline utilizes Docker containers for isolated build and test environments and deploys the application using Vercel. Additionally, Prometheus and Grafana are set up for monitoring the CI/CD process.

### Pipeline Stages

1. **Build**
    - Compile Python source files.
    - Stash compiled results.

2. **Test**
    - Run unit tests with pytest.
    - Generate JUnit XML report.

3. **Manual Approval**
    - Wait for manual approval before deploying.

4. **Deploy**
    - Build executable with PyInstaller.
    - Deploy to Vercel.


### Monitoring

Prometheus and Grafana are set up to monitor the CI/CD process.

1. **Prometheus**
    - Collects metrics from Jenkins.

2. **Grafana**
    - Visualizes metrics from Prometheus.

### Results

The result directory contains artifacts and screenshots from the CI/CD pipeline.
