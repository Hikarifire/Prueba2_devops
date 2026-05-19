Devops_2/
│
├── backend/
│   ├── back-despacho-service/
│   │   ├── src/
│   │   ├── Dockerfile
│   │   ├── pom.xml
│   │   └── README.md
│   │
│   └── back-venta-service/
│       ├── src/
│       ├── Dockerfile
│       ├── pom.xml
│       └── README.md
│
├── frontend/
│   ├── src/
│   ├── Dockerfile
│   └── README.md
│
├── terraform/
│   ├── main.tf
│   ├── ecs.tf
│   ├── variables.tf
│   ├── outputs.tf
│   └── provider.tf
│
├── .github/
│   └── workflows/
│       ├── backend-deploy.yml
│       ├── ventas-deploy.yml
│       └── frontend-deploy.yml
│
├── docker-compose.yml
├── .gitignore
└── README.md
