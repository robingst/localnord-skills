# Prospecting

1. `get_account_status`: remaining daily prospect quota. Every search uses it.
2. `search_prospects` with `query` (activity + city, for example "plombier Lyon") and `limit` (10 by default). Nothing is saved. Show the candidates (name, city, rating, review count, website, verified) and point out weak signals: few reviews, low rating, no website, unverified.
3. With the user's selection, after "yes": `add_prospects` with the same `query` and the chosen `business_ids` (20 at most per call). This saves them to the agency's pipeline and uses quota.
4. For each added prospect (ids from `list_prospects`): `audit_prospect_listing`. Score, weaknesses with severity, ready-made sales arguments.
5. `draft_prospect_email` with `prospectId` and `auditSummary` (the 2 or 3 strongest weaknesses). Nothing is sent: the draft is for the user to copy. The draft comes out in French; translate it if the prospect is not French-speaking.

Deliverable: 3 to 5 prospects, each with score, top weaknesses and the email draft (subject and body).

Rules for the email: no ranking promise, only facts from the audit, one clear call to action (a short call or a free audit).

## Without the connector

Ask for the businesses' names or Google Maps links and what the user sees on each listing (reviews, rating, photos, posts, website). Score each one on contact, reputation, media and content, then write the email.
