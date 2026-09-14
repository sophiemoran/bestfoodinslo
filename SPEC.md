# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page SLO restaurant picker that asks visitors what food, price range, atmosphere, and deal/review priorities they care about, then recommends matching places to eat.
- **Audience:** A hungry customer in San Luis Obispo who cannot decide where to eat or wants to discover a new place that fits their mood and budget.
- **Requirements:** One working quiz-style filtering interaction; recommendation cards show price range, food type, atmosphere, review/menu/deal information or links, and a short explanation of why each place matched.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Use only real restaurants that exist in or near San Luis Obispo. Do not include fictional, sample, placeholder, or made-up restaurants, reviews, ratings, deals, prices, menu items, or claims. Any menu, review, deal, or restaurant detail must come from a visible source link; if it cannot be verified, omit it or mark it unavailable. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Warm, cozy, bookstore-inspired design with deep green, cream, warm brown, and soft gold tones; the page should feel comforting and easy to browse, with recommendation cards that feel like curated staff picks.
- **Test:** I can answer the picker questions, get multiple real SLO-area restaurant suggestions, change one answer to see the results update, verify that each recommendation has source links for its claims, and point to my standing rule's effect in the preview.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
