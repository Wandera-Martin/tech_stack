# Traffic-Analytics-Data-Warehouse-Airflow-dbt-Redash

## Overview

This project focuses on creating a scalable data warehouse for a city traffic department, utilizing swarm UAVs (drones) to collect traffic data. The data is intended for improving traffic flow and undisclosed projects. The tech stack comprises MySQL, DBT, and Airflow, following the Extract Load Transform (ELT) framework.

## Project Structure

The project structure includes:

- **data:** Raw and cleaned datasets' CSV files.
- **dags:** Airflow DAGs for task orchestration.
- **notebooks:** Jupyter notebook for reading the data to the database
- **screenshots:** Visual representations of the project, including tech stack flow, path for track ID, and speed comparisons.
- **scripts:** Python utility scripts.
- **traffic_dbt:** dbt (Data Build Tool) files and configurations.
- **docker-compose.yaml:** YAML file for Docker Compose, facilitating the setup of Airflow and Docker.

# Airflow Data Loading with Docker

This repository contains the necessary files to set up a Dockerized Airflow environment for data loading into PostgreSQL.

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

