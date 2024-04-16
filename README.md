# FireCB Web Application

## Description

FireCB is a modern web application that utilizes Nginx and PHP for serving web content, with MySQL and Redis for data storage and caching. This setup is designed to offer robust, scalable performance for web applications.

## Services

The Docker Compose configuration includes the following services:
- **Nginx** (`firecb-nginx`): Serves as the web server, configured to handle requests and serve static assets.
- **PHP** (`firecb-php`): Handles dynamic content processing in conjunction with Nginx.
- **MySQL** (`firecb-db`): Used for database services with a volume for data persistence.
- **Redis** (`firecb-redis`): Acts as a caching layer to improve performance, also with a volume for data persistence.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
