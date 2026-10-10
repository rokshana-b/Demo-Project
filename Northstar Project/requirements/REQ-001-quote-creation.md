# REQ-001: Create a Quote

**Status:** Draft  
**Priority:** High  
**Area:** Quote

## User story
As an Underwriter, I want to create a quote with the required policy details so that I can review coverage before issuing a policy.

## Acceptance criteria
1. Given a user with quote-creation permission, when all required fields are valid, then the system saves the quote.
2. Given a required field is missing, when the user submits the form, then the system identifies the missing field.
3. Given a user without quote-creation permission, when they attempt to create a quote, then the system denies the action.
4. A newly created quote receives a unique fictional quote reference.

## Notes
This is demo-only behavior. Detailed state rules are intentionally simplified.
