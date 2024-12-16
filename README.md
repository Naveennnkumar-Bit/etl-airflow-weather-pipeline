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

## Getting Started

### Prerequisites
- Docker and Docker Compose installed on your system.
- PostgreSQL set up locally or via a Docker container.

### Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
```

### Running Locally with Docker

1. **Build and Start the Project**:
   ```bash
   docker-compose up --build
   ```

2. **Access Airflow**:
   - Webserver: [http://localhost:8080](http://localhost:8080)
   - Default credentials:
     - Username: `admin`
     - Password: `admin`

3. **Run the Pipeline**:
   - Trigger the DAG manually from the Airflow UI or let it run on the scheduled interval.

### Docker Hub Image
Pull the pre-built Docker image directly from Docker Hub:
```bash
docker pull <your-dockerhub-username>/<your-image-name>
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
- **Docker Hub**: [Link to Docker Hub Image](https://hub.docker.com/repository/docker/naveenkumar16/etl_airflow/general)
- **LinkedIn**: [Your LinkedIn Profile](linkedin.com/in/naveennnkumar)
