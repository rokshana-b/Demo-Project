# User stories

## US-001: Receive an estimate

As a prospective customer, I want to enter vehicle and driver information and see an estimate, so I can decide whether to continue.

**Acceptance criteria**

- Given all required values are valid, when I submit the quote, then I see an estimated premium and quote reference.
- Given a required value is missing or invalid, when I submit, then I see a useful prompt by that field.

**Related requirements:** REQ-001, REQ-002, REQ-003

## US-002: Understand eligible discounts

As a prospective customer, I want eligible discounts listed in the estimate breakdown, so I can understand the sample price.

**Acceptance criteria**

- An eligible safe-driver discount is named in the breakdown.
- An eligible multi-vehicle discount is named in the breakdown.
- The displayed total matches the fictional rules in the test plan.

**Related requirements:** REQ-004

## US-003: Attach a supporting document

As a prospective customer, I want to attach an accepted document, so the demo quote can record supporting information.

**Acceptance criteria**

- PDF, JPG, and PNG files no larger than 5 MB are accepted.
- Unsupported or oversized files show a clear prompt.

**Related requirements:** REQ-005

## US-004: Review my details

As a prospective customer, I want to review the information I entered, so I can spot a mistake before continuing.

**Acceptance criteria**

- The review screen shows the entered vehicle and driver details.
- Returning to edit preserves the other valid values.

**Related requirements:** REQ-006
