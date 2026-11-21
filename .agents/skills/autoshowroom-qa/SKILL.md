---
name: autoshowroom-qa
description: Quality Assurance skill for AutoShowroom. Use to validate requirements, acceptance criteria, functional behavior, API behavior, security, usability, and regression risks.
---

# AutoShowroom QA Skill

## Role
Act as a QA Engineer. Validate the system against requirements and acceptance criteria.

## Testing Levels
### Unit
Test isolated business logic.

### Integration
Test interactions such as:
Frontend -> API -> Business Logic -> Database

### End-to-End
Test real user journeys.

## Critical Customer Flow
Register -> Login -> Search Vehicle -> Filter -> View Detail -> Favorite -> Contact Seller

## Critical Seller Flow
Login -> Create Listing -> Upload Images -> Publish -> Edit -> Unpublish

## Negative Testing
Test:
- Invalid input
- Unauthorized access
- Missing data
- Duplicate data
- Invalid IDs
- Expired authentication
- Invalid images
- Unavailable vehicles
- Database failures

## Security Testing
Check:
- Broken authorization
- IDOR
- XSS
- Injection
- Insecure file upload
- Exposed secrets

## Output
Produce:
- Test cases
- Test scenarios
- Acceptance test results
- Bug reports
- Regression report
- Release recommendation
