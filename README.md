# 🦉 Hoot
🌱 A tiny Human Resources management system, consisting of microservices, utilising RESTful HTTP and AMQP protocols to communicate.

💡 This is a hobby project, commencing April 2023. It is not designed for production, but is to enable practice with a varied tech stack, including:
- [x] C# .NET 7
- [x] Java 17
- [x] Spring Boot
- [x] Python 3
- [x] Flask
- [x] Javascript
- [x] Typescript
- [x] NestJS
- [x] Express JS
- [x] Node.js
- [x] Docker
- [x] RabbitMQ
- [x] PostgreSQL
- [x] Entity Framework
- [x] Spring Data
- [x] MongoDB
- [x] PyMongo
- [x] Mongoose
- [ ] React
- [ ] Tailwind CSS
- [ ] Next.js
- [ ] Azure Cloud Services
  
___

![System diagram](diagram_architecture.drawio.png)

___

## Microservices
- [hoot-api-people](https://github.com/chrisashwalker/hoot-api-people)
- [hoot-api-posts](https://github.com/chrisashwalker/hoot-api-posts)
- [hoot-api-teams](https://github.com/chrisashwalker/hoot-api-teams)
- [hoot-api-links](https://github.com/chrisashwalker/hoot-api-links)

## API Gateway
- [hoot-api-gateway](https://github.com/chrisashwalker/hoot-api-gateway)

## Run
- Clone the microservice repositories
- Clone the API gateway repository
- Build Docker images as per instructions for each repository
- Run instances of the microservices and the API gateway using the Docker Compose configuration in this repository, with the command:
```
docker compose up -d
```
