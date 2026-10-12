# Reviews: replies, policy and flagging
Checked against Google's help pages on 2026-10-12.

## A good reply

1. Thank the reviewer by name.
2. Pick up one concrete detail from the review, so the reply could not sit under any other review.
3. Answer the substance: a question, a criticism, a useful update.
4. Invite them back with a detail that reinforces their experience, not with a deal.
5. Sign off with a name or initials if the business wants a personal touch.

- Keep it short and direct: long replies lose readers before the main point.
- No generic "thank you" pasted under every review.
- Write in the language of the review.
- Replies are public and shown as coming from the business. The reviewer is notified and can still change the review.

## Negative review

- Stay calm and factual. Never argue publicly, never attack the reviewer.
- Acknowledge real mistakes. Do not take responsibility for things outside the business's control. Apologise when it is genuine.
- No personal data: nothing about the reviewer beyond their public name (no booking details, visit dates, health information, address).
- Offer an offline contact: invite the reviewer to call or email the business to resolve it privately. Use the business's public contact, never a staff member's personal one.
- Explain what the business can and cannot do.

## What stays out of a reply

- Deals and promotions. Google: replies should be conversational, not promotional.
- The reviewer's private information, personal attacks.
- Localnord's rule: no links, no prices and no emojis in replies. Localnord's drafts flag them.
- Google checks replies against its content policies. A reply that is not approved has to be edited. The check usually takes up to 10 minutes, sometimes up to 30 days.

## Asking for reviews: Google's rules

Allowed: asking customers to review a genuine experience, for example with a review link or a QR code, without incentives and without trying to influence the rating or the content.

Prohibited:
- Incentives (payment, discounts, free goods or services) for a review, or for changing or removing a negative one. Reviews paid for, directly or in kind.
- Discouraging or prohibiting negative reviews, or selectively soliciting positive ones. Example: sending the Google link only to customers who said they were happy.
- Requiring or pressuring customers to leave a review while on the premises.
- Asking for specific content, including content that names a staff member.
- Asking staff to collect a certain number of reviews.
- Reviews based on a conflict of interest: current or former employees, contractors or consultants, family, competitors.
- Posting on a competitor's profile to hurt its reputation.

Asking every customer is not prohibited. Google's rules target selection, incentives, pressure, imposed content and staff quotas.

## What can be flagged

- Only reviews that break Google's prohibited and restricted content policy: fake engagement and spam, conflict of interest, off-topic content, offensive content, harassment, hate speech, personal information, sexually explicit content, impersonation.
- Not a genuine negative review the business disagrees with. Google: do not report a review just because you disagree with it or dislike it. Google does not arbitrate disputes between businesses and customers.
- How: from the Business Profile (Read reviews, Report icon next to the review, choose a reason), or from Google's Reviews Management Tool, which also shows the status: Decision pending, Report reviewed - no policy violation, Escalated.
- A review found compliant can get one appeal from the same tool, up to 10 reviews per appeal. Evaluation typically takes several days.
- Extortion with negative reviews has its own reporting path, linked from the same help page.

## With the connector

- `list_reviews`: find the reviews to handle (unreplied, low ratings, recent).
- `generate_review_replies`: saves internal drafts and returns their validation warnings (links, prices, emojis). No confirmation needed.
- `reply_to_review`: publishes on Google, only after an explicit "yes" for those replies.
- `detect_fake_reviews`: a suspicion score with reasons. A signal, never proof. Never accuse a reviewer in a public reply.
- `flag_review_removal`: prepares and logs the flag for a review the user chose. It deletes nothing and returns the Google link where the user finishes the report by hand.
- Step by step: follow the reviews routine.

## Sources

- https://support.google.com/business/answer/3474050 (Manage customer reviews)
- https://support.google.com/business/answer/3474122 (Tips to get more reviews, including tips to write better review replies)
- https://support.google.com/contributionpolicy/answer/7400114 (Prohibited & restricted content)
- https://support.google.com/business/answer/4596773 (Report inappropriate reviews on your Business Profile)
