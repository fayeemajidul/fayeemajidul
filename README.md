## Majidul Mooktadeer

Stealth Start Up Developer and Professional QA Automation Engineer. I build test frameworks, and I build them in public.


### Projects

**[Recrewit AI](https://recrewit.ai)** is AI screening for recruiting teams, so a
recruiter who is not technical can still hire engineers well. A role is posted
once and goes out to Indeed, LinkedIn and Dice. Every applicant is read and scored
against that specific role rather than matched against a keyword list, and strong
candidates carry on into a proctored technical interview.

The scoring is the part I care about most. Every score is transparent and
auditable, so a recruiter can see exactly why a candidate rose. The model judges
technical fit and nothing else. Culture fit stays with the recruiter, and a person
always makes the final call. Next.js, TypeScript, Supabase and the Anthropic API.

**Bear Macro** is a native macOS automation tool for a game, written in Swift. It
reads the screen with ScreenCaptureKit and finds state through structural pixel
detection rather than brittle image matching, then drives a proportional derivative
controller to hold a moving target. Ships as a signed disk image.

**CandewitGPT** is a job application autopilot that runs unattended on Fly.io.
Python, containerised, with a real CI pipeline. It drafts and queues applications
but will not send anything until I approve it from Slack, which is the whole point.

**[QA framework programme](https://github.com/fayeemajidul/qa-framework-template)**
builds one automation framework per month, one reviewed commit per day, entirely
on GitHub Actions. The machinery is the interesting part. The agent that writes the
daily work is forbidden from using git, and a guard script rejects anything that is
not real engineering before it can become a commit. September is
[Playwright with TypeScript](https://github.com/fayeemajidul/playwright-ts-automationexercise).

**[Countries GraphQL Framework](https://github.com/fayeemajidul/Countries-GraphQL-Framework)**
is a GraphQL API test suite with a shared request layer, schema introspection
assertions, and a written test strategy rather than just a folder of tests.

**WHOOP dashboard** is an open source dashboard that pulls WHOOP recovery and strain
data together with Apple Health, because neither app shows the two side by side.

**Westchester auction screener** is a due diligence tool for New York foreclosure
auctions. The interesting work is the lien survival rules, which decide whether a
debt disappears at auction or follows the buyer home.

**SHProperty** is a short stay rental site prototype in TypeScript, tested with
Playwright and Vitest.

### How I work

Page objects that never assert. An API layer for setup, so tests exercise the
thing they are actually testing. Structured logs, because a failure you did not
watch happen is only as debuggable as its evidence. Retries with a hard cap and a
record, never as a way to hide a race. Typed environment config that fails fast.

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
