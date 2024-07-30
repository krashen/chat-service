# Microservices-based chat application server

## Description

This app uses NextJS, MongoDB, RabbitMQ, Nginx, and Docker

## Installation

Clone the code, provide the .env files with the corresponding variables according to `/src/config/config.ts` in each of the three main services `chat-service notification-service user-service`

Run `docker-compose up --build` to build the containers.