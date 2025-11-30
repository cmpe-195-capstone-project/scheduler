## EmberAlert Scheduler

The scheduler periodically polls the Cal Fire public API, processes and cleans the incoming incident data, and stores it in the PostgreSQL database. It ensures that wildfire information remains up-to-date and consistent for the API server. This component runs independently, continuously refreshing the backend data used by clients.

### Responsibilities
- Fetch wildfire incident data at scheduled intervals
- Validate and clean incoming data
- Insert or update incident records in the database
- Provide a reliable data source for  clients
## Tech Stack
> This project's backend is built using the following core technologies:

<div align="center">
    <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="Postgres" />
    <img src="https://img.shields.io/badge/fastapi-109989?style=for-the-badge&logo=FASTAPI&logoColor=white" alt="FastAPI" />
    <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
    <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
</div>

---

## Running the Scheduler

This service is intended to run as part of the EmberAlert backend using Docker Compose.
Refer to the main backend README for setup and deployment instructions.

👉 [EmberAlert Backend README](https://github.com/cmpe-195-capstone-project/backend)

