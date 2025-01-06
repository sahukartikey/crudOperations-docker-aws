# CRUD Operations with Docker and AWS Integration

Welcome to the **sahukartikey-crudOperations-docker-aws** repository! This project is a robust backend system for managing CRUD (Create, Read, Update, Delete) operations, designed to leverage **Docker** for containerization and **AWS** for scalable cloud integration.

---

## Features

- **CRUD Operations**: Complete functionality for managing user data.
- **Docker Support**: Seamless development and deployment with `Dockerfile` and `docker-compose.yml`.
- **AWS Integration**: Includes utility modules to interact with AWS services.
- **Database Management**: SQL database with sample backup (`backup.example.sql`) provided for easy initialization.
- **CI/CD Pipelines**: Automated build and release workflows with GitHub Actions (`build.yml` and `release.yml`).
- **TypeScript**: Strongly typed, maintainable codebase.

---

## Directory Structure

```plaintext
sahukartikey-crudOperations-docker-aws/
├── README.md                # Documentation
├── Dockerfile               # Docker container configuration
├── backup.example.sql       # Example SQL database backup
├── build.yml                # CI workflow for build and testing
├── docker-compose.yml       # Docker Compose configuration
├── package.json             # Node.js dependencies and scripts
├── release.yml              # CI workflow for application release
├── tsconfig.json            # TypeScript configuration
└── src/                     # Source code
    ├── authenticated-item.ts # Authentication logic for items
    ├── aws-helpers.ts        # AWS service helper functions
    ├── db-item.ts            # Database item interactions
    ├── local-item.ts         # Local item storage management
    ├── local-user.ts         # Local user management
    ├── server-helpers.ts     # Server utility functions
    ├── server.ts             # Application entry point
    ├── models/               # Data models
    │   └── users.ts          # User data schema
    └── util/                 # Utility functions
        └── database.ts       # Database connection and queries
Features:
CRUD Operations: Includes server-side functionality for managing user data, leveraging TypeScript for type safety.

Docker Integration: Provides containerization support with a Dockerfile and docker-compose.yml for seamless development and deployment.

AWS Integration: Includes helper modules to interact with AWS services for scalable cloud-based storage and computing.

Database Management: Utilizes SQL database with example backups (backup.example.sql) and configuration scripts.

CI/CD Pipeline: Pre-configured GitHub Actions workflows (build.yml, release.yml) for automated builds, testing, and releases.