**Helios: Intelligent System Monitoring and Prediction**

Helios is a lightweight observability and predictive monitoring system built to collect, visualize, and forecast system performance metrics. 
It integrates Prometheus, Grafana, and a Python-based machine learning service for early warning insights — designed for both personal and 
small-scale cloud infrastructure monitoring.

**Objective**
To create a unified platform capable of:

- Collecting system metrics from multiple hosts (local and cloud).

- Visualizing performance in real time through Grafana dashboards.

- Predicting potential system stress or failures using ML models.

**Tech Stack**

- Programming: Python (Flask, scikit-learn, pandas, prometheus_client)

- Monitoring: Prometheus, Grafana, Windows Exporter

- Automation & Containerization: Docker, Docker Compose

- Cloud (optional): AWS EC2 for remote node integration

- Database (optional): SQLite or DynamoDB for storing training data
  

**Setup Overview**

- Clone the repository

-> git clone https://github.com/CyberLycan/helios.git

-> cd helios


- Create and activate a Python virtual environment

- Install dependencies
  
-> pip install -r requirements.txt

- Launch the monitoring stack via Docker Compose

- Run the ML microservice for predictive insights
  

**Outcome**

- A real-time monitoring system capable of:

- Observing and forecasting system resource usage

- Displaying interactive dashboards

- Extending easily to cloud infrastructure or multi-node setups
  

**Author**

_Karthik Chyawan_
Student | DevOps & Cloud Enthusiast | Author & Poet

Linkedin -> https://linkedin.com/in/karthikchyawan

Github profile -> https://github.com/CyberLycan

