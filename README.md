# MyGraderList

MyGraderList is a web app that lets students assess the difficulties and worthiness of each DSA grader problem in their respective courses.

## Frontend
### Technologies

-   TypeScript
-   React (Next)
-   tailwindcss
-   shadcn/ui
-   axios

### Repositories
- [Frontend](https://github.com/bookpanda/mygraderlist-frontend): web UI

## Server
The server uses gRPC for communication between microservices and also implements clean architecture.

### Why microservices?
Just for learning purposes. I wanted to know how to implement microservices and this project was a good opportunity to do so.

### Technologies

-   golang
-   gRPC
-   go-fiber
-   gorm
-   mysql
-   redis

### Repositories
- [Proto](https://github.com/bookpanda/mygraderlist-proto): common protobuf messages and services definitions library for all microservices
- [Gateway](https://github.com/bookpanda/mygraderlist-gateway): central server that handles all requests and sends them to the appropriate microservices
- [Backend](https://github.com/bookpanda/mygraderlist-backend): handles the business logic of the app
- [Auth](https://github.com/bookpanda/mygraderlist-auth): handles the authentication and authorization of the app


## Getting Started

### Prerequisites

-   pnpm
-   golang 1.21 or [later](https://go.dev)
-   docker
-   makefile

### Installation and Setup

1. Clone the [frontend](https://github.com/bookpanda/mygraderlist-frontend) and [gateway](https://github.com/bookpanda/mygraderlist-gateway) repo
2. Follow the instructions in the respective README.md

## Special Thanks
A huge thank you to [ImSoZRious](https://github.com/ImSoZRious) for all the help and guidance in this project.