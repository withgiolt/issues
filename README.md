# Giolt Issue Tracker

Central issue tracker for [Giolt](https://giolt.com) — a hosting and
deployment platform for [Gleam](https://gleam.run). Every repository under
the [`withgiolt`](https://github.com/withgiolt) organization files its bugs,
feature requests, and questions here instead of in its own tracker.

## Why one repo?

Giolt is split across several repositories. Splitting issues the same way
makes it hard to see the whole picture, duplicates triage effort, and makes
it easy to miss a report because it landed in the "wrong" repo. Filing
everything here instead means one place to search before opening a new
issue, one backlog to triage against, and no guessing which repo a
cross-cutting problem belongs in.

## Projects covered

Each issue template asks which project it's about:

- **giolt** — the core platform
- **cli** — the Gleam CLI for building with Giolt
- **glowvm** — the BEAM/Erlang runtime
- **docs** — documentation

If you're not sure which one your issue belongs to, take your best guess —
triage will sort it out.

## Before opening an issue

1. **Search first**, including closed issues — it may already be reported
   or fixed.
2. **Check the [docs](https://docs.giolt.com)** in case the behavior is expected or already
   documented.
3. If you're reporting a deploy or runtime problem, grab the relevant
   deploy ID or logs — it saves a round trip.

## Filing an issue

Pick the template that fits: **Bug Report**, **Feature Request**, or
**Question / Support**. Each one asks which project it's about, plus the
details specific to that kind of report (repro steps for bugs, the
problem you're solving for feature requests, and so on). Blank issues are
also allowed for anything that doesn't fit those three shapes.

## Contributing

This repo is for issues only — pull requests go to the relevant project's
own repository. If you're picking up an issue, comment on it first so work
isn't duplicated.
