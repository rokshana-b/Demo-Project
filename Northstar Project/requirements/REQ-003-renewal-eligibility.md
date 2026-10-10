# REQ-003: Check Renewal Eligibility

**Status:** Draft  
**Priority:** Medium  
**Area:** Renewal

## User story
As a Service Representative, I want to see whether a policy is eligible for renewal so that I can explain the next step to the customer.

## Acceptance criteria
1. Active policies within the fictional renewal window are marked `Review`.
2. Cancelled policies are marked `Not Eligible`.
3. Policies outside the renewal window are marked `Not Yet Eligible`.
4. Users without policy-view permission cannot retrieve renewal details.
5. The displayed result includes a short reason.
