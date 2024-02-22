
# Django-Next.js-app

A fullstack web project with Django as the server, PostgreSQL as the database and Next.js as the frontend.

## About the template

- PostgreSQL used as the primary database.
- Superuser is already initialized with the credentials: Username- `admin`, Email- `admin@admin.com`, Password- `admin`
- Integration with Django Rest Framework
- Integrated Djoser for user register/login/logout workflows.
- Used JWT for Authentication.
- API Documentation is configured using swagger.
- Containerized using Docker and managed using docker-compose.
- A typescripted Next.js client has been preinstalled and integrated with docker-compose.
- Added Chakra UI and Chakra icons in the frontend as a design and component library alongwith axios for making api calls.

## Getting Started

To get a local copy of this template up and running on your machine, follow these simple steps.

### Prerequisites

- Docker
`curl -fsSL https://get.docker.com -o get-docker.sh`
`sudo sh get-docker.sh`

### Installation

- Clone the repo `git clone https://github.com/sachnaror/django-nextjs-app`
- Change the current directory to the template `cd django-nextjs-app`
- Build the docker containers`docker-compose -f docker-compose.dev.yml build` for the dev containers and `docker-compose -f docker-compose.prod.yml build` for the prod containers
- Run the docker containers`docker-compose -f docker-compose.dev.yml up` for the dev containers and `docker-compose -f docker-compose.prod.yml up` for the prod containers

## API Documentation

API documentation will be in swagger. You can view it in `/swagger` for API documentation soon once we start on APIs.

## Technologies used

<a href="https://www.djangoproject.com/" target="_blank"><img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/> </a>
<a href="https://www.django-rest-framework.org/" target="_blank"> <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray" /> </a>
<a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> </a>
<a href="https://www.postgresql.org" target="_blank"> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/></a>
<a href="https://www.nextjs.org/" target="_blank"> <img src="https://img.shields.io/badge/Next.JS-000000?style=for-the-badge&logo=next.js&logoColor=white"/> </a>
<a href="https://www.typescriptlang.org/" target="_blank"><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/></a>
