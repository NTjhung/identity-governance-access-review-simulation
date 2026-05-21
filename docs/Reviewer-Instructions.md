# Reviewer Instructions

## Purpose

This document explains how reviewers should evaluate user access during the manual access review. The goal is to confirm whether each user still needs access to the assigned Microsoft Entra ID security group.

## Reviewer Responsibilities

Reviewers are responsible for checking whether users still need access based on job role, department, project assignment, contractor status, and business need.

## Review Decision Options

| Decision | Meaning |
|---|---|
| Approve | The user still needs access |
| Remove | The user no longer needs access |
| Review Further | More information is needed before making a final decision |

## How to Review Access

For each user, review the following:

1. Does the user still work in the listed department?
2. Does the user's job title match the access they have?
3. Is the access required for their current role?
4. Is the user a contractor or temporary worker?
5. Is the group considered sensitive or privileged?
6. Is there a business reason to keep the access?
7. Should access be removed or reviewed further?

## Review Guidance by Group

### SG-HR-Employees

Review whether the user still works in HR or needs access to HR-related resources.

### SG-Finance-Employees

Review carefully because finance access may include sensitive financial information.

### SG-IT-Admins

Review carefully because IT admin access may allow elevated permissions.

### SG-Contractors

Review carefully because contractor access should be time-limited and removed when no longer needed.

## Example Decisions

| User | Group | Decision | Reason |
|---|---|---|---|
| Alice Johnson | SG-HR-Employees | Approve | User works in HR and access matches role |
| Dana Smith | SG-Contractors | Remove | Contractor access should be removed after project completion |
| Carlos Ramirez | SG-IT-Admins | Review Further | Privileged access requires manager confirmation |

## Notes for Reviewers

- Do not approve access automatically.
- Remove access if there is no clear business need.
- Mark access as Review Further if you are unsure.
- Privileged and contractor access should receive extra attention.
- All decisions should be documented for audit evidence.
