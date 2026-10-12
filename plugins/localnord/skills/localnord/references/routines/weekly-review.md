# Weekly portfolio review

Goal: in a few minutes, tell the agency what needs attention this week across all its listings.

## With the connector

Read-only steps: no confirmation needed.

1. `list_agency_alerts`: recent notifications (new reviews, failed posts, automations to validate).
2. `list_listings` with `filters: { includeInactive: true }`, so suspended and pending listings are not left out (page with `limit` and `offset` on a large portfolio). For each listing read its health (ok, paused, pending, disconnected), its unanswered reviews count and its last post date.
3. For each listing with unanswered reviews: `list_reviews` with `filters: { replyState: 'unreplied' }`, to see their ratings and how long they have waited. On a large portfolio, start with the 10 listings with the most unanswered reviews and say how many are left.
4. `get_scheduled_content` with `view: 'counts'` and `includeEmpty: true`: listings with nothing scheduled.
5. Optional, for a prioritized plan: `plan_portfolio_week` (P1/P2/P3). It launches no action.

## Classify each listing

- **Urgent**: disconnected or pending listing, unanswered 1–2★ review, failed publication.
- **To do**: unanswered reviews waiting for more than 7 days, nothing scheduled, no post for 14 days or more.
- **OK**: none of the above.

## Deliverable

| Listing | Status | Why | Next action |
|---|---|---|---|

Urgent first, then To do; group the OK listings on one line. Offer the next routine ("Shall I draft the replies for the 3 listings with pending reviews?"). Do not start any write action on your own.

## Without the connector

Ask for each listing: last post date, number of unanswered reviews, lowest recent rating, any warning shown by Google. Apply the same classification and the same table.
