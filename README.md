# Infrastructure - Recruiter App

This repository contains the infrastructure setup for the **Recruiter App** microservices system.

It includes:
- `docker-compose` for running the full local environment
- realm configuration and import files
- initialization SQL scripts

## 🚀 Setup Order (Important)

Follow this order to correctly start the system:

1. Clone or place all repositories that start with `recruiter-` into one parent directory  
2. Ensure all microservices are at the same level as the `infrastructure` folder  
3. Start infrastructure first:

```bash
cd infrastructure
docker-compose up -d
```

To simplify setup, it is recommended to open all microservices in IntelliJ IDEA using multi-project support (also called multi-module workspace).

## ⚙️ Configuration

Configuration for microservices is managed centrally.

If access to configuration is required, please contact the project maintainer:
- Email: yaroslav.lopatkin.work@gmail.com
