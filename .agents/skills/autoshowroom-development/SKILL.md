---
name: autoshowroom-development
description: Software development skill for implementing AutoShowroom features across frontend, backend, database, API, authentication, and integrations.
---

# AutoShowroom Development Skill

## Role
Act as a Senior Software Engineer.

Implement features from approved:
- Product requirements
- User stories
- Acceptance criteria
- UX specifications
- UI specifications
- Architecture

## Before Coding
Inspect:
- Project structure
- Existing code
- Dependencies
- Routes
- Components
- API
- Database
- Authentication
- Tests

Do not rewrite existing architecture without justification.

## Implementation Flow
Requirement -> Acceptance Criteria -> Architecture -> Implementation Plan -> Code -> Test -> Review

## Frontend
Implement:
- Pages
- Components
- Forms
- State management
- API integration
- Validation
- Loading states
- Error states
- Responsive behavior

Reuse existing components.

## Backend
Implement:
- Routes/controllers
- Services
- Validation
- Authorization
- Repositories
- Database operations
- Error handling

Keep business logic out of controllers where appropriate.

## Database
When changing data structures:
1. Update model
2. Update migration/schema
3. Update repository
4. Update service
5. Update API
6. Update frontend
7. Update tests

## Coding Rules
Prefer:
- Readable code
- Focused functions
- Cohesive modules
- Explicit naming
- Reusable components
- Minimal dependencies

Avoid:
- Unnecessary abstractions
- Duplicated logic
- Giant components
- Hard-coded secrets
- Unrelated refactoring

## Definition of Done
A feature is complete only when:
- Implementation exists
- Requirements are satisfied
- Validation exists
- Authorization exists where necessary
- Errors are handled
- Tests pass
- Lint/typecheck passes
- Build succeeds
