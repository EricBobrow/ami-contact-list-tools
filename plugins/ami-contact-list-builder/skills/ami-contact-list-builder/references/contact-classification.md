# Contact Relevance, Segmentation, and Identity Matching

## Evidence review method

Use broad search terms to find candidates, then decide relevance from message-level evidence. Review:

- subject and current message content
- sender, recipients, and whether the user sent, received, or replied to the message
- signature details that identify the person or organization
- proposals, drawings, attachments, meetings, fees, invoices, permits, project names, addresses, participants, or other concrete context
- reciprocal correspondence or project material sent by the user

Treat direct project discussion, a substantive professional exchange, or repeated relevant correspondence as strong evidence. A keyword is only a search lead. Do not retain a contact merely because a word appears in an old quoted message, a signature, a newsletter, a mass solicitation, or an unrelated phrase such as `graphic design`.

## Qualifying professional correspondence

Include a person when the email history contains evidence of a professional relationship relevant to architecture, projects, clients, referrals, consultants, builders, the built environment, or the operation and marketing of the architect's firm.

Examples include:

- past or active architectural clients
- prospective clients who discussed a possible project
- architectural services, consultations, feasibility studies, proposals, retainers, fees, invoices, drawings, revisions, submissions, and project coordination
- residential, commercial, mixed-use, multi-unit, renovation, addition, fit-up, redevelopment, and new-construction discussions
- permits, planning, zoning, variances, heritage, building-code, accessibility, fire, inspections, occupancy, and municipal review
- structural, civil, mechanical, electrical, geotechnical, building-science, environmental, septic, HVAC, and other project engineering
- surveys, grading, servicing, stormwater, arborist work, site studies, and environmental studies
- builders, contractors, trades, suppliers, and construction managers involved in projects
- architects, interior designers, landscape architects, planners, surveyors, and other consulting professionals
- real-estate agents, brokers, developers, owners, investors, appraisers, development-finance contacts, and other people involved in a plausible property or project opportunity
- referral partners or people who introduced potential clients
- other professionally relevant people discussing projects, architecture, property, clients, or industry matters
- students, interns, job applicants, or employment contacts when the user wants professional-network records, while keeping them under outreach review by default

Exclude:

- the architect and current firm staff
- automated notices, receipts, system messages, newsletters, and no-reply senders
- clearly personal correspondence with no professional relevance
- spam and mass solicitations
- one-way sales pitches for marketing, advertising, SEO, websites, software, insurance, banking, travel, events, or unrelated business services when the user did not engage about a relevant project or professional relationship
- course promotions, awards solicitations, publication offers, sponsorship requests, and generic vendor offerings without substantive reciprocal correspondence
- generic role addresses when no individual can be identified, unless the user specifically wants organizations represented

When a plausible contact has mixed evidence, retain the interaction only in Needs Review until the user decides. Do not let a broad search term override a clear exclusion.

## Primary Contact Type for review

Assign one primary `Contact Type` to organize the review workbook. This is separate from relationship tags and does not imply marketing permission.

Use the closest supported type:

1. `Client / Prospect`
2. `Engineers`
3. `Planning / Municipal / Government`
4. `Surveyors / Designers / Consultants`
5. `Contractors / Builders / Trades`
6. `Real Estate / Development / Finance`
7. `Referral / Industry`
8. `Employment / Talent`
9. `Other Professional`

Choose the type from the person's primary role in the relevant correspondence, not from a keyword or company name alone. If two types are plausible, choose the best primary type and explain the alternative in Review Notes. Put uncertain cases in Needs Review as `Uncertain Contact Type`.

After the pilot, sort Contacts so each Contact Type forms one continuous block. Use a subtle visual marker on the first row of each block when the spreadsheet format supports it. Do not copy Contact Type into the CRM `Tags` field unless the user explicitly approves matching CRM tags.

## Approved AMI relationship tags

Assign one or more of these exact tags. Separate multiple tags with commas.

- **Past Client**: clear evidence that the architect was engaged for paid or substantive project work.
- **Prospective Client**: discussed a possible project, proposal, consultation, scope, fee, or next step without clear evidence that the project proceeded.
- **Contractor / Builder**: builder, contractor, trade professional, or construction company contact.
- **Consulting Professional**: architect, engineer, designer, planner, surveyor, landscape professional, specialist, or other project consultant.
- **Referral Source**: introduced, recommended, or regularly connects the architect with potential clients or projects.
- **General**: professionally relevant correspondence that does not fit the more specific tags.

