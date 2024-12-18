# Exploring Apache Airflow & Astro for ETL Pipelines

This project showcases how to build and manage an ETL (Extract, Transform, Load) pipeline using **Apache Airflow** and **Astro**. The pipeline fetches weather data from an API, processes it, and loads it into a PostgreSQL database for further analysis.

## Overview

### Tools Used:
- **Apache Airflow**: An open-source platform for orchestrating workflows.
- **Astro (Astronomer)**: Simplifies managing Airflow deployments.
- **PostgreSQL**: Target database for storing processed data.
- **Docker**: Containerization for seamless deployment.

### Key Features:
- **ETL Pipeline**: Built using Airflow DAGs to extract, transform, and load data.
- **Daily Automation**: The pipeline runs daily to ensure the database is always up-to-date.
- **Dockerized Deployment**: The entire project is containerized and available on Docker Hub.

## Project Workflow

1. **Extract**:
   - Fetch weather data from a public API.
2. **Transform**:
   - Clean and preprocess the data into a structured format.
3. **Load**:
   - Store the transformed data in a PostgreSQL database.

The workflow is managed using **Directed Acyclic Graphs (DAGs)** in Airflow, enabling task orchestration and monitoring.

## Airflow UI Example
![Airflow DAGs](https://github.com/Naveennnkumar-Bit/etl-airflow-weather-pipeline/blob/main/AFL.png)


## Getting Started

### Prerequisites
- Docker and Docker Compose installed on your system.
- PostgreSQL set up locally or via a Docker container.

### Docker Hub Image
Pull the pre-built Docker image directly from Docker Hub:
```bash
docker pull naveenkumar16/etl_airflow
```

## Learning Outcomes

- Simplified scheduling and monitoring of workflows with Astro.
- Hands-on experience with building ETL pipelines using Airflow.
- Leveraging Docker to containerize and share data engineering projects.

## Next Steps

- Explore advanced Airflow features such as error handling and dynamic pipelines.
- Apply these concepts to larger-scale, real-world data engineering problems.

## Contributing
Feel free to fork this repository, open issues, and submit pull requests for improvements or new features.

## Acknowledgments
- **Krish Naik**: For the tutorial that inspired this project.

## Connect
- **Docker Hub**: Check out my [ETL with Airflow Docker repository](https://hub.docker.com/repository/docker/naveenkumar16/etl_airflow/general) for Docker images and configurations related to my ETL and Airflow projects.
- **LinkedIn**: Feel free to [connect with me on LinkedIn](https://linkedin.com/in/naveennnkumar) for networking and discussions on data science, analytics, and technology.

