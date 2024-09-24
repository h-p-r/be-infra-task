# Readme

- This Project demonstates running of 3 Nest.js services in docker environment.
- The services are only asscessible from a nginx reverse proxy on port 3000, 4000 and 5000 to enhance security.

## Fixes

- Fixed the users RestController Mapping

## Pre-requisites

- Docker
- Any Docker Runtime
- docker-compose
- Make sure ports 3000, 4000 and 5000 are not already occupied by other applications

## Installation

1. **Running the services:**
   Run the below command from the cloned repo directory
   ```sh
   docker-compose up --build
   ```
2. **Check the Running services:**
   Run the below commmand to check what all services are running
   ```sh
   docker ps
   ```
3. **Access the APIs:**
   The APIs can be asscessed from the below endpoints:
   
   - Users API: http://localhost:3000/users
   - Orders API: http://localhost:4000/orders
   - Products API: http://localhost:5000/products





