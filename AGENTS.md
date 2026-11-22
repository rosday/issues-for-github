# Repository instructions

**New issue intake (Rodrigo, 2026-11-14).** New issues added to an app board in **Triage** have no `Version` unless the user explicitly asks for one. Do not choose the highest backlog/planned version, infer a target from a parent, dates or the current release, or attach a version-derived release parent without that request. Preserve existing issues and their saved versions/parents; this rule does not authorize clearing or changing them. When a Version is explicitly assigned, the existing Version-to-parent sync may align its mapped release parent.

## Syncing with upstream

Bring in changes from `upstream/main` while preserving this fork's Projects inspector and Mac sidebar. Change the behaviors below only when Rodrigo explicitly requests it.

- **Projects in the Mac issue inspector.** Give each open project an issue belongs to its own collapsible section. Each section starts expanded and shows all supported fields, including empty ones. Keep the controls to edit fields and add or remove project memberships.
- **Projects in the Mac navigation sidebar.** List every open, visible project as a selectable row under **Projects**, as on iPad. Selecting a project opens its last-used view and shows its All Issues, views and milestones below. Keep hidden projects accessible from the expandable row in the same section.

Carry these behaviors forward when resolving conflicts or adapting the fork to upstream code. Verify the affected behavior whenever an upstream sync touches either surface.
