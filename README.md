# gitea-docker

My [gitea](https://about.gitea.com/) docker compose.

It starts the following services:
* db - postgres
* gitea - Gitea

## .env example

```bash
GITEA_VERSION=version
GITEA__database__DB_TYPE=type
GITEA__database__HOST=host:port
GITEA__database__NAME=dbname
GITEA__database__USER=username
GITEA__database__PASSWD=password
POSTGRES_VERSION=version
POSTGRES_USER=username
POSTGRES_PASSWORD=password
POSTGRES_DB=dbname
```
