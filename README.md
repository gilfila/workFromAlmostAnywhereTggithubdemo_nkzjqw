# Work From Almost Anywhere TGGithubDemo

A Workday Extend demo app for requesting and managing "work from almost anywhere" (remote work) requests. This repo demonstrates keeping an Extend app's source under GitHub version control.

## What the app does

- Employees submit remote-work requests (single page, wizard, or quick-add flows) with country selection, date ranges, and right-to-work verification uploads.
- Managers review, approve, or send back requests via a manage-requests hub.
- A calendar view and days chart visualize approved remote-work time.

## Structure

```
workFromAlmostAnywhereTggithubdemo_nkzjqw/
├── appManifest.json        # App identity (name, reference ID, version)
├── model/                  # Business objects, business process, tasks, report, security domains
├── presentation/           # Pages (.pmd), app/site definitions (.amd/.smd), pods, cards, scripts, WQL queries
├── cards/                  # Workday cards (card definitions + tenant settings)
├── attributes/             # Default attributes
└── images/                 # App thumbnails
```

## Working with it

Edit the source here, then deploy through Workday Extend tooling (App Builder / `wcloud`) against your Extend developer tenant. The app's reference ID is `workFromAlmostAnywhereTggithubdemo_nkzjqw`.
