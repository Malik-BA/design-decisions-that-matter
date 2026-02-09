# ADR-001: Authentication Strategy

## Context
The platform supports high-volume user access with varying risk profiles.

## Options considered
1. Password-only authentication
2. Mandatory MFA for all users
3. Risk-based authentication

## Decision
Adopt risk-based authentication with mandatory MFA for high-risk actions.

## Consequences
- Improved user experience for low-risk sessions
- Increased system complexity
- Reduced account takeover risk
