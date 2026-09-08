# Official links and URL preservation

| Purpose | Stable website address |
| --- | --- |
| Project | https://calorietoken.net/ |
| CalorieApp | https://calorietoken.net/index.php/calorieapp/ |
| Whitepaper page | https://calorietoken.net/index.php/whitepaper/ |
| Roadmap summary | https://calorietoken.net/index.php/roadmap/ |
| Buying guide | https://calorietoken.net/index.php/how-to-buy-calorie/ |
| Contact and current community channels | https://calorietoken.net/index.php/contact/ |

Use these existing website addresses for general references. A new document or visual design does not require changing their slugs. Current repository reading paths are [whitepaper/CalorieToken-Whitepaper.pdf](../whitepaper/CalorieToken-Whitepaper.pdf) and [roadmap/README.md](../roadmap/README.md). Use dated release paths for references to a particular edition.

## Preserving old references

- Existing `/index.php/` page URLs remain valid entry points; removing that prefix is a separate migration.
- An old page that has a clear successor can redirect to that specific successor. A retired service with no equivalent should retain a clear retirement explanation and suitable next steps.
- Historical PDF and image URLs may be referenced by third parties. Keep their source copies, or map them deliberately to an equivalent archive location.
- The website's existing current-whitepaper download address is intended to continue working when its reading copy moves to GitHub. Activate that redirect only after the repository PDF is published and verified.
- Version-specific historical references should remain distinguishable from a current-document alias. Record any exceptional alias in the release notes.
- Preserve useful page anchors and query parameters where they belong to the reading journey. Login, session, account and payment routes are outside document redirects.
- Validate a redirect before making it permanent. Preserve long-lived public aliases so external authors do not need to repair every old link.

The exact historical download presently used by the website's current-whitepaper button is:

`https://calorietoken.net/wp-content/uploads/2026/02/CalorieToken-Whitepaper-V3.1.docx.pdf`

Although its filename contains an old version, the website uses it as a current reading link. The historical contents are preserved separately in the [whitepaper archive](../whitepaper/archive/README.md).

## External descriptions

A working link and an accurate description are separate checks. Updating an external profile may still be useful when it describes an old prototype as a current product. For corrections, identify the exact project by its website and XRPL asset identity; the name “Calorie” or ticker “CAL” alone is ambiguous.

Reference: [Google's guidance on URL mappings, redirects and monitoring](https://developers.google.com/search/docs/crawling-indexing/site-move-with-url-changes).
