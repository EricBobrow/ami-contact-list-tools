# Email Source Setup

## General rule

Use a supported email connector when possible. Test access with a narrow, read-only search before processing a large mailbox. Never request or store the user's password.

## Outlook or Microsoft 365

1. Ask the user to open Codex and install or enable the Outlook Email connector if it is not already available.
2. Have the user sign in to the Microsoft account that contains the email history.
3. Ask them to approve the minimum email-reading access requested by the connector.
4. Run a read-only test, such as finding a few recent messages in Inbox and Sent.
5. Confirm the correct account and folders before starting the pilot.

If Outlook is only the desktop application but the underlying account is Gmail, use the Gmail connector instead.

## Gmail or Google Workspace

1. Ask the user to open Codex and install or enable the Gmail connector if needed.
2. Have the user sign in to the Google account that contains the email history.
3. Ask them to approve the minimum email-reading access requested by the connector.
4. Run a read-only test, such as finding a few recent messages in Inbox and Sent.
5. Confirm the correct account and folders before starting the pilot.

## Apple Mail

Apple Mail is an application, not the email provider. First identify the account shown in Apple Mail:

- Gmail or Google Workspace: use the Gmail connector.
- Microsoft 365, Exchange, Hotmail, or Outlook: use the Outlook Email connector.
- iCloud Mail or another provider without a supported connector: export the relevant mailbox as an MBOX file.

### Export an Apple Mail mailbox to MBOX

1. Open the Mail application on the Mac.
2. In the left sidebar, click the mailbox to export, such as Inbox, Sent, or a project mailbox.
3. In the menu bar at the top of the screen, choose **Mailbox**, then **Export Mailbox**.
4. Choose an easy-to-find folder, such as Desktop or Documents.
5. Click **Choose**. Apple Mail creates a folder containing an `.mbox` package.
6. Repeat for each mailbox needed, especially both Inbox and Sent.
7. In Codex, attach or point to the exported `.mbox` files and ask to begin with the agreed pilot date range.

Do not use Computer Use to open thousands of messages one by one. It may help with the export or a few spot checks, but the MBOX data should be analyzed directly.

An Apple Mail MCP server is an optional advanced setup. Treat community-built software as third-party software and explain that it requires installation and permission to access email data. It is not the standard beginner workflow.

## Exported MBOX safeguards

- Keep the exported files in a private folder.
- Analyze only the approved mailbox and date range.
- Do not copy complete email bodies into the contact workbook.
- Keep short summaries focused on the professional relationship or project context.
- Tell the user when processing is complete so they can decide whether to retain or delete the export.

