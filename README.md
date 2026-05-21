# Identity Governance Access Review Simulation

## Project Overview

This project demonstrates a manual Identity Governance access review process. The lab simulates how an IAM team can review user access, collect reviewer decisions, track remediation, and prepare audit evidence.

This project does not require Microsoft Entra ID P1 or P2 licensing. Instead of using the built-in Microsoft Entra access review feature, this lab uses a manual access review process based on group membership exports, reviewer instructions, decision tracking, and remediation documentation.

## Business Problem

Organizations need to regularly confirm that users still require access to sensitive systems, groups, and applications. Without regular access reviews, users may keep access they no longer need, which increases security and audit risk.

## Tools Used

- Microsoft Entra ID
- Security groups
- Group membership review
- Manual access review process
- Markdown documentation
- GitHub
- Screenshots as audit evidence

## What This Project Demonstrates

- Identity governance concepts
- Manual access review process
- Least privilege review
- Group membership review
- Reviewer decision tracking
- Access remediation planning
- Audit evidence documentation
- IAM documentation

## Groups Reviewed

The simulated access review focuses on the following groups:

- SG-HR-Employees
- SG-Finance-Employees
- SG-IT-Admins
- SG-Contractors

## Review Scope

The review evaluates whether users still need access based on:

- Department
- Job role
- Contractor status
- Privileged access risk
- Business need
- Least privilege

## Project Files

- docs/
- sample-data/
- screenshots/

## Documentation Created

- docs/Access-Review-Plan.md
- docs/Reviewer-Instructions.md
- docs/Remediation-Tracker.md
- docs/Audit-Evidence-Packet.md
- docs/Risk-Matrix.md
- sample-data/access-review-users.csv

## Key IAM Concepts Demonstrated

### Access Reviews

Access reviews help organizations confirm that users still need access to systems, groups, and applications.

### Least Privilege

Least privilege means users should only have the access required for their job responsibilities.

### Remediation

Remediation is the process of removing, updating, or correcting access after a review decision.

### Audit Evidence

Audit evidence includes screenshots, exports, review decisions, and remediation records that prove the review was completed.

## Resume Bullet

- Built a manual identity governance access review simulation for Microsoft Entra ID groups, including reviewer instructions, access review planning, remediation tracking, least privilege analysis, and audit evidence documentation.

## Status

In progress. This project will be updated with access review documentation, sample review data, screenshots, and final remediation results.
