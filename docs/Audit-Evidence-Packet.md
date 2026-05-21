# Audit Evidence Packet

## Purpose

This document summarizes the evidence collected for the manual identity governance access review simulation. The goal is to show that the access review was planned, documented, reviewed, and tracked for remediation.

## Evidence Included

The evidence packet includes:

1. Access review plan
2. Reviewer instructions
3. Sample access review data
4. Remediation tracker
5. Risk matrix
6. Group membership screenshots
7. Final review summary

## Review Scope

The access review covered the following Microsoft Entra ID security groups:

| Group | Risk Level | Reviewer |
|---|---|---|
| SG-HR-Employees | Medium | HR Manager |
| SG-Finance-Employees | High | Finance Manager |
| SG-IT-Admins | High | IT Manager |
| SG-Contractors | High | Project Owner |

## Evidence File List

| Evidence Item | File Location |
|---|---|
| Access Review Plan | docs/Access-Review-Plan.md |
| Reviewer Instructions | docs/Reviewer-Instructions.md |
| Remediation Tracker | docs/Remediation-Tracker.md |
| Risk Matrix | docs/Risk-Matrix.md |
| Access Review User Data | sample-data/access-review-users.csv |
| Screenshots | screenshots/ |

## Sample Review Results

| Decision | Count |
|---|---|
| Approve | 6 |
| Remove | 1 |
| Review Further | 1 |

## Items Requiring Follow-Up

| User | Group | Required Action |
|---|---|---|
| Carlos Ramirez | SG-IT-Admins | Validate continued need for privileged access |
| Dana Smith | SG-Contractors | Remove contractor access |

## Audit Summary

The simulated access review identified two items requiring follow-up:

1. One privileged access assignment requires additional validation.
2. One contractor access assignment should be removed.

This shows how an IAM team can use access reviews to identify unnecessary access, reduce risk, and support least privilege.

## Final Statement

This manual access review simulation demonstrates an identity governance process that can be used when built-in access review tools are unavailable or when a company needs a documented manual review process for audit readiness.
