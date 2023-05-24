# Docker WordPress

This repository provides a Docker-based environment for running WordPress.

## Getting Started

### Prerequisites

To use this environment, you will need to have Docker and Docker Compose installed on your system. If you do not already have these tools installed, you can download them from the Docker website:

- [Docker](https://www.docker.com/products/docker-desktop)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Installation

To install and run the environment, follow these steps:

1. Clone this repository to your local machine.
2. Add `wordpress.local` in your hosts File
2. Navigate to the cloned repository in your terminal.
3. Run the `docker-compose up` command to start the containers.
4. Open a web browser and navigate to `http://wordpress.local` to access the WordPress site.

### USE PhpMyAdmin

Open a web browser and navigate to `http://localhost:8081/`

## Configuration

This environment is pre-configured with default settings, but you can customize it to suit your needs. Some of the available configuration options include:

- Database settings: You can modify the database settings in the `docker-compose.yml` file to use a different database name, username, and password.
- PhpMyAdmin settings: You can modify the PhpMyAdmin settings in the `docker-compose.yml` file to use a different username, and password.
- WordPress version: You can modify the WordPress version used by changing the `WORDPRESS_VERSION` environment variable in the `docker-compose.yml` file.
- Themes and plugins: You can add or remove themes and plugins by modifying the `wordpress/wp-content` directory in the repository.

For more information on configuring the environment, see the [official Docker documentation](https://docs.docker.com/compose/wordpress/).

## Contributing

If you would like to contribute to this repository, please follow these steps:

1. Fork this repository to your own account.
2. Create a new branch with your changes: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -am 'Added some feature'`.
4. Push your changes to your fork: `git push origin my-feature-branch`.
5. Create a new pull request and wait for approval.

## License

This repository is licensed under the MIT License - see the `LICENSE` file for details.
