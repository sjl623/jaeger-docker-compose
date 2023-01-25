Jaeger docker compose
- with elasticsearch as storage backend
- use basic-auth to protect jaeger UI

visit jaeger UI with http://localhost \
default user/passwd: **admin/admin**\
genereate your username/password in https://www.web2generators.com/apache-tools/htpasswd-generator and replace it in `docker-compose.yml`\
DON'T forget to escape any $ with $$ in `docker-compose.yml`
