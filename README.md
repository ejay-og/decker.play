# Decker.Play

> Turn your restaurant TVs into a revenue stream.

Decker.Play ships a free plug-in HDMI TV Box that turns any TV in your venue
into a programmatic DOOH ad screen and digital signage system. Restaurants
keep **65%** of ad revenue. No contract, no monthly fees.

Currently launching in **Los Angeles**.

---

## How it works

1. **Get your TV Box** — order online. Plug the HDMI box into any TV, connect
   wifi through the app.
2. **Set your content mix** — choose the ratio of paid brand ads vs. your own
   content (menus, specials, happy hour promos, Instagram, live sports).
3. **Get paid monthly** — brands bid on your screen time automatically through
   established DSPs. Payouts hit your account every month.

## What's included

- **Digital signage** — full CMS for menus, specials, events, Instagram feed,
  live sports & odds. Works even at 0% ad fill.
- **Smart content tools** — templates for daily specials, happy-hour
  countdowns, Instagram feeds, live scores, events. Edit from your phone.
- **Programmatic monetization** — ads delivered through the same pipes as
  digital billboards and CTV. No sales calls.
- **Brand safety & control** — set your ad-to-content ratio, block
  categories, never a blank screen.
- **Earnings dashboard** — real-time impressions, revenue, proof-of-play
  logs, next payout.

## Earnings (illustrative)

| Venue           | TVs | Visitors/day | Est. monthly earnings |
| --------------- | --- | ------------ | --------------------- |
| Small cafe      | 1   | ~80          | $30–$60               |
| Casual dining   | 2   | ~200         | $250–$400             |
| Popular spot    | 2   | ~400         | $800–$1,200           |
| Sports bar      | 4   | ~700         | $2,500–$3,500         |

Estimates assume ~45% fill rate with a third-party SSP. Actual earnings depend
on location, foot traffic, and screen count. Revenue share: you keep 65% of
net ad revenue, paid monthly.

## For brands & agencies

Decker.Play inventory is accessible through the DSPs you already use — no new
tools, no new workflows:

> The Trade Desk · Google DV360 · StackAdapt · Amazon DSP · Yahoo DSP ·
> Basis (Centro) · Vistar · Broadsign Ads · 30+ more

Target by geography, venue type, time of day, day of week, and audience.
Dynamic creative updates in real time based on weather, local events, and
inventory.

## Decker.Play vs. traditional screen providers

|                      | Decker.Play                        | Traditional providers            |
| -------------------- | ---------------------------------- | -------------------------------- |
| Hardware             | TV Box plugs into your own TVs     | $500–1,500 proprietary screen    |
| Revenue share        | You keep 65%                       | You keep $0                      |
| Setup                | Self-serve — plug in and go        | Rep + scheduled install          |
| Contract             | None — unplug anytime              | Multi-year agreements            |
| Screen orientation   | Any TV you already own             | Provider's vertical screens only |
| Content control      | You set the ad-to-content ratio    | Provider controls the screen     |
| Monthly fees         | $0                                 | $0 (but no earnings for you)     |

## Repository contents

This repo hosts the static marketing site. Pages are self-contained HTML
with inlined CSS and assets — no build step.

```
pages/
├── decker-play-landing.html      # Main marketing / landing page
├── decker-play-get-started.html  # Signup form
├── decker-play-thank-you.html    # Post-signup confirmation
├── decker-play-privacy.html      # Privacy Policy
└── decker-play-terms.html        # Terms of Service
```

### Preview locally

```bash
cd pages
python3 -m http.server 8000
# open http://localhost:8000/decker-play-landing.html
```

Any static host (GitHub Pages, Netlify, Vercel, S3+CloudFront) can serve the
`pages/` directory as-is.

## Contact

- Email: team@deckerapp.com

---

&copy; 2026 Decker
