# Remediation Tracker

## Purpose

This tracker documents access review decisions and any remediation actions required after the review. Remediation may include removing a user from a group, validating privileged access, or confirming business need with a manager.

## Remediation Summary

| User | Group | Review Decision | Remediation Action | Status | Notes |
|---|---|---|---|---|---|
| Alice Johnson | SG-HR-Employees | Approve | None | Complete | Access matches HR Manager role |
| Grace Kim | SG-HR-Employees | Approve | None | Complete | Access matches Recruiting Specialist role |
| Brian Lee | SG-Finance-Employees | Approve | None | Complete | Finance access is appropriate |
| Henry Brown | SG-Finance-Employees | Approve | None | Complete | Access matches Accounts Payable role |
| Carlos Ramirez | SG-IT-Admins | Review Further | Validate admin need with IT Manager | Pending | Privileged access requires confirmation |
| Dana Smith | SG-Contractors | Remove | Remove from SG-Contractors | Pending | Contractor access should be time-limited |
| James Clark | SG-Contractors | Approve | None | Complete | Temporary access still needed for active project |
| Emma Wilson | SG-Sales-Employees | Approve | None | Complete | Access matches Sales role |

## Items Requiring Action

| User | Required Action | Owner | Due Date | Status |
|---|---|---|---|---|
| Carlos Ramirez | Confirm continued need for IT admin group access | IT Manager | TBD | Pending |
| Dana Smith | Remove from contractor access group | IAM Team | TBD | Pending |

## Remediation Process

1. Review all decisions marked Remove or Review Further.
2. Confirm the decision with the reviewer if needed.
3. Remove or update access in Microsoft Entra ID.
4. Save evidence of the change.
5. Update the remediation tracker.
6. Document final completion status.

## Audit Notes

The remediation tracker should be retained as part of the access review evidence package. It shows that review decisions were tracked and that risky or unnecessary access was identified for follow-up.
