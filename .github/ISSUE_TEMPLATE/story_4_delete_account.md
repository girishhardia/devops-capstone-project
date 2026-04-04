---
name: "Story 4 — Delete Account"
about: "Delete a Customer Account"
labels: feature
---

# Story 4 — Delete Account

**As a customer service representative**  
I need to delete a customer account  
So that I can remove inactive customers

## Details

- Delete account by ID

## Acceptance Criteria

- [ ] Given a valid account ID
- [ ] When I send a DELETE request to /accounts/{id}
- [ ] Then the account should be deleted

- [ ] Given an invalid ID
- [ ] When I send a DELETE request
- [ ] Then I should receive a 404 error
