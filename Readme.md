# CodeTalks Introduction

CodeTalks is an offline-first VS Code extension for managing project-scoped
**Work Items**. Capture work while coding, organize it on a Kanban board, and
connect it to your GitLab or GitHub project.

See [CodeTalks Features](features.md) for the full list of supported features.

## Why CodeTalks?

Keep track of work discovered during coding, debugging, or AI chat sessions
without leaving your editor. Each workspace can be associated with a configured
project, keeping its board focused on the relevant work.

## Work in your editor

- Organize Work Items across **Backlog**, **Ready**, **In Progress**, **In Review**, and **Done**.
- Create and edit titles, descriptions, assignees, priorities, tags, and planning dates.
- Save work locally, including when remote creation is unavailable.
- See which items are waiting to sync.

## Connect to GitLab or GitHub

Create remote Work Items and refresh your board from the configured provider
using **CodeTalks: Sync From Remote**. Supported fields and editing behavior
vary by provider; see the [provider support and limitations](features.md#git-provider-support).

## Current availability

The VS Code extension is the primary client. An experimental mobile PWA is in
development, but it is not yet at feature parity and should not be treated as a
fully synchronized companion client.

Comment contents are not synchronized. GitHub edits made in CodeTalks currently
remain local and can be overwritten by a later refresh; GitLab edits are sent
to GitLab.
