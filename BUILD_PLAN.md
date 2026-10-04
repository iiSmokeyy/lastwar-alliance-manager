# Sin Command Center

This branch is the customized alliance-management build based on Last War Alliance Manager.

## Goal
Turn the existing application into an R5 command center while preserving the stable member, permissions, event, OCR, VS, scheduling, and SQLite foundations.

## Phase 1 — Foundation
- Preserve existing authentication and role permissions.
- Preserve current member CRUD and event systems.
- Rebrand the management shell as **Command Center**.
- Add a dashboard entry point without deleting existing tools.
- Keep upstream `main` untouched while development happens on `sin-command-center`.

## Phase 2 — Transfer & Recruitment
- Transfer applicant roster.
- Seat classes: Purple, Blue, White.
- Priority / If Possible / Unassigned status.
- Destination group/alliance assignment.
- Seat capacity counters.
- Application/activity notes and decision status.

## Phase 3 — Leadership
- R4 responsibility board.
- Leadership notes and role assignments.
- Alliance/server diplomacy records.
- Merge planning.

## Phase 4 — Events
- Desert Storm A/B team planning.
- Canyon Storm planning.
- Stage assignments and substitutes.
- Reusable battle-plan views.

## Phase 5 — Operations
- Activity and participation dashboard.
- Alliance message/mail generator.
- Season planning and accountability.
- Mobile-friendly R5 overview.

## Development policy
The original fork's `main` branch remains the clean upstream baseline. Customized work is developed on this branch and can be reviewed before merging.
