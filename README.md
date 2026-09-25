# SideQuest site

Pre-launch waitlist page for SideQuest. Static `index.html` and `styles.css`. Coming soon on iOS.

## Do not publish yet

Founder has not given a go-ahead. Leave this unpublished: no GitHub Pages, no hosting, no domain.

The page sends `noindex, nofollow`. Remove that robots meta when it is time to publish.

## Waitlist form

Both email forms post to Formspree:

`https://formspree.io/f/REPLACE_ME`

`REPLACE_ME` is a placeholder. This repo does not contain a real Formspree id. Swap it in before the list can accept mail. Loops is not used. Until that swap, submitting the form says the waitlist isn’t connected yet.

When Formspree accepts a post, the page shows: “You’re on the list. We’ll write when there’s something real to try.”

## UTM fields

If the page URL includes them, these query params are copied into hidden fields on both forms: `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`, `utm_term`. Empty params stay empty. Expected paid values, for when a campaign exists:

| Param | Expected value |
| --- | --- |
| `utm_source` | `meta` |
| `utm_medium` | `paid_social` |
| `utm_campaign` | `sq_waitlist_tlv_v1` |
| `utm_content` | `script_a` or `script_b` |
| `utm_term` | `tlv_broad_2544` |

## Meta Pixel

Commented stub only, with placeholder `META_PIXEL_ID`. The pixel script is not loaded. PageView and Lead each run once, only after a successful Formspree submit, not on page load.

## Local preview

Open `index.html` in a browser. No build step.

## Copy

Visible copy follows Founder-approved draft v1 (2026-09-25). Outing memory is called field notes. The wordmark is SideQuest, one word, and it is not the page H1.
