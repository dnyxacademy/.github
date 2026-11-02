# How we work

This applies to every repository in the Dnyx Academy organisation, and to the repository you create
from one of our starter templates during your internship.

## The loop

1. **Pick up the ticket.** Each day's work arrives as a ticket in your Dnyx Learn lesson, with a due
   date. The longer brief for the week's assignments lives in the matching public repository.
2. **Branch.** Never commit straight to `main`. Name the branch after the work:
   `week-1/responsive-layout`, `week-3/crud-api`.
3. **Commit as you go.** Several small commits across several days beats one big commit on the last
   evening — your commit history is part of how your work is marked.
4. **Open a pull request.** Open it early, even as a draft, and describe what you did and what you
   are unsure about.
5. **Answer the review.** A mentor comments within 48 hours. Reply to every comment in writing and
   push the fixes. Unanswered review comments cost marks.
6. **Submit the link.** Paste the pull request link into the Dnyx Learn lesson before the due date.

## Writing a good pull request

- One piece of work per pull request. If the title needs the word "and", it is probably two.
- Say what changed and why, not just what file you touched.
- Include a screenshot or a short clip for anything visual.
- Say what you tested, and what you know is still broken.

## Using AI assistants

Using AI tools is allowed, taught and expected — but with rules.

- **Disclose it.** Every weekly note includes a short "How I used AI" section.
- **Understand it.** If you cannot explain a line in a review comment, do not ship it.
- **Never paste secrets** — keys, tokens, connection strings, anyone's personal data — into a prompt.
- **Check licences** before copying generated code that looks like it came from somewhere else.

## Never commit

- `.env` files, API keys, tokens, passwords or database URLs. Use `.env.example` with empty values.
- `node_modules/`, build output, virtual environments, large data files or datasets.
- Anyone else's personal data, including real learner records.

If you do commit a secret by accident, tell a mentor the same day and rotate the key. Deleting the
file is not enough — it stays in the history.

## Honest work

Your repository is a record of what you built. Copying another learner's work, or submitting a
project you did not build, fails that item and is recorded. Asking for help, pairing with someone
and reading other people's code are all fine — say so in your note.
