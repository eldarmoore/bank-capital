# Bank Capital

Bank Capital is a web-based banking application built with Laravel 10. It allows users to manage their bank accounts, view transaction histories, transfer funds, and more. This project is designed as a practice exercise to explore and implement various web development concepts using Laravel.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed on your system:
- Docker
- Composer
- Git

### Installation

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/yourusername/bank-capital.git

2. Start the Docker containers using Laravel Sail:
   ```sh
   ./vendor/bin/sail up -d
3. Run database migrations to set up the database schema:
   ```sh
   ./vendor/bin/sail artisan migrate

## Usage
- To access the application, open your web browser and visit http://localhost.
- Register a new user account to start using the application features.
### Common Commands

* Starting the Docker environment:
   ```sh
   ./vendor/bin/sail up

* Stopping the Docker environment:
   ```sh
   ./vendor/bin/sail down
* Running migrations:
   ```sh
   ./vendor/bin/sail artisan migrate
* Running seeders (if applicable):
   ```sh
   ./vendor/bin/sail artisan db:seed
* Running tests:
   ```sh
   ./vendor/bin/sail artisan test

## Built With
- [Laravel 10](https://laravel.com/docs/10.x/releases) - The web framework used
- [Docker](https://www.docker.com/) - Containerization
- [MySQL](https://www.mysql.com/) - Database

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning
We use SemVer for versioning. For the versions available, see the tags on this repository.

## Authors
Your Name - Initial work - YourUsername
See also the list of contributors who participated in this project.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

To access the application, open your web browser and visit http://localhost.
Register a new user account to start using the application features.
Common Commands
