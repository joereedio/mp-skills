---
name: implement
description: "Implement a piece of work based on a spec or set of tickets."
disable-model-invocation: true
---

Implement the work described by the user in the spec or tickets.

Use /tdd where possible, at pre-agreed seams.

Run typechecking and single test files regularly as you work.

Once done, commit your work to the current branch. Then use /code-review to review it against the commit you started from.

Apply the review's fixes, re-running the affected single test files: a fix is a change like any other.

Then run the full test suite once, so it covers exactly what gets committed, and commit the fixes. Report the full suite's result together with the commit it ran against.
