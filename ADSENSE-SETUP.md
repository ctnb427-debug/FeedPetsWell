# FeedPetsWell advertising handoff

This redesign prepares the public site for review; it does not activate ads or claim Google approval.

Implemented: mobile calculator, source/methodology page, original explanatory content, About, Contact, privacy/cookies, terms, veterinary/affiliate disclosures, real Gumroad product link, cover, sitemap, consent-gated existing Analytics ID.

Before requesting review / enabling advertising:

1. Confirm the Gumroad listing's current $7 price, currency and product description. The supplied cover is used unaltered; surrounding copy makes no treatment or savings guarantees.
2. Confirm the owner is comfortable using the public GitHub issue tracker for site feedback; a dedicated public support email would offer an easier private contact option. Never publish private contact information without authorisation.
3. Add `feedpetswell.com` as the site in AdSense. The custom domain is active and is the canonical address used by the live pages, sitemap and robots file.
4. Obtain the actual publisher ID / verification snippet from the user's AdSense account. Do not insert a fabricated publisher ID.
5. Configure Google's Privacy & messaging certified CMP (or another Google-certified CMP) for relevant visitors before activating advertising. The existing cookie dialog controls Analytics only; it is NOT a certified advertising CMP.
6. Add the publisher-specific ads.txt record at the serving domain ROOT, not merely at `/FeedPetsWell/ads.txt`. This generally requires the user-site repository or a custom-domain configuration. Verify the public root response.
7. Update privacy disclosures for the final ad partners / consent configuration and review the entire site against current Google Publisher Policies. Include the actual Google code only when account and consent configuration are ready.
8. Request review. Approval and revenue are not guaranteed.

References:
- https://support.google.com/adsense/answer/1348695
- https://support.google.com/adsense/answer/13554116

Verification: run a static web server and check cat/dog formula cases, food splits, metric/imperial conversion, invalid input, excluded health/weight situations, cookie choices, routes and responsive layout.
