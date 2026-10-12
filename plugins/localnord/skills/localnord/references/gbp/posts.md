# Posts
Checked against Google's help pages on 2026-10-12.

## Post types

- **Update**: news about the business. Description, photo or video, and an optional action button with a link.
- **Offer**: a sale or a deal. Title, dates and time are required. Google adds a "View offer" button. Optional: description, photo or video, coupon code, link, terms and conditions.
- **Event**: title, start and end dates and times. Optional: description, photo or video, action button. Without times, the event shows as lasting 24 hours on its dates.
- Hotels cannot publish offer posts, nor any post that mentions or links to deals, promotions or discounts.
- Posts show in the Updates or Overview tab on mobile, and in "From the owner" on a computer, on Search and Maps.
- Posts older than 6 months are archived unless a date range is set.

## Rhythm

Practice, not a Google rule:
- Keep a steady rhythm the business can sustain, for example one post a week, rather than a burst of posts followed by months of silence.
- Tie each post to something true and current: real work done, a season, a new product, a real event or offer with its real dates.
- Vary the types and topics. Write each post for its listing instead of reposting the same text.
- Put the key message in the first sentence: readers often stop there.

## What Google rejects or removes

- **Phone number in the text**: "Posts that include a phone number in the post description might get rejected if they cannot be verified as being connected to the business". Google may also remove posts with unverified contact information (phone, email, social handles). Use the Call now button instead: it uses the profile's verified number.
- **Unrelated contact details or links**: email addresses, phone numbers, social links or links to other websites that are not related to the business.
- **Untrusted links**: only link to websites you trust. Google blocks links to malware, viruses, phishing or pornographic material.
- **Regulated products**: a business in a regulated industry (for example alcohol, tobacco, pharmaceuticals, gambling, adult services) may post, but not about the regulated products themselves.
- **Offensive or explicit content**: no inappropriate or offensive language, images or videos, nothing sexually suggestive or explicit.
- **Fake or misleading content**, and everything else banned by Google's prohibited and restricted content policy (harassment, hate speech, dangerous content, personal information...).
- **Low-quality text**: Google asks to avoid misspelled words, extra characters, text that adds no value, and auto-generated or distracting content.

After publishing, Google reviews each post. Statuses: Live, Pending (still processing, or profile not verified), Not approved (a question mark shows which policy was violated). A post that is not approved does not show on Search or Maps.

## Localnord's drafting rules

Localnord's drafts also keep out of the text:
- phone numbers, URLs and domain names, email addresses, social handles, precise street addresses;
- any fact, figure, price, guarantee or award the user did not provide;
- unverifiable superlatives ("best in town") and invented urgency ("last chance" without a real deadline).

Text written for a business follows the listing's language.

## Action button and link

- Updates and events can carry one action button with a link, for example to book, order online or learn more. Offers get "View offer" automatically.
- Call now uses the verified phone number of the profile: the right button when a call is the expected action.
- Link to a working page of this business that matches the button: the booking page for a booking button, the product page for a product.
- Do not write "click here" in the text. Give the reason to act; the button does the rest.

## With the connector

- `create_post_draft`: saves an internal draft. No confirmation needed.
- Before anything goes to Google, show the draft: type, text, image, button and link, publication date.
- `schedule_post_publication`: schedules the post, only after an explicit "yes" for that post and that date.
- `publish_post_google`: publishes now, only after an explicit "yes".
- Report what happened. Google reviews each post: it can stay pending before going live, or be not approved.

## Without the connector

Ask for the business type, the topic, the real facts to include (dates, offer terms) and the button target. Write the post with the rules above and say it must be published from Google Business Profile.

## Sources

- https://support.google.com/business/answer/7342169 (Create & manage posts on your Business Profile)
- https://support.google.com/business/answer/7213077 (Business Profile photos, videos & posts content policy)
- https://support.google.com/contributionpolicy/answer/7400114 (Prohibited & restricted content)
