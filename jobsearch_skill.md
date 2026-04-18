# Job Search Skill

Triggered by "search for jobs".

## Your criteria

- **Role types:** [PUT YOUR ROLES HERE such as Senior Engineer]
- **Comp floor:** [PUT YOUR COMP MINIMUM HERE such as >=$150K]
- **Company type:** [PUT YOUR COMPANY CRITERIA HERE such as series C+ and public]
- **Locations:** [PUT YOUR LOCATIONS HERE such as Remote, Hybrid, San Francisco, etc]

## Step 1 — Search Gmail simultaneously

Run these searches in parallel:

- LinkedIn digests: `subject:(LinkedIn job alert OR job matches for you) newer_than:30d`
- ATS emails: `from:(greenhouse.io OR lever.co OR ashbyhq.com OR workday.com) newer_than:30d`
- Job board alerts: `subject:(job alert OR hiring OR opening) newer_than:30d`
- Recruiter outreach: `subject:(opportunity OR role OR position) from:(recruiting OR recruiter) newer_than:30d`

Extract from each: company name, role title, salary if listed, job link.

## Step 2 — Deduplicate

Same company + role from multiple sources: keep the most complete version.

## Step 3 — Cross-reference your tracker

Fetch your tracker doc: [YOUR GOOGLE DRIVE DOC ID]
Remove any company/role combinations already listed there.

## Step 4 — Filter by your criteria

For each remaining job:
- Company type check: use web search if uncertain (`[COMPANY] funding stage 2024 2025`)
- Comp check: if not posted, estimate via `[COMPANY] [ROLE] salary site:levels.fyi OR site:glassdoor.com`
- Drop anything that doesn't meet your bar.

## Step 5 — Check for prior applications

For each remaining job, search Gmail:
`subject:(confirmation OR applied OR thank you for applying) [COMPANY NAME] newer_than:365d`

- Already applied → append to tracker, remove from output.

## Step 6 — Rank and output

Rank by [YOUR PRIORITY ORDER, e.g. title tier, then recency].

Format each result:
- Role Title — Company — Comp (stated or estimated)
- Link
- Location
- Status: Ready to apply

Include summary: total found, already applied, filtered out, ready to apply.


