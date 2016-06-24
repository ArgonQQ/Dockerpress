Dockpress
========
:whale: Wordpress Containerized with persistent data container (Apache + Wordpress, MariaDB and two Data-Container :whale:

Clone the repository
------------------
```bash
git clone https://github.com/ArgonQQ/Dockpress.git
```

:whale: What is this? :whale:
-------------
With this `docker-compose.yml` file you can easily spin up your `Wordpress` with a `Database` and two `Data-Container` where everything is stored persistent.

```
Dockpress
├── LICENSE
├── Readme.md
└── docker-compose.yml
```

Getting Started
---------------
Change into the cloned directory and start the container daemonized

`docker-compose up -d`

Database Credentials
--------------------
```
DB-User:      root # Standard root MariaDB user
DB-Password:  MyPa$$word # Is set in the docker-compose.yml file
```
