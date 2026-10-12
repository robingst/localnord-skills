# Categories
Checked against Google's help pages on 2026-10-12.

## What the primary category does

- It tells people what the business is and helps Google show it in local search. Google's example: a primary category of "Pizza restaurant" can make a business appear for "Restaurants", "Italian restaurants" or "Pizza".
- It unlocks category-specific features: order, reservation and menu links for restaurants, a booking button and a services list for health and beauty businesses, class ratings and amenities for hotels.
- A profile has one primary category and up to 9 additional ones.
- A category is a description, not a ranking lever. Never promise a position from a category change.

## Choosing the primary category

- Describe the business as a whole. The category completes "This business IS a...", never "This business HAS a...".
- Take the most specific category that fits the main activity. Google's example: "Nail salon" rather than "Salon".
- If no specific category fits, take a more general one. Custom categories cannot be created.
- Do not pick a service, a product, an amenity or a keyword. Those belong in services, products, attributes or the description.
- Check the choice against what the business shows on its signage and website, and against what it actually sells.

## Secondary categories

- Use as few as possible. Each one must be a real line of business of this location.
- Google's example: a grocery store can add "Bakery" and "Deli" next to its primary category "Grocery store".
- Do not add one category per product or service.
- Do not use a category that belongs to another business at the same place. A restaurant inside a hotel, or an independently run cafe inside a gym, gets its own profile.
- An activity the business does not offer (yet) gets no category.

## Frequent mistakes

- **A service as the category.** A business that "has" a service is not that service. Keep the primary category on what the business is, and list services in the services section.
- **A category copied from a competitor.** What appears on a competitor's profile says nothing about what this business is. Start from the business itself. (Practice, not a Google rule as written.)
- **Piling up categories.** Adding loosely related categories to show up in more searches goes against Google's "as few as possible" guideline. Guideline violations can lead Google to restrict the profile.
- **Frequent switching.** Adding or editing a category may prompt Google to verify the business again. Google may also reject significant category changes that alter the business's identity.
- **A new business at the same address.** Do not recategorise the old profile: the old one is marked permanently closed and the new business gets its own profile.

## Before changing categories

1. Write the proposed list: primary first, then secondaries, one line of reason each.
2. Say what is removed and what is added compared with today.
3. Warn that the change may trigger a new verification.
4. Change only after the user's explicit "yes".

## With the connector

- `get_available_categories`: search Google's official list by keyword to find the exact category.
- `suggest_listing_categories`: proposes secondary categories already resolved to Google category ids, from the listing's name, primary category, services and website. It writes nothing. Keep only the ones that match a real activity, and have the user confirm each one.
- Changing categories on Google is a listing edit. Show the full before/after list and wait for an explicit "yes" before any write to Google.

## Without the connector

Ask for the business type, its main services, its website and its current categories. Propose one primary category and only the secondaries that match real activities, with the reason for each, and say the change is made in Google Business Profile, under Edit profile, Business category.

## Sources

- https://support.google.com/business/answer/7249669 (Manage your business category)
- https://support.google.com/business/answer/3038177 (Guidelines for representing your business on Google)
- https://support.google.com/business/answer/3039617 (Edit your Business Profile)
- https://support.google.com/business/answer/13762416 (Overview of Google Business Profile policies)