Use the most specific supported tag or tags. Do not infer Past Client from a friendly tone or a single inquiry. When evidence is incomplete, suggest the best tag, lower the confidence, and place the item in Needs Review.

## Optional project and client-type tags

Some firms already know the project types, specialties, markets, or client types they want to address with different messages. Treat these as an optional second tag set, separate from the AMI relationship tags during review.

Before applying them:

1. Ask whether the user wants this additional segmentation.
2. If yes, ask for the exact tag names and a brief description of when each should apply.
3. Offer examples only when useful: `Residential`, `Commercial`, `Hospitality`, `Healthcare`, `Education`, `Developer`, `Homeowner`, or another clearly named specialty.
4. Repeat the proposed list and rules back to the user and wait for approval.

Apply only the exact user-approved tags. Use one or more when the correspondence clearly supports them. Evidence may include project descriptions, property types, proposals, drawings, consultant coordination, completed work, or repeated professional discussions.

Do not:

- force every contact into a project or client-type category
- invent a specialty from a company name or job title alone
- silently replace the user's wording with a synonym
- apply a broad tag when the evidence concerns an unrelated part of the person's work

Leave `Project / Niche Tags` blank when no approved tag is supported. Put uncertain cases in Needs Review as `Uncertain Project / Niche Tag`, with the likely tag and evidence explained. Test the optional tags on the pilot and revise the rules before processing earlier years. If the user changes the approved list later, recheck previously processed contacts against the revised rules.

Keep `Relationship Tags` and `Project / Niche Tags` separate in the review workbook. Combine both sets only in the import-ready `Tags` column.

## Confidence

Use `High`, `Medium`, or `Low`.

- **High**: direct and repeated evidence clearly supports the decision.
- **Medium**: evidence is useful but incomplete or somewhat indirect.
- **Low**: the decision is a tentative suggestion that needs human review.

## Exact duplicate removal

Compare email addresses without regard to capital letters. For example, `Jane@Example.com` and `jane@example.com` are the same address. Retain one contact row and keep all qualifying interaction rows.

## Same person with multiple email addresses

A matching name is a signal for review, not automatic proof.

Create a potential identity match when two records have the same or very similar name but different email addresses. Compare:

- full name and distinctive spelling
- display-name variations, alternate surnames, initials, and signature names
- organization, job title, and website domain
- phone numbers and signature details
- conversation participants and project names
- an explicit message stating that the person changed email addresses

Combine the records only when multiple clues support the match. Choose the most recent, active, professional address as the primary email when the evidence is clear. Keep other verified addresses in `Additional Emails`.

When evidence shows that a person changed employers or roles, keep the person as one contact but flag potentially stale organization, title, office phone, and email details for review. Do not overwrite a verified historical detail with an unverified current assumption.

Do not combine records based only on:

- employer name
- a shared office phone number
- a generic address such as `info@company.com`
- a common name without supporting evidence

If uncertain, keep separate rows and add both to Needs Review with the proposed match explained.

## Phone-number extraction and selection

Look first in the current message's signature and direct contact blocks. Capture phone numbers associated with the individual, not numbers belonging to quoted third parties, forwarded contacts, project sites, or unrelated participants.

Record the original wording in `Phone as Found`. Prefer a direct or mobile number as the primary `Phone`. Do not use a fax number as the primary phone.

Ask for the user's usual country before converting local numbers. Produce CRM-ready numbers in E.164 format, which begins with `+`, the country code, and the subscriber number without spaces or punctuation. Examples:

- United States or Canada: `(415) 555-0123` becomes `+14155550123`
- United Kingdom: `020 7946 0123` becomes `+442079460123`
- Australia: `02 9374 4000` becomes `+61293744000`

Preserve numbers that already include a valid country code. Interpret `00` or `011` as an international dialing prefix when the context is clear. Remove a domestic trunk zero only when the country rules make that unambiguous.

Store additional verified numbers in `Additional Phones`, separated by commas. Store an extension separately in `Extension`. Use `Phone Type` such as Mobile, Direct, Office, Home, or Other.

If the country, number, ownership, or conversion is uncertain, leave the CRM-ready `Phone` field blank, preserve the original in `Phone as Found`, and add a plain-language review note.

If a number appears to belong to a former employer, preserve it as evidence only when useful, mark it as possibly stale, and keep it out of the CRM-ready phone field until verified.
