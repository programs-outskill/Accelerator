# Kanban Board

## What This Is

A fast, minimal kanban task manager for engineering teams. Built to replace Notion boards — focuses on smooth task flow without the setup overhead. Start as a personal dogfooding tool, then hand off to a small team (2-5 people).

## Core Value

Moving engineering tasks through stages (Backlog → Done) must feel instant and frictionless — if dragging a card or scanning the board feels slow, nothing else matters.

## Requirements

### Validated

(None yet — ship to validate)

### Active

- [ ] Single kanban board with 5 columns: Backlog, To Do, In Progress, Review, Done
- [ ] Task cards with title, description, priority, assignee, and due date
- [ ] Drag-and-drop to move tasks between columns
- [ ] Filter tasks by assignee, priority, or search by title
- [ ] Data persisted in browser local storage
- [ ] Create, edit, and delete tasks
- [ ] Visual priority indicators on cards (e.g., color-coded)

### Out of Scope

- Backend / API / database — deferred to team rollout phase
- Authentication / user accounts — not needed for local-first v1
- Multiple boards — single board is sufficient for v1
- Real-time collaboration — requires backend, deferred
- Notifications — no backend to push from
- Mobile-native app — web-first

## Context

- Replacing Notion boards for engineering task management
- Pain points with Notion: poor task flow (clunky drag-drop), too much setup/configuration
- Will dogfood personally before rolling out to team of 2-5
- Engineering tasks: tickets, bugs, features, sprint work
- Team rollout will require backend + auth (future milestone)

## Constraints

- **Tech stack**: React — user preference
- **Storage**: Local storage for v1 — no backend infrastructure
- **Scope**: Simple version first — resist feature creep
- **Users**: Single user for v1 (assignee field is for labeling, not auth)

## Key Decisions

| Decision | Rationale | Outcome |
|----------|-----------|---------|
| Local storage over backend | Ship fast, dogfood first, add backend when team needs it | — Pending |
| Single board | Keeps v1 simple, multiple boards adds routing/state complexity | — Pending |
| React (not Next.js) | No backend needed for v1, pure frontend is simpler | — Pending |
| 5-column flow | Matches existing engineering workflow (Backlog → To Do → In Progress → Review → Done) | — Pending |

---
*Last updated: 2026-02-10 after initialization*
