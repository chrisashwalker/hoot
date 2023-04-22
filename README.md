# 🦉 Hoot
🌱 A tiny Human Resources management system, consisting of microservices, utilising RESTful HTTP and AMQP protocols to communicate.

💡 This is a hobby project, designed with the intention to enable practice with a varied tech stack, including:
- C# .NET 7
- Java 17
- Spring Boot
- Python 3
- Flask
- Javascript
- Express JS
- Docker
- Entity Framework
- Spring Data
- SQLAlchemy
- PostgreSQL
- MongoDB
- Redis
- Typescript
- React
- Tailwind CSS
- Next.js
- Node.js
- RabbitMQ
- Azure Cloud Services

## Microservices
- [hoot-api-people](https://github.com/chrisashwalker/hoot-api-people)
- [hoot-api-posts](https://github.com/chrisashwalker/hoot-api-posts)
- [hoot-api-teams](https://github.com/chrisashwalker/hoot-api-teams)

## API Gateway
- [hoot-api-gateway](https://github.com/chrisashwalker/hoot-api-gateway)

## Run
- Clone the microservice repositories
- Build Docker images as per instructions for each repository
- Clone the API gateway repository
- Run instances of the microservices and the API gateway using the Docker Compose configuration in this repository, with the command:
```
docker compose up -d
```
