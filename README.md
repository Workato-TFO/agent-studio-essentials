# Agent Studio Essentials — Lab Guide

A practical lab for building an IT-support Genie in Workato Agent Studio.
Served via GitHub Pages from the `docs/` folder (branch `main`, folder `/docs`).

## Lab

| Lab | Tier | Time |
|---|---|---|
| [Build your first Genie in Agent Studio](docs/index.html) | Foundational | 120 minutes |

You'll stand up a Genie, open it to end users, ground it in a knowledge base,
explore a Kanban ticket tracker, and give the Genie skills to create, retrieve,
and list tickets on a user's behalf.

## Structure

- `docs/` — the published surface: the self-contained lab page (Pages source)

- Every commit is checked by the publish guard workflow
  (`.github/workflows/publish-guard.yml`); the same checks run locally as a
  pre-push hook — enable once per clone with:

```
git config core.hooksPath .githooks
```

## Contributing

Content is authored and reviewed elsewhere; this repo holds only pressed,
vetted output. Do not edit the lab HTML in place — changes land as a fresh
press of the whole bundle.
