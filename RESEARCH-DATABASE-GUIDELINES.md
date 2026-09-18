# ✅ Research Database Guidelines

## Record types

- `advertised-project`: an institution currently publishes a defined project or vacancy.
- `research-area`: an official research group or faculty research direction; no vacancy implied.
- `proposed-topic`: a research idea derived from literature and aligned with a research group; not endorsed by the professor.
- `funding-call`: an official funding or studentship announcement with a stated deadline.
- `potential-supervisor`: a researcher whose official university or institute profile shows a plausible research match; supervision availability is not implied.

## Required metadata

```yaml
id: unique-record-id
title: Specific research title
subject: Main discipline
tags: [keyword-1, keyword-2]
country: Country
university: University name
department: Department or institute
record_type: proposed-topic|potential-supervisor|advertised-project|research-area|funding-call
status: verified|needs-review|expired|unconfirmed
last_verified: YYYY-MM-DD
university_topic_url: Official research or programme page
supervisor_profile_url: Official university or institute faculty profile, if applicable
research_group_url: Official laboratory or research-group page, if applicable
contact_source: Official institutional page, if published
funding_url: Official funding page, if applicable
source_urls: Official sources supporting important claims
```

## Official university source policy

- Use official university, department, institute, laboratory, government, funder, or publisher pages whenever possible.
- For professor records, prioritize the official university faculty profile and department page.
- Confirm current affiliation, academic title, department, research group, and research interests from official sources.
- Verify publications through institutional repositories, official publication lists, ORCID, or publisher pages when available.
- Include institutional email addresses only when publicly listed on an official source.
- Never infer a private email address or guess an institutional email format.
- Never describe a professor as a confirmed guide without written confirmation.
- Do not infer current supervision availability or funding from a faculty profile alone.
- Check official doctoral programme, funded project, studentship, and admissions pages for application-related claims.
- Keep a source URL for each material claim and record the verification date.

## Verification policy

- Confirm that a professor's current affiliation matches the record.
- Separate a research theme from an active PhD vacancy.
- Add an access/verification date for volatile information.
- Mark old, unavailable, or redirected opportunities as `expired` or `needs-review`.
- Prefer recent publications and projects, but do not assume that recent publication means current supervision availability.
- If official sources conflict, record the conflict and mark the record `needs-review` until resolved.

## Topic quality checklist

A useful topic should contain:

1. A defined problem and target population/system.
2. A measurable research objective.
3. A plausible methodology.
4. A clear contribution beyond implementation alone.
5. Ethical, legal, safety, and reproducibility considerations where relevant.
6. A realistic scope for a doctoral thesis.

## Recommended review cadence

- Active vacancies and deadlines: review weekly during application seasons.
- Faculty affiliations and contact pages: review every 3 months.
- Research themes and publications: review every 6 months.
- General portal links: review every 6 months.

## Data integrity status

`verified` means the linked source was checked and the claim is supported by it. It does **not** mean admission, funding, or supervision is guaranteed.
