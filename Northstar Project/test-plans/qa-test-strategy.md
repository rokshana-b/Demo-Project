# QA Test Strategy

## Purpose
Describe the lightweight testing approach for the Northstar demo.

## Test levels
- **Workflow testing:** validate quote, issuance, and renewal paths.
- **Negative testing:** submit incomplete or invalid information.
- **Authorization testing:** verify allowed and denied actions by role.
- **Regression testing:** rerun core scenarios after changes.

## Coverage dimensions
- Fictional state: Maple, Cedar, Harbor
- Role: Underwriter, Service Representative, QA Analyst
- Workflow: quote, issuance, renewal
- Outcome: positive, negative, boundary

## Entry criteria
- Requirement is available and has acceptance criteria.
- Demo environment is accessible.
- Test data is prepared.

## Exit criteria
- All high-priority scenarios are executed.
- Critical defects are resolved or explicitly accepted for the demo.
- Results and known limitations are documented.

## Risks and assumptions
- State-specific rules are placeholders.
- No external carrier APIs are connected.
- Sample results do not represent production behavior.
