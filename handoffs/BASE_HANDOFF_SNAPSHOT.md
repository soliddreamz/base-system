# BASE SYSTEM — HANDOFF SNAPSHOT (CURRENT STATE)

Owner: William Smith McClinton
Repo: base-system (public)
Purpose: Base — Creator-Owned App System (Core Framework)

---

## What Base Is
Base is a creator-owned application system.
It protects creators from platform dependency by enforcing:
- structure over style
- predictable behavior
- non-algorithmic design principles
- clean separation between system and apps

ChatGPT is used as a drafting assistant only.
Base authority lives in this GitHub repo.

---

## Locked Authority Layer (DO NOT EDIT WITHOUT INTENT)

### Step 9 — Core Principles (LOCKED)
Location:
- core/base-principles.md

Defines:
- Creator-first
- Structure over style
- Ownership & portability
- Minimal surface area
- Quiet infrastructure
- Respect for culture

---

### Step 10 — UI & Behavior Constraints (LOCKED)
Location:
- core/base-ui-constraints.md

Defines:
- Locked navigation model
- Locked UI components (style allowed, structure not)
- No algorithmic feeds
- No forced ads
- Consistent system behavior
- Accessibility baseline

---

### Step 12 — System vs App Boundary (LOCKED)
Location:
- framework/SYSTEM_APP_BOUNDARY.md

Defines:
- What belongs in Base
- What must stay in apps/pilots
- Enforcement: violations are not Base-compatible

---

## Reference Layer (Non-rule index)

### Step 13 — Framework Index (Reference Only)
Location:
- framework/FRAMEWORK_INDEX.md

Purpose:
- Maps framework documents
- Adds no new rules

---

## Pilot Ecosystem (Existing repos; code stays separate)
Pilots exist as independent repositories under the same owner account.
Base does not store pilot code in this repo.

Known pilots:
- Pilot 1: base-dj-alamo
- Pilot 2: base-high-demand
- Pilot 3: base-skunk-munk-tv
- Pilot 4: base-meda-monsta
- Pilot 5: TheBeatList

(If a pilot map doc exists, it belongs in: pilots/PILOT_MAP.md)

---

## Folder Structure (base-system repo)
- core/       (locked authority docs)
- framework/  (system boundary + indexes)
- pilots/     (documentation only; no pilot code)
- apps/       (documentation only; no app code)
- handoffs/   (snapshots + continuity docs)

---

## What NOT to Do Next
- Do NOT move pilot code into base-system
- Do NOT refactor existing pilots yet
- Do NOT add new locked rules impulsively

---

## Next Step Options (choose one path)

### Path A — Documentation completion
- Create pilots/PILOT_MAP.md (if not already done)
- Create README upgrade (plain-language overview)

### Path B — Technical codification (later)
- Define locked UI component specs (Button/Card/List/Row)
- Define navigation contract
- Define “Base compatibility checklist” for pilots

### Path C — Governance & scaling
- Define versioning rules
- Define contribution rules (even if solo)
- Define public vs private split (principles public, runtime private)

---

## Status
Base authority layer complete through Step 13.
Snapshot created at Step 14.
