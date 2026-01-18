# Identity Lifecycle Management (Joiner–Mover–Leaver)

## Overview
This project explores how user access is managed throughout an employee’s lifecycle using Microsoft Entra ID. I focused on the practical, day-to-day steps involved in onboarding users, updating access when roles change, and removing access when someone leaves an organization.

## Purpose
The goal of this project was to better understand how proper identity lifecycle management helps keep systems secure and prevents users from having access they no longer need.

## Tools Used
- Microsoft Entra ID (Azure AD)
- Security Groups
- Role-Based Access Control (RBAC)

## Project Scope
This project was completed using a personal Entra ID tenant and test user accounts only. All users and scenarios are simulated, and no real or sensitive data is included.

## Joiner: User Onboarding
I created test user accounts and assigned them to role-based security groups. This ensured each user only received access necessary for their role, following the principle of least privilege.

## Mover: Role Changes
To simulate a role change, I updated group memberships and removed permissions that were no longer appropriate. This helped prevent access from slowly accumulating over time.

## Leaver: User Offboarding
When simulating a user departure, I disabled the account and removed group memberships to ensure access was fully revoked and could no longer be used.

## Why This Matters
Managing user access correctly is one of the simplest but most important parts of security. Small oversights, like forgetting to remove access, can create real risks. This project helped me see how even basic identity tasks play a major role in protecting systems.

## What I Learned
Through this project, I gained hands-on experience with identity lifecycle workflows and a deeper appreciation for how identity management supports overall security. It reinforced how important accuracy and timeliness are when managing access.
