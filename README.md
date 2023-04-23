# 🦉 Hoot
🌱 A tiny Human Resources management system, consisting of microservices, utilising RESTful HTTP and AMQP protocols to communicate.

💡 This is a hobby project, designed with the intention to enable practice with a varied tech stack, including:
- [x] C# .NET 7
- [x] Java 17
- [x] Spring Boot
- [x] Python 3
- [x] Flask
- [x] Javascript
- [x] NestJS
- [x] Express JS
- [x] Docker
- [ ] Entity Framework
- [ ] Spring Data
- [ ] SQLAlchemy
- [ ] PostgreSQL
- [ ] MongoDB
- [ ] Redis
- [x] Typescript
- [ ] React
- [ ] Tailwind CSS
- [ ] Next.js
- [x] Node.js
- [ ] RabbitMQ
- [ ] Azure Cloud Services

## Microservices
- [hoot-api-people](https://github.com/chrisashwalker/hoot-api-people)
- [hoot-api-posts](https://github.com/chrisashwalker/hoot-api-posts)
- [hoot-api-teams](https://github.com/chrisashwalker/hoot-api-teams)
- [hoot-api-links](https://github.com/chrisashwalker/hoot-api-links)

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
