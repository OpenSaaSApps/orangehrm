# orangehrm

> Click To Deploy OrangeHRM — Open Source Human Resource Management

[![Sync](https://github.com/opensaasapps/orangehrm/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/orangehrm/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/orangehrm/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/orangehrm/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/orangehrm)](https://hub.docker.com/r/thefractionalpm/orangehrm)

Upstream: [orangehrm/orangehrm](https://github.com/orangehrm/orangehrm) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `ORANGEHRM_DATABASE_HOST` | ⚪ | |
| `ORANGEHRM_DATABASE_PORT` | ⚪ | |
| `ORANGEHRM_DATABASE_NAME` | ⚪ | |
| `ORANGEHRM_DATABASE_USER` | ⚪ | |
| `ORANGEHRM_DATABASE_PASSWORD` | ✅ | |
| `ORANGEHRM_ADMIN_USERNAME` | ⚪ | |
| `ORANGEHRM_ADMIN_PASSWORD` | ✅ | |
| `ORANGEHRM_SMTP_HOST` | ✅ | |
| `ORANGEHRM_SMTP_PORT` | ⚪ | |
| `ORANGEHRM_SMTP_AUTH_TYPE` | ⚪ | |
| `ORANGEHRM_SMTP_USERNAME` | ✅ | |
| `ORANGEHRM_SMTP_PASSWORD` | ✅ | |

## Image

```
docker pull orangehrm/orangehrm:latest
docker pull thefractionalpm/orangehrm:latest
```

## Ports

| Port | Service |
|---|---|
| `80` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
