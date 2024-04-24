# Ferry

## Setup

### 0. Requirements

- Docker
- Docker Compose

- this setup assumes that [Cloudflare](https://www.cloudflare.com/) is the DNS provider for your domain.

### 1. Add environment variables

Add the missing information for the environment variables and host information:

```bash
nano .env
nano config/hosts
```

## Usage

### Start container

```bash
docker compose up -d
````

### Stop container

```bash
docker compose down
```
