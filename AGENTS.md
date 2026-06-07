# ZAM Community Instance

This repository is a shared ZAM context for a team, open-source project,
professional association, or other purposeful community.

## First Time Here

Invoke `$setup` or select `setup` through `/skills`. The setup workflow reads
`.zam/config.yaml`, installs dependencies, distributes ZAM skills, and clones or
links the configured source repositories.

## Regular Use

Invoke `$zam` or select `zam` through `/skills` to start a learning session in
this community context. Codex repository skills live under `.agents/skills/`;
they are not custom slash commands.

## Repository Contents

- `beliefs/` contains the community's shared worldview.
- `goals/` contains shared objectives and learning work.
- `members/` describes membership and roles.
- `.zam/config.yaml` declares community identity and related repositories.

Every committed change is part of the community's approval trail.
