---
name: "Story 2 — Read Account"
about: "Read a Customer Account"
labels: feature
---

# Story 2 — Read Account

**As a customer service representative**  
I need to read a customer account  
So that I can view customer details

## Details

- Retrieve account by ID

## Acceptance Criteria

- [ ] Given a valid account ID
- [ ] When I send a GET request to /accounts/{id}
- [ ] Then I should receive account details

- [ ] Given an invalid ID
- [ ] When I send a GET request
- [ ] Then I should receive a 404 error
