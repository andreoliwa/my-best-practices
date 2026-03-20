# Code

## Write TODO comments for temporary code

Add `TODO` comments (with a Jira ticket if applicable) for anything temporary —
retry limits, tables scheduled for deletion, feature flags, conditional logic
that will be removed.

The code is the source of truth. We work async across time zones, and we can't
remember everything about every work stream. Common sense doesn't scale —
explicit communication through code does.

Without a `TODO`, the next person looking at the code won't know it's temporary.
This has happened multiple times: someone reads code that was meant to be
short-lived and treats it as permanent.

### Examples

- `TODO(PROJ-123): remove 50x retry once the upstream fix is deployed`
- `TODO(PROJ-456): drop this table after backfill migration`
- `TODO: remove this IF after feature X is fully rolled out`

## Communicate through code

We can't keep every detail in our heads — especially across work streams.

Use comments, `TODO`s, and docstrings to capture intent and business rules where
future readers will actually see them:

- `TODO`s in serving and storage table definitions
- `TODO`s in `.proto` files next to nested messages or deprecated fields
- Business rules documented in `.proto` files, not just in Confluence
