# Things Agent Cloud: known issues

This repository lists the known problems with [Things Agent Cloud](https://things-agent-cloud.tobiaspoertner.com), the service that connects Claude, ChatGPT, Cursor and Claude Code to your Things 3 tasks.

For whether everything works right now, see the **[status page](https://things-agent-cloud.tobiaspoertner.com/status)**. It shows each part of the service and links every known issue listed here.

## Reading a known issue

Each known issue says:

- **What's wrong:** the problem, in plain words.
- **Who is affected:** for example everyone, only people using one app, or only people using repeating to-dos.
- **What you can do:** a workaround, or "nothing to do on your side".

Its labels show which part of the service it touches (`component:…`) and where it stands (`state:…`):

| State | Meaning |
|---|---|
| `state:investigating` | We're looking into it. |
| `state:identified` | We know the cause. |
| `state:fixing` | A fix is in progress. |
| `state:monitoring` | A fix is in place and we're watching it. |
| `state:fix-released` | The fix is live. |
| `state:resolved` | Resolved. The issue is closed. |

To hear about changes, open an issue and select **Subscribe**.

## Reporting a problem

Something not working that isn't listed? **[Report a problem](../../issues/new/choose)** with the form, or email [things-agent-cloud@tobiaspoertner.com](mailto:things-agent-cloud@tobiaspoertner.com) if you'd rather not post publicly (for example about your account or a payment).

This repository is public. Please don't post email addresses, passwords, history keys or the content of your tasks. We never need them to look into a problem; if we need to reach you, we'll ask you to email us.

## What this repository is not

It holds no code and no user data. Entries here are written for people using the service; the technical work happens elsewhere.
