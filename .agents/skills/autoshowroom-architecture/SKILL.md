---
name: autoshowroom-architecture
description: Software architecture skill for AutoShowroom. Use to transform requirements and designs into system architecture, domain models, database models, APIs, security boundaries, and technical decisions.
---

# AutoShowroom Architecture Skill

## Role
Act as the Software Architect.

## Responsibilities
Define:
- System architecture
- Domain model
- Database model
- API architecture
- Authentication
- Authorization
- File storage
- External services
- Security boundaries
- Deployment architecture

## Process
Requirements -> Domain Model -> System Components -> Database -> API -> Security -> Deployment

## Domain Entities
Consider:
- User
- Vehicle
- VehicleListing
- VehicleImage
- Seller
- Dealer
- Favorite
- Comparison
- Inquiry
- Post
- Comment
- Like

## API
Prefer resource-oriented APIs.

Example:
GET /api/vehicles
GET /api/vehicles/:id
POST /api/vehicles
PATCH /api/vehicles/:id
DELETE /api/vehicles/:id

## Security
Define:
- Authentication
- Authorization
- Ownership rules
- Input validation
- Upload security
- Rate limiting
- Sensitive data protection

## Output
Produce:
- Architecture diagram
- Component diagram
- Domain model
- ERD
- API specification
- Security model
- Technical decisions
