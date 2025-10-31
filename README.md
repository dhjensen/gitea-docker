# gitea-docker

My [gitea](https://about.gitea.com/) docker compose.

It starts the following services:
* db - postgres
* gitea - Gitea

## .env example

```bash
GITEA_VERSION=1.25.0
GITEA__database__DB_TYPE=postgres
GITEA__database__HOST=db:5432
GITEA__database__NAME=gitea  
GITEA__database__USER=gitea  
GITEA__database__PASSWD=password
POSTGRES_VERSION=17.6
POSTGRES_USER=gitea    
POSTGRES_PASSWORD=password
POSTGRES_DB=gitea
```
