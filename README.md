# AMI Contact List Tools

This public Codex plugin helps architects turn relevant email history into a clean, reviewed professional contact list for Sunshine Island CRM.

It guides the user through email-source setup, a small pilot, relationship and project-type tagging, likely duplicate review, phone-number formatting, and preparation of a workbook and CSV. It does not contain anyone's email, contact records, passwords, or connector credentials.

This is an early testing release from the Architect Marketing Institute. The repository is public so invited testers can install it easily. AMI will continue refining the workflow as the pilot develops.

## Install in Codex

### Easiest method

1. Open Codex and start a new task.
2. Copy the paragraph below and paste it into Codex:

> Please install the AMI Contact List Builder plugin from the public marketplace at https://github.com/EricBobrow/ami-contact-list-tools. Add that marketplace, install `ami-contact-list-builder`, and tell me when I should start a new Codex task.

3. Approve the installation if Codex asks for permission.
4. When Codex says the installation is complete, start a new Codex task. This refreshes the list of available skills.
5. Paste this short starter prompt:

> Use `$ami-contact-list-builder` to help me build a reviewed professional contact list from my email history for Sunshine Island CRM. Ask me the setup questions one at a time.

Codex will begin with a few simple questions, then recommend a small pilot before analyzing a larger date range.

### Command-line method

Advanced users can install the plugin with these two commands:

```text
codex plugin marketplace add EricBobrow/ami-contact-list-tools --ref main
codex plugin add ami-contact-list-builder@ami-contact-list-tools
```

Start a new Codex task after installation.

## Email access and privacy

The plugin contains instructions only. Each tester separately authorizes their own Gmail or Outlook Email connector, or supplies their own Apple Mail MBOX export. Codex should use read-only email access during contact discovery and should never ask the user to paste an email password into a task.

The workflow creates files for the tester to review. It does not automatically import contacts, decide marketing permission, or launch campaigns.

## Support

For installation, testing, or Sunshine Island CRM import help, contact [support@archmarketing.org](mailto:support@archmarketing.org).

Copyright © 2026 Architect Marketing Institute. All rights reserved.
