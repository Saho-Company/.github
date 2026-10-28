# .github

Shared defaults for every repository in the **Saho-Company** organization.

## What's inside

- `.github/pull_request_template.md` — the organization-wide pull request template. Any repo without its own template gets this one automatically when a pull request is opened.

## How it works

GitHub treats this repo as the fallback for community health files across the org. A repository's own files always win: if a repo has its own `pull_request_template.md`, that one is used instead of this one.

## The template at a glance

Every pull request is asked for a summary, the reason behind the change, the implementation changes, deployment notes (migrations, environment variables, workers, infrastructure), and risks or breaking changes, so reviewers get the full picture before they open the diff.

## Contributing

Change the template here and it rolls out to every repo that doesn't override it. Keep it short, keep it useful, and don't add a field nobody fills in.
