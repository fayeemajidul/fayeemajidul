## Majidul Mooktadeer

Stealth Start Up Developer and Professional QA Automation Engineer. I build test frameworks, and I build them in public.


### Now building

| Month | Framework | Target | Nightly | Report |
|---|---|---|---|---|
| Sep 2026 | [Playwright with TypeScript](https://github.com/fayeemajidul/playwright-ts-automationexercise) | automationexercise.com | [![nightly](https://github.com/fayeemajidul/playwright-ts-automationexercise/actions/workflows/nightly.yml/badge.svg)](https://github.com/fayeemajidul/playwright-ts-automationexercise/actions/workflows/nightly.yml) | [latest](https://fayeemajidul.github.io/playwright-ts-automationexercise/latest/) |

### Shipped

_The first framework completes at the end of September 2026._

### How I work

Page objects that never assert. An API layer for setup, so tests exercise the
thing they are actually testing. Structured logs, because a failure you did not
watch happen is only as debuggable as its evidence. Retries with a hard cap and a
record, never as a way to hide a race. Typed environment config that fails fast.
A hosted report with history. And a nightly run that keeps all of it honest.

A skip is not a pass.

### On the automation

The daily engineering in these repos is AI assisted and reviewed by me. I am
saying so plainly because a portfolio that hides how it was made is not worth
much. Each repo carries a `docs/HOW_THIS_REPO_IS_BUILT.md` explaining exactly
what runs, what it is forbidden from doing, and how a day's work is rejected if
it is not real. The machinery is public in
[qa-framework-template](https://github.com/fayeemajidul/qa-framework-template),
including the guard script that refuses empty diffs, silently skipped tests, and
vague commit messages.

### Also here

- [Countries-GraphQL-Framework](https://github.com/fayeemajidul/Countries-GraphQL-Framework), a GraphQL API test suite with a shared request layer and a written test strategy
- [Teams-App-Status](https://github.com/fayeemajidul/Teams-App-Status), scheduled Microsoft Teams status on macOS with no Graph API
