#Quick PHP, MySQL, Nginx and Symfony (Or Laravel) Docker setup

Ensure you have Docker Desktop installed -> https://www.docker.com/products/docker-desktop/
- Clone the repository
- Run `docker-compose up --build` to build the containers and create the `app/` directory
- Grab the ID of the `symfony_docker_php` container with `docker ps`
- Connect to the container with `docker exec -it <containerID> /bin/sh`
- Configure Git - `git config --global user.email "you@example.com"` and
  `git config --global user.name "Your Name"`
- Install Symfony with `symfony new .` (Or Laravel if you prefer)
- Load up `localhost:8080` in your browser.

## MySQL details
- MYSQL_ROOT_PASSWORD: docker_and_symfony
- MYSQL_DATABASE: docker_and_symfony
- MYSQL_USER: docker_and_symfony
- MYSQL_PASSWORD: docker_and_symfony

