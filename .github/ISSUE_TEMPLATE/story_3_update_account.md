---
name: "Story 3 — Update Account"
about: "Update a Customer Account"
labels: feature
---

# Story 3 — Update Account

**As a customer service representative**  
I need to update a customer account  
So that I can modify customer details

## Details

- Update existing account information

## Acceptance Criteria

- [ ] Given a valid account ID
- [ ] When I send a PUT request to /accounts/{id}
- [ ] Then the account should be updated

- [ ] Given an invalid ID
- [ ] When I send a PUT request
- [ ] Then I should receive a 404 error
