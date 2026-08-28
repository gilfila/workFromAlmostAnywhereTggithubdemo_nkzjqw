# CLAUDE.md — githubdemo

## Purpose
Demo of keeping a Workday Extend app under GitHub version control. Contains the Extend app **"Work From Almost Anywhere TGGithubDemo"** (reference ID `workFromAlmostAnywhereTggithubdemo_nkzjqw`) — a remote-work request/approval app (requests, manager review, calendar, days chart, right-to-work attachments).

## Stack
Workday Extend source: `.pmd`/`.amd`/`.smd` presentation files, `.pod`/`.card`/`.script`/`.wqlquery` assets, model files (`.businessobject`, `.businessprocess`, `.task`, `.report`, `.securitydomain`, `.attachment`). No local build — deploy via Workday Extend tooling against the dev tenant.

## Structure
Single app folder `workFromAlmostAnywhereTggithubdemo_nkzjqw/` — see `README.md` for the layout.

## Conventions
- Repo name matches the app's reference ID on GitHub (account `gilfila`).
- Keep secrets out of the repo (`.env` gitignored); app files carry no credentials — keep it that way when adding API endpoints/orchestrations.

## Last turn / Pending (2026-08-28)
Initialized git and published the app to GitHub as a private repo `workFromAlmostAnywhereTggithubdemo_nkzjqw` under `gilfila`, with README/CLAUDE.md/.gitignore added. Secrets/PII sweep was clean. Then added a sample **About page** (`presentation/about.pmd`, routed at `/about` via the AMD) on branch `feature/about-page`, pushed to GitHub. **Pending:** open/merge the PR for `feature/about-page` (this CLAUDE.md update is uncommitted on that branch); flip the repo to public if Tony wants it shareable.
