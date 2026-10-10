# Manual test cases

All values refer to the fabricated records in `../test-data/quote-scenarios.csv`. Pass/fail outcomes in the report are illustrative.

| ID | Requirement | Scenario | Steps | Expected result |
|---|---|---|---|---|
| TC-001 | REQ-001, REQ-003 | Complete valid quote | Enter HL-1001 and submit. | Estimate and unique quote reference appear. |
| TC-002 | REQ-001, REQ-002 | Missing garaging ZIP | Leave ZIP blank; complete other required values; submit. | Submission is stopped and a prompt identifies the missing ZIP. |
| TC-003 | REQ-002 | Invalid date of birth | Enter the sample invalid date from HL-1002 and submit. | Date prompt explains the accepted value. |
| TC-004 | REQ-004 | Eligible safe-driver discount | Enter HL-1003; inspect the breakdown. | Safe-driver discount appears once and total follows the sample rule. |
| TC-005 | REQ-004 | Eligible multi-vehicle discount | Enter HL-1004; inspect the breakdown. | Multi-vehicle discount appears once and total follows the sample rule. |
| TC-006 | REQ-005 | Accepted document | Attach a fictional PDF smaller than 5 MB. | File is accepted and shown as attached. |
| TC-007 | REQ-005 | Unsupported or oversized document | Try an unsupported type or a file larger than 5 MB. | File is rejected with a clear explanation. |
| TC-008 | REQ-006 | Review entered details | Complete valid values and open review. | Review shows entered vehicle and driver details; edit preserves remaining values. |
