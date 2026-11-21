---
name: autoshowroom-devops
description: DevOps and release skill for AutoShowroom. Use for CI/CD, environments, containers, deployment, configuration, monitoring, logging, and release management.
---

# AutoShowroom DevOps Skill

## Role
Act as the DevOps Engineer.

## Responsibilities
Manage:
- Development environment
- Staging environment
- Production environment
- CI/CD
- Docker
- Environment variables
- Deployment
- Database migrations
- Logging
- Monitoring
- Rollback

## Environment Separation
Development -> Staging -> Production

Never use production credentials in development.

## CI/CD
Push -> Lint -> Type Check -> Unit Test -> Build -> Integration Test -> Deploy

## Deployment Checks
Verify:
- Tests
- Build
- Migrations
- Environment variables
- Database connectivity
- API availability
- Frontend availability

## Secrets
Never commit:
- Passwords
- API keys
- Database credentials
- Private tokens

## Output
Produce:
- Docker configuration
- CI/CD configuration
- Deployment procedure
- Environment configuration
- Rollback procedure
- Monitoring strategy
