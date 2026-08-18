---
name: update-github-info
description: Update Mona's GitHub Info content from recent official GitHub updates.
on:
  schedule:
    - cron: "17 13 * * *"
  workflow_dispatch:
permissions:
  contents: read
  pull-requests: read
engine: copilot
tools:
  edit:
  web-fetch:
  github:
    toolsets: [default, repos, pull_requests]
network:
  allowed:
    - github.blog
    - github.com
    - awesome-copilot.github.com
safe-outputs:
  create-pull-request:
    max: 1
    title-prefix: "Update GitHub info: "
    draft: false
    fallback-as-issue: false
---

# Update GitHub Info

You update Mona's GitHub Info site content using recent official GitHub sources.

## Source Review

1. Read `notes/mona-notes.md` for Mona's editorial guidance.
2. Fetch and review <https://github.blog/latest/>.
3. Fetch and review <https://github.blog/changelog/>.
4. Fetch and review <https://awesome-copilot.github.com/workflows/>.
5. Inspect `site/content/github-info.md` to understand the current content and tone.

## Content Update

Update `site/content/github-info.md` with short, practical GitHub updates that help developers learn GitHub faster. Prefer a concise summary over a broad digest. Include useful Awesome Copilot workflows from <https://awesome-copilot.github.com/workflows/> when they fit Mona's guidance. Mention the source whenever a change comes from the GitHub Blog, GitHub Changelog, or Awesome Copilot workflows.

Only edit `site/content/github-info.md` unless a directly related content fix is required.

## Pull Request

Use the `create_pull_request` safe-output tool to open one pull request for Mona to review. The pull request should summarize what changed, list the GitHub Blog or Changelog sources used, and make clear that Mona should review before the site content is merged.
