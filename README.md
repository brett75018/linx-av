# Beginner onboarding prototype

Clickable prototype from a product design case study on **mobile life-insurance onboarding for a first-time saver** — someone who arrives already advised, having asked an AI assistant which contract to pick.

**[Open the prototype →](https://brett75018.github.io/linx-av/)**

- English — [`en.html`](en.html)
- Français — [`fr.html`](fr.html)

## What it shows

The prototype walks the funnel end to end and demonstrates five changes:

1. **A projection at the project step** — deposit, monthly payment and horizon on one screen, so the funnel gives something back before the recommendation.
2. **The saver's file, saved before the account** — an email is enough; resuming returns to the recommendation, not to the start.
3. **The declaration, wired** — "I need guidance" opens a channel that is actually available: an appointment out of hours, or chat support anytime.
4. **A recommendation that matches the source** — the contract the saver was already pointed to.
5. **The account split from the paperwork** — signing up and completing KYC become two separate moments.

## Running it

Each file is a single self-contained HTML document with no build step, no dependencies and no external requests. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Embedding it

Each page is frameable, so the prototype can be dropped into a portfolio page as a live, clickable phone:

```html
<div style="position:relative;width:100%;max-width:420px;margin:0 auto;aspect-ratio:390/800;">
  <iframe src="https://brett75018.github.io/linx-av/en.html"
          title="Beginner onboarding prototype"
          loading="lazy"
          style="position:absolute;inset:0;width:100%;height:100%;border:0;
                 border-radius:28px;box-shadow:0 20px 50px rgba(26,81,105,.18);"></iframe>
</div>
```

Sharing any of the three URLs in Slack, Claude or a social post unfurls the card in `og-image.png`.

## Disclaimer

Independent case study by Sébastien Brett. **Not affiliated with, commissioned by, or endorsed by LINXEA.** Product names and branding belong to their respective owners. Screens, figures and projections are illustrative and do not constitute financial advice.
