---
name: implement
description: "Implement a piece of work based on a spec or set of tickets."
disable-model-invocation: true
---

Implement the work described by the user in the spec or tickets.

Before you start, note the commit you are on: it is the fixed point for the review.

Use /tdd where possible, at pre-agreed seams.

Run typechecking and single test files regularly as you work.

Once done, commit your work to the current branch. Then use /code-review to review it against the commit you noted.

Apply the review's fixes, re-running the affected single test files: a fix is a change like any other, so the full suite must cover it too.

Then run the full test suite once and commit the fixes. If the review found nothing to fix, still run it; there is just nothing more to commit. Report the full suite's result together with the commit it ran against.
