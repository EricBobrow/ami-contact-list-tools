---
name: ami-contact-list-builder
description: Build a clean, reviewed, segmented professional contact list from Outlook, Microsoft 365, Gmail, Google Workspace, Apple Mail, or exported MBOX email history for Sunshine Island CRM. Use when an architect wants Codex to review message-level professional evidence, find relevant contacts and interactions, reject keyword-only false positives, organize contacts by review type, suggest AMI relationship tags, apply optional user-approved project-type or client-type tags, match likely duplicate identities, collect and format phone numbers, create a workbook and CSV, or prepare for a GoHighLevel contact import.
---

# AMI Professional Contact List Builder

## Purpose

Guide a less technically experienced architect through the entire process without presenting a long specification. Ask setup questions one at a time, run a small pilot, show the results, and expand only after approval.

The workflow prepares files for review. It does not make marketing-permission decisions, import contacts, or launch campaigns unless the user separately asks for that action and confirms the reviewed data.

## Interaction Style

- Begin with a brief, reassuring explanation of the outcome and the small-pilot approach.
- Ask one question at a time. Do not present a long intake form.
- Explain unfamiliar technical terms in plain language the first time they appear.
- Make a sensible recommendation when the user is unsure, then ask for confirmation.
- Keep email access read-only during discovery and analysis.
- Never ask the user to paste an email password into Codex.
- Pause for approval after the pilot and before any CRM import or campaign action.

## Guided Workflow

### 1. Identify the email source

Ask which email setup the user has: Outlook or Microsoft 365, Gmail or Google Workspace, or Apple Mail.

Read `references/email-source-setup.md` when the provider is uncertain, a connector is missing, Apple Mail is involved, or MBOX files are supplied.

If a supported connector is not available, explain the installation or connection step in plain language and wait for the user to complete it. Do not claim access until a read-only test succeeds.

### 2. Gather setup details one at a time

Ask for:

1. The mailbox or account to analyze.
2. The user's name, firm name, and the firm's own email addresses or domains to exclude.
3. The usual country for interpreting local phone numbers.
4. Whether the user wants optional project-type, market-niche, or client-type tags in addition to AMI relationship tags. If yes, ask for the exact tag names and a brief description of when each should apply. Offer examples such as `Residential`, `Commercial`, `Hospitality`, `Healthcare`, `Developer`, or `Homeowner` only when helpful, and wait for approval of the final list. If no, skip these tags without adding complexity.
5. The pilot date range. If unsure, recommend the most recent three months.
6. The folder where working files should be saved.

Confirm the final scope in a short summary before analyzing messages.

### 3. Run a small pilot

Search both received and sent email, including at least Inbox and Sent. Analyze messages until reaching either the end of the pilot date range or 30 to 50 qualifying contacts.

Use a two-pass method: search broadly for plausible architecture, construction, property, referral, consulting, and firm-related correspondence, then review the actual message evidence before retaining a contact. Check the subject, current message content, sender, recipients, direction, signature, and useful project context. Do not classify a contact from a keyword that appears only in old quoted text, a signature, a newsletter, or an unrelated use of a broad word such as `design`.

Use batches small enough for reliable progress and save a new version after each completed batch. If a connector paginates or limits results, continue through every page in the approved scope. Keep a brief progress log containing the date range completed, folders searched, pages or result sets completed, messages reviewed, exclusions, and the last stable output version.

Use the relevance and classification rules in `references/contact-classification.md`.

### 4. Build the review workbook

Create a workbook with the three worksheets and exact field purposes in `references/workbook-schema.md`. Use the spreadsheet skill available in the current environment.

Keep one contact row per person after approved identity matching. Keep separate interaction rows so useful relationship history is not compressed into one vague note.

Assign one primary `Contact Type` for review organization, separate from CRM relationship tags. After the pilot, sort the Contacts worksheet so each type forms a continuous block. Treat these types as review aids rather than marketing permission or CRM tags.

### 5. Review ambiguous records

Show the user the pilot results and a short review list. Give special attention to:

- the same name appearing with different email addresses
- shared or generic email addresses
- uncertain names or organizations
- uncertain marketing category
- uncertain project-type, market-niche, or client-type tag
- phone numbers that cannot safely be converted to international format
- contacts whose professional relevance is unclear
- possible false positives caused by quoted text, signatures, newsletters, or one-way solicitations
- contact details that may be stale because the person changed employers or roles
- employment, student, or applicant contacts whose professional relevance may be real but whose outreach suitability requires a separate decision

Do not silently guess. Put uncertain records on the Needs Review worksheet with a plain-language reason and a recommended action.

### 6. Obtain pilot approval

Summarize:

- messages reviewed and folders or date ranges completed
- qualifying contacts found
- results excluded after evidence review, grouped by the main exclusion reasons
- primary Contact Type totals
- likely duplicates or multiple-email identities
- suggested AMI relationship-tag totals
- optional project-type, market-niche, or client-type tag totals when those tags are in use
- phone numbers found and how many need review
- any limitations in the source or connector

Ask the user to approve the pilot rules before expanding the date range. Incorporate corrections into the next batch.

### 7. Expand and finalize

After approval, process the remaining approved date range in batches. When the scope spans many years, complete one year or another clearly bounded range at a time, report the results, and preserve a resumable checkpoint before moving backward. Preserve stable identifiers and previously approved decisions. Recheck new evidence that may strengthen or change a contact's category.

Before creating the final CSV:

- require one reviewed contact row per person
- keep the exact AMI relationship tags in `Relationship Tags`
- keep only the user's approved optional tags in `Project / Niche Tags`
- combine both approved tag sets in the import-ready `Tags` column, separated by commas
- include only CRM-ready international phone values in `Phone` and `Additional Phones`
- keep uncertain values out of CRM import fields and explain them in `Review Notes`
- preserve source evidence in the interaction sheet
- exclude the architect, firm staff, automated senders, and nonprofessional messages
- keep review-only contacts out of the CRM CSV until the user confirms that outreach is appropriate

Provide a clean workbook and a contacts-only CSV. Do not import them automatically.

### 8. Prepare for Sunshine Island CRM

When the user is ready to import, read the import section in `references/workbook-schema.md`. Explain the field mapping and recommend a small test import first. Remind the user that the AMI team is available at support@archmarketing.org if any import question or problem arises.

## Completion Standard

The result is ready only when:

- the approved scope has been fully processed
- Inbox, Sent, and any other approved folders reached the end of pagination for every completed date range
- every output file opens successfully
- every contact has a clear evidence trail or a review flag
- duplicate and multiple-email cases have been reviewed
- CRM phone fields contain only safe international values
- relationship tags use only the approved AMI wording
- optional project-type, market-niche, or client-type tags use only the user's approved wording and remain blank when evidence is insufficient
- no password, private authentication token, or unnecessary full email body is copied into the workbook
- no contact is retained solely because of a keyword in quoted text, a signature, a newsletter, or an unrelated solicitation
- the user has been reminded to confirm consent and appropriateness before marketing outreach
