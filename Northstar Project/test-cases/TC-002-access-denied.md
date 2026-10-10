# TC-002: Deny Quote Creation for Unauthorized Role

**Requirement:** REQ-001  
**Priority:** High  
**Type:** Negative / Authorization

## Preconditions
- User is signed in as a Service Representative.
- User does not have quote-creation permission.

## Steps
1. Navigate to the quote creation route.
2. Attempt to open the creation form.
3. Attempt submission if the form is accessible.

## Expected results
- The action is denied.
- No quote is created.
- The user sees a suitable access message.

## Sample result
Not executed — placeholder for demo.
