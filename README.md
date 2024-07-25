# Docker Compose

## Overview

The Docker Compose project contains Docker Compose files along with `.env` files for some of the most commonly used technologies by developers. Each technology is organized into its own folder, making it easy to download and run.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/.../docker-compose.git
   cd docker-compose
   ```
2. **Navigate to the desired folder**:
Each folder contains a Docker Compose file and a corresponding ```.env``` file. Choose the folder for the technology you want to use.

3. **Run Docker Compose**:
Execute the following command in the folder:
   ```bash
   docker compose up
   ```
This command will start the Docker containers defined in the ```docker-compose.yml``` file for that technology.

## Folder Structure
The project includes the following folders, each named according to the Docker images they contain:

- Apache_Camel
- Apache_Cassandra
- Apache_Kafka
- Camunda
- Elasticsearch
- Hashicorp
   - console
   - vault
- Keycloak
- MinIO
- MongoDB
- MySQL
- Neo4j
- PostgreSQL
- RabbitMQ
- Redis
 
## Notes
Ensure that you have Docker and Docker Compose installed on your machine before running the commands.
Each folder contains specific configurations and environment variables customized for the respective technology.

## Contributing
Feel free to contribute to this project by submitting issues or pull requests. Your contributions are welcome!

## License
Feel free to modify any sections as needed!
