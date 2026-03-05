# Principles

## Golden rule: don't waste other people's time

Basically everything in this repo is about that.

- [Avoid back-and-forth](slack.md#avoid-back-and-forth-provide-all-the-info-in-fewer-messages)
- [Show, don't tell](slack.md#show-dont-tell-provide-context-upfront-links-screenshots-cli-output)
- and so on...

## Write code with an open-source mindset

Code is the source of truth.

Handover of knowledge is done by reading the code. Open-source projects don't
have handover sessions with video calls or meetings.

Write code, docs, and commit messages as if the reader has no prior context —
because in 6 months, they might not.

## Leave TODO comments for other developers and AI agents

If you're writing code that will be removed in the future, add a `TODO` comment
(with a Jira ticket if applicable) and a brief explanation.

This helps other developers and AI agents understand the intent and context of
the code, and avoid being puzzled by the "why" of the code.
