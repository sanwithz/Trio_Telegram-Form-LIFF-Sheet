# Temporary security pause

The public form has been replaced locally with a static maintenance notice. It contains no form, login flow, tracking, SDK, script, or external network request.

## Required actions before restoring a collection flow

1. Revoke and replace the original Telegram bot token in BotFather. Removing the browser code does not revoke the token or remove it from repository history.
2. Audit the Telegram bot, Google Apps Script endpoint, stored submissions, access permissions, and logs for unauthorized use.
3. Do not place service tokens or recipient identifiers in browser-delivered files. Use an authenticated server-side relay with secrets held outside the public repository.
4. Define the data purpose, retention, operator identity, and user consent before collecting contact details, images, or identity data. Do not force a third-party login on page load.
5. Add server-side upload validation and size limits, authentication and authorization, abuse protection, and appropriate logging before deployment.

This is a temporary pause proposal, not a completed backend security fix.
