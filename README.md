# Hermes Email Agent

A personal, single-user automation app that connects a self-hosted
[Hermes Agent](https://github.com/NousResearch/hermes-agent) to the owner's own
Google account through the official Google APIs and OAuth 2.0.

## What it does

- Reads mail from the owner's own Gmail mailbox (search, threads, labels)
- Drafts, labels and — only with the owner's explicit confirmation — sends mail
- Uses Google's official OAuth 2.0 "Desktop app" client flow
- Runs entirely on the owner's own machine; there is no hosted backend

## Scopes requested

- `gmail.readonly` — read and search messages
- `gmail.modify` — apply/remove labels
- `gmail.send` — send mail composed and approved by the owner

## Authorization

Access is granted by the mailbox owner during a standard Google consent screen.
No other user can authorize this client. Authorization can be revoked at any time
at <https://myaccount.google.com/permissions>.

## Data handling

See [PRIVACY.md](PRIVACY.md).

## Contact

Open an issue in this repository.
