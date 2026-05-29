# Ramble University Launch Checklist

This checklist turns the Ramble University website into a simple revenue path.

## Current public pages

- Home: `https://rambleuniversity-png.github.io/`
- Shop: `https://rambleuniversity-png.github.io/shop.html`
- Thank-you page: `https://rambleuniversity-png.github.io/thank-you.html`

## What is already built

- Branded home page with Ramble University positioning.
- Shop page for digital printable products.
- Thank-you page for Formspree redirect after email signup.
- Product sections for:
  - Ring the Alarm
  - The Space Between
  - The Inner House / Personal Governance
- Soft-launch fallback email links.
- Gumroad, Etsy, and Payhip placeholder button areas.

## Email capture

The user has a functional Formspree account associated with:

- `carla.henson360@gmail.com`
- `etheircosmos@gmail.com`

To fully wire the site, paste the Formspree endpoint into the shop page. It should look like:

`https://formspree.io/f/xxxxxxx`

Once the endpoint is available, update the email capture section in `shop.html` so the form action points to that endpoint and includes this hidden redirect:

`_next=https://rambleuniversity-png.github.io/thank-you.html`

## Fastest money path

1. Publish `Ring the Alarm` first on Gumroad or Payhip.
2. Add the live checkout URL to `shop.html`.
3. Publish the same product on Etsy for search traffic.
4. Link all bios/social posts to `https://rambleuniversity-png.github.io/shop.html`.
5. Use the email capture form to collect waitlist subscribers for Personal Governance.

## Suggested pricing

- Ring the Alarm: $9 to $17
- The Space Between: $12 to $24
- Personal Governance / The Inner House: waitlist first, then $27+ for a fuller workbook or course pathway

## Product listing checklist

For each product, prepare:

- Final PDF
- Cover image
- 5 to 10 mockup images
- Short description
- Long description
- Keywords and tags
- Digital download/refund note
- Link back to the Ramble University shop page

## Replace staged seller links

In `shop.html`, replace these placeholder links once products are live:

- `https://gumroad.com/`
- `https://www.etsy.com/`
- `https://payhip.com/`

## Stronger CTA after first product is live

Once there is a live checkout URL, change the main call-to-action from soft-launch language to direct sales language:

- Buy Ring the Alarm
- Download the printable
- Get the cryptogram collection

## Notes for future assistants

Keep Ramble University focused on:

- Reflective printable products
- Wonder Department puzzle and symbolism tools
- Personal Governance as the signature framework
- Emotional Sovereignty as a bridge product
- Warm, intelligent, imaginative brand language
- Practical next steps toward revenue
