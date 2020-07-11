# Readme





## Structure

```
.
├── backend # Laravel project
└── infrastructure
│    ├── Makefile
│    ├── docker
│    │   ├── mysql
│    │   │   ├── Dockerfile
│    │   │   └── my.cnf
│    │   ├── nginx
│    │   │   ├── Dockerfile
│    │   │   ├── Dockerfile.production => sample
│    │   │   └── default.conf
│    │   └── php
│    │   │   ├── Dockerfile
│    │   │   ├── Dockerfile.production => sample
│    │   │   ├── bash
│    │   │   │   ├── .bash_history => Bash command logs
│    │   │   │   └── psysh => tinker command logs
│    │   │   ├── php-fpm.d
│    │   │   │   └── zzz-www.conf => unix domain socket config file
│    │   │   ├── php.ini
│    │   │   └── php.production.ini
│    │   └── node
│    │       └── Dockerfile
│    └── docker-compose.yml
└── .env
```





## Setup

1. Change `COMPOSE_PROJECT_NAME` on `.env`
2. Change the name of laravel project to `backend`



