# Privacy Policy — Hermes Email Agent

_Last updated: 2026-11-10_

This policy describes how the "Hermes Email Agent" app (Google Cloud OAuth
client used by its owner) handles Google user data. The app is a personal,
single-user tool: it is authorized only by its owner, for the owner's own Google
account.

## 1. What data is accessed

With the owner's consent, the app accesses:

- Gmail messages, threads and labels in the owner's mailbox
  (`gmail.readonly`, `gmail.modify`, `gmail.send`)

No other Google data is requested.

## 2. Where data is stored

- OAuth credentials (access token, refresh token) are stored as a local file on
  the owner's own machine, readable only by the owner's account.
- Mail content is processed in memory on that same machine. Messages are not
  copied into any external database or cloud service.

## 3. How data is used

Data is used solely to perform the actions the owner requests — searching and
reading mail, applying labels, and sending messages the owner has reviewed and
approved. Data is not used for advertising, profiling, model training, or any
purpose unrelated to those requested actions.

## 4. Sharing and transfer

No Google user data is sold, rented, or shared with third parties. Data is not
transferred to any hosted backend operated by this project — there is no such
backend.

## 5. Retention and deletion

- Mail content: not retained beyond the running task; nothing is persisted
  unless the owner explicitly asks for output to be saved locally.
- Credentials: retained on the owner's machine until revoked or deleted. The
  owner can delete them at any time by removing the local token file.
- Revoking access at <https://myaccount.google.com/permissions> immediately ends
  the app's ability to read or send mail.

## 6. Google API Services User Data Policy

The app's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## 7. Contact

For questions about this policy, open an issue at
<https://github.com/lvxianchao/hermes-email-oauth/issues>.
