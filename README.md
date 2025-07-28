# ⚙️ Docker Compose Collection

## 📖 Overview

This project provides a curated collection of Docker Compose setups for many popular technologies used by developers.  
Each technology is organized into its own folder, containing a `docker-compose.yml` file and optional `.env` configuration, making it easy to run and test services locally.

---

## 🚀 Getting Started

To get started with the project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/.../docker-compose.git
   cd docker-compose
   ```

2. **Navigate to the desired folder**:  
   Each folder contains a `docker-compose.yml` file and a corresponding `.env` file (if needed). Choose the folder for the technology you want to use.

3. **Run Docker Compose**:
   ```bash
   docker compose up
   ```
   This command will start the containers defined in the `docker-compose.yml` file for the selected service.

---

## 📁 Folder Structure

The repository is organized by technology and includes the following folders:

- **Apache**
  - Cassandra
  - Kafka
- **Camunda**
- **Elastic Stack**
  - Elasticsearch
  - Logstash
  - Kibana
- **HashiCorp**
  - Consul
  - Vault
- **Keycloak**
- **MinIO**
- **MongoDB**
- **MySQL**
- **Neo4j**
- **Node.js**
- **n8n**
- **PostgreSQL**
- **RabbitMQ**
- **Redis**

Each folder is self-contained with its own Docker Compose file, allowing you to quickly spin up isolated environments.

---

## ⚠️ Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)

Make sure both are installed and properly configured on your system.

---

## 🤝 Contributing

Contributions are welcome!  
If you'd like to add a new technology or improve an existing setup, feel free to submit a pull request or open an issue.

---

## 📄 License

This project is open-source. Feel free to fork and adapt it for your own use.
