# Suspended or disabled listing
Checked against Google's help pages on 2026-10-12.

## What Google calls it

- **Suspended profile**: a profile that does not follow Google's guidelines. Profiles using a P.O. box are suspended. Content and appeals sent for a suspended profile may be rejected until it is reinstated.
- **Disabled profile**: for example when Google determines the business is not at the location it claims.
- **Restricted account**: after repeated policy violations, the Google Account is restricted from Business Profile activity. All its profiles are suspended and it cannot create or claim others. A restriction on another Google product can also suspend a profile created with that account.
- **Removed profile or account**: the public can no longer see the profile. If an owner's account is removed, all its locations are removed; if a manager's account is removed, the locations are not affected.
- **Content restrictions**, while the profile stays up: "Rejected business information edit" (name, category, address, phone, website), "Restricted media" (post, photo, video), and other content restrictions.
- "Soft" and "hard" suspension are not Google's terms. Rely on the decision shown in Google's appeals tool: date, reason, policy concerned, whether it can be appealed.

## Frequent causes

- **Name with extra words**: keywords, city, services, slogans. Google: unnecessary information in the name "could result in the suspension" of the profile.
- **Address the business cannot use**: P.O. box or remote mailbox, virtual office, co-working space without permanent signage, staff and customers during business hours.
- **Address shown by a business that does not receive customers**: a service-area business removes its address and sets a service area. A business needs in-person contact with customers during its stated hours.
- **Business not at the address, or not eligible**: lead generation agents, online-only businesses, rental or for-sale properties.
- **Identity changes**: Google may reject significant name or category changes. A new business at the same address gets its own profile; the old one is marked permanently closed, not renamed.
- **Many edits in a short time**: practice, not a published Google rule. Google reviews every edit and some changes trigger a new verification, so change one thing at a time and wait until it is live.
- **Account problems**: a restricted account suspends all the profiles it holds.

## Reinstatement path

1. Read the decision in Google's appeals tool and check the verification status.
2. Fix the profile first, so that it fully follows the guidelines: real name, eligible address (or address removed and service area set), accurate categories.
3. Gather evidence: business registration, business license, tax certificate, utility bill for the business (electricity, phone, water, internet). The business name and address on each document must match the profile.
4. If the account is restricted, appeal the account first from the My accounts page. Appeal the profile once the restriction is lifted.
5. Submit the appeal in the Google Business Profile appeals tool: select the profile and the decision, attach the evidence, explain briefly, submit.
6. Appeals can be submitted only once. Do not send several appeals for the same issue before getting a decision.
7. Google answers by email. Review can take up to 5 business days. Statuses in the tool: Submitted, Approved, Not Approved, Can't be appealed, Eligible for appeal.
8. If the appeal is denied, request an additional review only with new evidence. In the UK and the EEA, further redress options exist, including out-of-court dispute settlement.

For 10 or more suspended locations, the tool offers a bulk reinstatement request: a spreadsheet of the Business Profile IDs plus supporting documents.

## Never

- Never create a new profile for the same business. Google: "Do not create a new Business Profile for the same business."
- Never promise a reinstatement or a delay to the client.
- Never send documents whose name or address differs from the profile without explaining why.

## With the connector

- `get_listing_verification_status`: verified, pending, suspended or never verified. Read-only. Start here.
- `list_google_changes`: changes Google made itself to the listing (name rewritten, category changed, address adjusted). Look at what moved before the suspension.
- Fixes to name, address or categories are writes to Google: show the before/after and wait for an explicit "yes".
- The appeal is filed by the owner or manager in Google's appeals tool. Claude prepares the checklist and the short explanation; it cannot file the appeal.

## Without the connector

Ask for the notice received (screenshot), the current name, address and categories, and whether the business receives customers at its address. Find the likely cause in the list above, then give the fixes and the appeal steps.

## Sources

- https://support.google.com/business/answer/4569145 (Fix suspended or disabled profiles)
- https://support.google.com/business/answer/13597551 (Appeal Business Profile content & profile restrictions)
- https://support.google.com/business/answer/13762416 (Overview of Google Business Profile policies)
- https://support.google.com/business/answer/3038177 (Guidelines for representing your business on Google)
- https://support.google.com/business/answer/9157481 (Manage your service areas for service-area & hybrid businesses)
