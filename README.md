# Typo3 Setup

## Services

- MariaDB 10
- Typo3 8

## Installation

After issuing `docker-compose up --build` open `http://localhost` in your browser and you will be led through the Typo3 setup dialog.
On the first page (database connection) please enter:
- Available: "Manually configured  MySQL TCP/IP connection"
- Username: typo3
- Password: typo3pw
- Host: typo3-db
- Post: 3306

On the next page (select database), check option "Use an existing empty database" and select the database "typo3".

On the next page you are asked to enter the credentials for the admin user. Choose as you like and continue.

On the last page you are asked what your first step after admin login. I chose to select a prebuilt package.

## References

https://www.martin-helmich.de/de/blog/typo3-cms-docker.html
