# Security

## Reporting a vulnerability

**Use GitHub's private vulnerability reporting** — the *Report a vulnerability* button on the
Security tab of any repository in this organization. That opens a private advisory visible only to
the maintainer.

⛔ **Do not open a public issue for a security problem**, and please don't disclose it publicly
before it's fixed.

## What to expect

These are small, actively maintained projects with a single maintainer. Realistically:

- **Acknowledgement within 7 days.** If you haven't heard back by then, assume the notification
  was missed and ping again.
- **An honest assessment, including "this isn't a vulnerability."** If a report is declined you'll
  get the reasoning, not a form letter.
- **Credit in the advisory** unless you'd rather not be named.

There is no bug bounty.

## Scope

In scope: anything in a repository in this organization that could expose a user's data, execute
unintended code on their machine, or misrepresent what the software is doing.

Out of scope: findings from automated scanners with no demonstrated impact, and issues in
third-party dependencies that are already public — report those upstream.

## A note on what these projects claim

Several of these tools make explicit claims about what they do *not* do — no telemetry, no network
calls beyond ones you enabled. **A demonstrated violation of a stated guarantee is a security
report, not a bug report**, and it will be treated as one.
