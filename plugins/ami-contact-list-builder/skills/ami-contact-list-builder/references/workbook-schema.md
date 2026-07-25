# Workbook and CRM Import Specification

## Workbook file

Create one Excel-compatible workbook with these worksheets:

1. `Contacts`
2. `Relevant Interactions`
3. `Needs Review`

Save a versioned working file after each completed batch. At finalization, also export the reviewed `Contacts` worksheet as a UTF-8 CSV.

## Contacts worksheet

Use these columns in this order:

1. First Name
2. Last Name
3. Full Name
4. Primary Email
5. Additional Emails
6. Phone as Found
7. Phone
8. Additional Phones
9. Phone Type
10. Extension
11. Organization
12. Job Title
13. Relationship Tags
14. Project / Niche Tags
15. Tags
16. Relationship Summary
17. First Relevant Date
18. Most Recent Relevant Date
19. Relevant Interaction Count
20. Source Mailbox
21. Classification Confidence
22. Phone Confidence
23. Needs Review
24. Review Notes

`Phone` and `Additional Phones` contain only verified E.164 values. `Phone as Found` preserves the readable number taken from the email. Dates use ISO format `YYYY-MM-DD`.

`Relationship Tags` contains only the approved AMI relationship tags. `Project / Niche Tags` contains only the user's approved optional project-type, market-niche, or client-type tags and may be blank. `Tags` combines both approved sets as a comma-separated value for CRM import.

## Relevant Interactions worksheet

Use these columns:

1. Contact Full Name
2. Contact Email Used
3. Interaction Date
4. Direction
5. Subject
6. Short Professional Summary
7. Project or Topic
8. Source Mailbox
9. Source Message Identifier

Keep the summary brief and factual. Do not copy full message bodies or unrelated private details.

## Needs Review worksheet

Use these columns:

1. Review Type
2. Contact or Record
3. Current Value
4. Suggested Value or Match
5. Why Review Is Needed
6. Evidence Summary
7. Recommended Action
8. User Decision

Typical review types include Possible Same Person, Shared Email, Uncertain Name, Uncertain Relationship Tag, Uncertain Project / Niche Tag, Uncertain Phone, and Uncertain Professional Relevance.

## Final CSV

Create the CSV only after the user approves the reviewed contact rows. Include one row per person. Keep:

- Primary Email in the main Email field
- Additional Emails in a separate custom field unless the user chooses another CRM strategy
- Phone as an E.164 value
- Additional Phones in a separate custom field
- Tags separated by commas, combining the approved relationship tags and optional project or client-type tags
- useful relationship history in the Contact Notes or a suitable custom field

Do not include source-message identifiers in the CRM import CSV.
Keep the separate `Relationship Tags` and `Project / Niche Tags` columns in the review workbook. Include them in the CSV only if the AMI team has created matching custom fields; otherwise import the combined `Tags` column.

## Sunshine Island CRM import

Sunshine Island CRM is based on HighLevel. Interface wording may change over time, so use the current Contacts import screen and explain any wording difference plainly.

Recommended procedure:

1. Sign in to Sunshine Island CRM.
2. Open **Contacts**.
3. Choose **Import Contacts**, **Import**, or the current equivalent.
4. Upload the reviewed contacts CSV.
5. Confirm the file has one contact per row and that the first row contains column headings.
6. Map CSV columns to CRM fields. At minimum, map First Name, Last Name, Email, Phone, Tags, and the relationship note or custom field selected by AMI.
7. Confirm that `Phone` maps to the CRM's main phone field and contains international values beginning with `+`.
8. Map optional fields such as Organization, Additional Emails, Additional Phones, Phone Type, Extension, Relationship Tags, Project / Niche Tags, and Review Notes only when matching custom fields exist.
9. Choose the appropriate duplicate-handling option. Normally use Email as the main matching field, with Phone as an additional matching field when the records are clean.
10. Import a small test group first, such as 10 to 20 contacts.
11. Inspect the test contacts in Sunshine Island CRM. Confirm names, email, phone, tags, and notes landed in the correct fields.
12. Correct any mapping problem before importing the remaining contacts.
13. Complete the full import only after the test passes.

Do not add imported contacts to a marketing campaign automatically. First confirm consent, appropriateness, and the firm's outreach plan.

If any import step is unclear or produces an unexpected result, stop and contact the AMI team at support@archmarketing.org. AMI can help review the CSV, fields, and import mapping.

Current HighLevel import guidance:
https://help.gohighlevel.com/support/solutions/articles/155000005143
