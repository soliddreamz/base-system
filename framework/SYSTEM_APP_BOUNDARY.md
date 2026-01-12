# Base System — System vs App Boundary

This document defines the separation of responsibility
between the Base system and applications built on Base.

This boundary is intentional and enforced.

---

## What Belongs in Base (System Layer)

Base is responsible for:
- Core principles and rules
- UI & behavior constraints
- Navigation model
- Component definitions
- Accessibility baseline
- Predictable system behavior

Base MAY include:
- Reference specifications
- Abstract component contracts
- Compatibility requirements

Base MUST remain:
- Stable
- Minimal
- Opinionated
- Hard to change

---

## What Does NOT Belong in Base

Base does NOT include:
- App-specific content
- Creator branding
- Media assets
- Business logic
- Monetization strategies
- Advertising implementations
- Analytics or tracking

Base never contains:
- Artist names
- Brand-specific language
- App copy
- Pilot code

---

## What Belongs in Apps (Pilot / App Layer)

Applications are responsible for:
- Content
- Branding
- Media
- Copy
- External links
- Creator-specific workflows
- Monetization choices

Apps MAY:
- Customize appearance
- Choose business models
- Evolve independently

Apps MUST:
- Follow Base rules
- Respect locked constraints
- Remain compatible

---

## Enforcement

An application that violates Base rules:
- Is not considered Base-compatible
- May not claim Base usage
- Is outside the system boundary

---

## Status

This document is LOCKED.
Changes require system-level approval.
