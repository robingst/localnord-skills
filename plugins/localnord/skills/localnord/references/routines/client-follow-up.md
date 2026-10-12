# Client follow-up

## Onboard a new client listing

1. `list_available_gmb_locations` with `onlyAvailable: true`: Google locations the agency can access that are not in Localnord yet. Pick one with the user; its id looks like locations/123.
2. `onboard_client_listing` with `google_location_id`. First call without `confirm_credits`: it returns the cost (one paid slot of the subscription, plus the audit once the free quota is used). Show it, ask, then call again with `confirm_credits: true`.
3. `run_full_audit`: score, top priorities, health summary.
4. `get_listing_config`: what is left to configure (language of generated texts, review automation, ranking scans). Propose values; apply them with `update_listing_config` only after "yes". Adding ranking keywords costs one ranking scan per keyword and per cycle: say so before.

Deliverable: an onboarding plan with 3 quick wins for this week, then the monthly rhythm (posts, photos, reviews).

## Monthly client report

1. `list_reports` for the listing: reuse a report of the same period if one exists.
2. `generate_report` (default period: last full month). It runs in the background: call `get_report` until its status is ready.
3. Summarize the report in 5 lines for the agency.
4. Delivery with `deliver_report`: `action: 'pdf'` returns a link, no confirmation needed. `action: 'email'` (sent to the client in the agency's branding) and `action: 'share'` (public link) only after "yes", with the recipient shown.

## Client meeting brief

1. `prepare_client_brief` with `periodDays` (30 by default, 90 for a quarterly review).
2. Write a one-page brief: results against the previous period, reviews, rankings, work done by the agency, 3 next actions. Follow the tool's notes: if the period starts before the listing was added, say so; the work done counts only what was published through Localnord, and the posts the client published directly on Google are counted apart (never add them to the agency's work); missing previous data is not growth; a section marked unavailable is named as such, not skipped.

## Without the connector

Ask for the Google Business Profile performance numbers (views, calls, direction requests, website clicks) for the period and the previous one, plus review count and average rating. Same deliverables.
