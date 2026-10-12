# Reviews

## Reply to pending reviews

1. Get the listing id with `list_listings` (`search` with the business name).
2. `list_reviews` with `filters: { replyState: 'unreplied', requireComment: true }` (oldest first). Mention rating-only reviews separately: they need no text reply.
3. `generate_review_replies` for the listing: it saves internal drafts and never overwrites an existing draft. `tone`: professional by default, warm for a neighbourhood business. For a crisis: `filters: { maxRating: 2 }` and `sort: 'lowest_rating_first'`. Always pass `language` with the language of the reviews (fr, en, es or de): without it, the drafts come out in French. For another language, write the drafts yourself.
4. Show every draft: author, rating, review excerpt, proposed reply, and its validation warnings (links, prices or emojis that Google may reject). Edit on request with `save_review_reply_draft`.
5. Ask: "Do I publish these N replies?" Only after "yes", call `reply_to_review` for each approved review (it uses the saved draft). Set `overwrite: true` only when the user asks to replace an existing reply.
6. Report: published, failed (with the reason), skipped.

What a good reply contains, and what Google forbids: [../gbp/reviews-rules.md](../gbp/reviews-rules.md).

## Wave of negative reviews

1. `list_reviews` with `filters: { maxRating: 2 }` and `sort: 'published_at_desc'`: look at dates and authors.
2. `detect_fake_reviews`: suspicion score and reasons. A signal, never proof.
3. For each review the user wants to flag, after "yes": `flag_review_removal` with the reason. It deletes nothing: give the user the Google link it returns so they finish the flag by hand.
4. Reply calmly to the genuine negative reviews with the steps above (professional tone, offer an offline contact).

## Without the connector

Ask the user to paste the reviews (rating, text, date) with the business name and type. Write the replies with the same rules, and say they must be posted from Google Business Profile.
