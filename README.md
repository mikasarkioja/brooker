# Brooker Project

This project is a monorepo structure containing the following components:

## Structure

- **apps/api**: The backend API service (Prisma, Node.js).
- **libs/shared**: Shared code, DTOs, and interfaces.
- **libs/risk-engine**: Core business logic for risk assessment.
- **libs/fivaldi-adapter**: Adapter for Fivaldi ERP integration.

## Setup

1.  **Environment Variables**:
    - Copy `brooker.env.txt` to `.env` (or use it directly if configured).
    - Update `DATABASE_URL` if needed.

2.  **Docker**:
    - The project includes a `docker-compose.yml` for orchestration (currently empty/WIP).

## Development

*Work in progress - initial structure setup.*

