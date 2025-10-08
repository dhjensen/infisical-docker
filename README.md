# infisical-docker

[Infisical](https://infisical.com/) docker compose.

# .env example

```bash
REDIS_VERSION=version
POSTGRES_VERSION=version
POSTGRES_USER=infisical
POSTGRES_PASSWORD=password
POSTGRES_DB=infisical
INFISICAL_VERSION=version
INFISICAL_ENCRYPTION_KEY=key
INFISICAL_AUTH_SECRET=key
INFISICAL_SITE_URL=https://url
INFISICAL_DB_CONNECTION_URI=postgres://${POSTGRES_USER}:${POSTGRES_PASSWORD}@db:5432/${POSTGRES_DB}
INFISICAL_REDIS_URL=redis://redis:6379
```
