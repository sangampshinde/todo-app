# PROJECT STRECTURE
```text
todo-app/
├── backend/              # NestJS backend
├── frontend/             # Next.js frontend
├── docker-compose.yml    # For PostgreSQL and other services
└── README.md

# Backend (NestJS) 
## Folder Structure
backend/
├── src/
│   ├── auth/             # Authentication module
│   ├── common/           # Shared utilities, filters, interceptors
│   ├── config/           # Configuration files
│   ├── mail/             # Email templates and services
│   ├── notifications/    # Notification system
│   ├── tasks/            # Todo tasks module
│   ├── users/            # User management
│   ├── app.module.ts     # Root module
│   └── main.ts           # Application entry point
├── test/                 # Test files
├── .env                  # Environment variables
├── nest-cli.json
├── package.json
└── tsconfig.json
