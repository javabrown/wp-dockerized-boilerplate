# Docker WordPress Boilerplate

A Docker-based WordPress boilerplate for creating seamless development environments. Quickly set up and run WordPress projects with this easy-to-use Docker Compose configuration. The setup includes a MySQL database container and a WordPress container, ensuring consistency across Windows and macOS environments. Use it as a foundation for your WordPress projects, eliminating the hassle of configuring local development environments.

## Features

- Docker Compose setup for WordPress development.
- MySQL container with easy configuration.
- Cross-platform compatibility for Windows and macOS.
- Convenient volume mapping for project files and database data.
- Get started with WordPress development in minutes!

## Usage

1. Clone the repository.
2. Customize the environment variables in the `.env` file.
3. Run `docker-compose -f docker-compose.yml up`.
4. Access your WordPress site at `http://localhost:8080`.

**After Docker Image Up, type following URL to launch the WordPress Site:**
[http://localhost:8080](http://localhost:8080)

**DB can be connected using following connection params:**
- HOST: localhost
- PORT: 3306
- USER: root
- PASSWORD: your-root-password

**Shutdown Docker Images (Free your computer memory):**
`docker-compose -f docker-compose.yml down`.

Happy coding!
