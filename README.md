##1. Prerequisites
Docker Desktop (Windows)

Docker Compose

GitHub account

Access to the internet (for pulling images)

##2. Setting Up the Services
Clone the repository: git clone https://github.com/<username>/<repository-name>.git

Navigate to the project directory: cd <repository-name>

Run the services: docker-compose up -d

##3. Accessing the Services
Gitea: http://localhost:3000

Grafana: http://localhost:3001

Authelia (SSO): http://localhost:9091

##4. Testing Logs in Grafana
Navigate to the Grafana dashboard at http://localhost:3001.

Use the sample queries provided to view logs from Loki.
