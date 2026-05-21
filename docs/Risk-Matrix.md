# Access Review Risk Matrix

## Purpose

This risk matrix helps prioritize access review decisions based on the sensitivity of the group, the type of access, and the potential impact if access is misused.

## Risk Levels

| Risk Level | Meaning |
|---|---|
| Low | Access has limited impact and low sensitivity |
| Medium | Access may include sensitive business or employee data |
| High | Access may include financial, contractor, or privileged access |
| Critical | Access may allow broad administrative control or major business impact |

## Group Risk Ratings

| Group | Access Type | Risk Level | Reason |
|---|---|---|---|
| SG-HR-Employees | HR department access | Medium | HR data may contain employee information |
| SG-Finance-Employees | Finance department access | High | Finance data may include payment and financial records |
| SG-IT-Admins | Privileged IT access | High | IT admin access may allow elevated permissions |
| SG-Contractors | Contractor access | High | Contractor access should be limited and time-bound |
| SG-Sales-Employees | Sales department access | Low | Sales access is lower risk in this lab scenario |

## Risk-Based Review Guidance

### Low Risk

Low-risk access can be reviewed quarterly or semi-annually depending on company policy.

### Medium Risk

Medium-risk access should be reviewed at least quarterly or semi-annually, especially when it involves employee or customer information.

### High Risk

High-risk access should be reviewed more frequently. This includes finance access, contractor access, and privileged access.

### Critical Risk

Critical access should require strict controls, approval, monitoring, and frequent review.

## Review Priority

| Priority | Group | Reason |
|---|---|---|
| 1 | SG-IT-Admins | Privileged access should be reviewed first |
| 2 | SG-Contractors | Contractor access should be time-limited |
| 3 | SG-Finance-Employees | Finance access is sensitive |
| 4 | SG-HR-Employees | HR access may include employee data |
| 5 | SG-Sales-Employees | Lower-risk department access |

## Summary

Risk-based review helps IAM teams focus on the most sensitive access first. Privileged, contractor, finance, and HR access should receive more attention than standard low-risk access.
