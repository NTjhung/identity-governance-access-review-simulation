# Access Review Plan

## Purpose

This document defines the plan for a manual identity governance access review. The goal is to confirm that users still need access to selected Microsoft Entra ID security groups and to document reviewer decisions for audit evidence.

## Review Type

Manual group membership access review.

## Review Scope

The following groups are included in this review:

| Group | Reason for Review | Risk Level |
|---|---|---|
| SG-HR-Employees | HR data may contain sensitive employee information | Medium |
| SG-Finance-Employees | Finance data may contain payment and financial records | High |
| SG-IT-Admins | IT admin access may allow elevated permissions | High |
| SG-Contractors | Contractor access should be time-limited and reviewed often | High |

## Review Goals

The goals of this access review are to:

1. Confirm that users still need their assigned access.
2. Identify users who should be removed from groups.
3. Identify privileged access that needs additional validation.
4. Document reviewer decisions.
5. Track remediation actions.
6. Collect evidence for audit readiness.

## Review Frequency

Recommended frequency:

| Group Type | Review Frequency |
|---|---|
| Standard department groups | Quarterly or semi-annually |
| Finance and HR groups | Quarterly |
| Contractor groups | Monthly or quarterly |
| Privileged admin groups | Monthly or quarterly |

## Reviewers

| Group | Reviewer |
|---|---|
| SG-HR-Employees | HR Manager |
| SG-Finance-Employees | Finance Manager |
| SG-IT-Admins | IT Manager |
| SG-Contractors | Project Owner |

## Review Decision Options

Reviewers can choose one of the following decisions:

| Decision | Meaning |
|---|---|
| Approve | User still needs access |
| Remove | User no longer needs access |
| Review Further | More information is needed before deciding |

## Remediation Process

If a reviewer marks access as **Remove**, the IAM team should:

1. Confirm the reviewer decision.
2. Remove the user from the group.
3. Document the removal date.
4. Save evidence of the change.
5. Update the remediation tracker.

If a reviewer marks access as **Review Further**, the IAM team should:

1. Contact the manager or system owner.
2. Confirm whether access is still needed.
3. Update the final decision.
4. Document the reason.

## Evidence to Collect

The following evidence should be collected:

- Group membership screenshots
- Sample access review data
- Reviewer decision table
- Remediation tracker
- Final audit evidence packet

## Final Output

At the end of the review, the project should include:

- Access review plan
- Reviewer instructions
- Remediation tracker
- Risk matrix
- Audit evidence packet
- Screenshots of reviewed groups
