# Nginx Docker Compose

This project demonstrates usage of Nginx in Docker Compose network.   
Here one instance of Nginx (nginx) calls another instance (user) via Docker Compose network.

```
┌─────────────┐         ┌────────────┐
│             │         │            │
│  nginx      │         │  user      │
│             ├────────►│            │
│  pub:80     │         │  pub:8080  │
│  priv:80    │         │  priv:80   │
│             │         │            │
└─────────────┘         └────────────┘
```
