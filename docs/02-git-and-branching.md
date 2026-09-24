# Git & Branching Strategy
**Branch Naming Standard:** 
Always branch off main/master (or the repository's designated default branch) using structured prefixes:
  - Features: feature/#<id>-short-description (e.g., feature/#183-new-login-ui)
  - Bug Fixes: fix/#<id>-short-description (e.g., fix/#182-db-check-sqlite-crash)
  - Chores / Maintenance: chore/#<id>-short-description

**Local Pre-Flight Checks:**
* Run test suites, type-checkers, and linters locally before pushing changes.

**Pull Request Protocol:**
  - Summarize the architectural or functional change.
  - Provide step-by-step verification instructions (how to run, reproduce, or inspect the change in local or staging environments).
  - Link the issue using Closes #<id> or Fixes #<id>.
  - Request at least one peer code review.


