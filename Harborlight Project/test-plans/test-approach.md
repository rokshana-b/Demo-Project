# Test approach

## Objective

Demonstrate a lightweight manual QA approach for the fictional Harborlight auto quote pilot.

## Coverage

- Required field validation and correction.
- Estimate and reference display.
- Fictional discount eligibility and breakdown.
- Document type and size handling.
- Review screen content and navigation.

## Method

Run the cases in `../test-cases/manual-test-cases.md` using the fabricated rows in `../test-data/quote-scenarios.csv`. Record Pass, Fail, or Blocked and a short note. Link failures to GitHub Issues.

## Entry conditions

- Requirements and test cases are available for review.
- The demo environment or screen mock is available (this repository does not include one).
- Test records use only the fabricated sample values.

## Exit conditions

- All high-priority cases have a recorded result.
- Failures have a linked issue or a documented reason for deferral.
- A short summary is published in `../reports/test-summary.md`.

## Risks and assumptions

- No application is supplied, so execution results are illustrative unless you pair this repository with a separate demo screen.
- Discount percentages and upload rules are sample-only business rules.
- Dates, identities, ZIP codes, and premium values are fictional.
