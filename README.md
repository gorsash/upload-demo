Installation
=============
1. Install [composer](https://getcomposer.org/) if it is not installed.
1. Run `composer install` in the project directory.
1. Create database for the project.
1. Copy the file `.env.example` to a new file called `.env`.
1. Setup database parameters in the `.env` file.
1. Run `./migrate.sh`.
1. Setup your web server to point to the `public` directory of the project.
