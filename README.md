#Smart Bio-Reactor Monitoring Platform Using Big Data and IoT

This is the project of my course Big data Techonlogies for M1 at CNAM, which presents a real-time monitoring platform for bio-reactors, utilizing IoT sensors and big data technologies to track and optimize crucial environmental parameters. It aims to enable early anomaly detection and prediction to enhance bio-reactor efficiency.

 Here are few objectives

    Simulate and collect real-time data for key parameters: temperature, pressure, humidity, and O₂ levels
    Detect anomalies and predict trends using machine learning
    Visualize data and alerts in real time
    Deploy the system using microservices for scalability

  System Architecture Modules:

    Sensor Data Generation (Simulation)
        Python script simulates IoT sensor output with controlled anomalies
    Data Ingestion with Apache Kafka
        Kafka streams real-time data to consumers
    Data Storage with MongoDB
        NoSQL database stores structured sensor data
    Real-Time Dashboard (Grafana/Kibana)
        Monitors and visualizes live data
    Advanced Analytics
        Uses SVM for anomaly classification
        Implements LSTM for time-series forecasting

  Deployment
        Dockerized services
        Kubernetes for orchestration

  Tech Stack
    Programming: Python
    Big Data: Apache Kafka
    Database: MongoDB
    Visualization: Grafana, Kibana
    ML Models: Scikit-learn (SVM), Keras (LSTM)
    DevOps: Docker, Kubernetes
