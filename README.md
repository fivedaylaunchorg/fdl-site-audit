# fdl-site-audit

**Free small business website audit tool from [fivedaylaunch](https://fivedaylaunch.com).**

Grades any URL against 5 pillars that consistently separate small business sites that generate leads from ones that don't:

| Pillar | What it checks |
|---|---|
| **SSL** | HTTPS certificate present + valid, no mixed content warnings |
| **Mobile viewport** | `<meta name="viewport">` present, mobile-first CSS, tap targets sized correctly |
| **Form health** | Contact forms actually deliver — checks for common broken-form patterns (posts to `/wp-admin`, missing action, dead reCAPTCHA) |
| **Page speed** | First contentful paint under 2.5s on 4G, image compression, script blocking |
| **Schema markup** | `LocalBusiness` JSON-LD present with the specific subtype (Dentist, Restaurant, HairSalon) rather than generic Organization |

## Why these five specifically

We scanned 849,489 US small business websites while building [fivedaylaunch](https://fivedaylaunch.com). ~20% failed one or more of the above. The full findings are published in the [State of SMB Web 2026 report](https://fivedaylaunch.com/reports/state-of-smb-web-2026).

## Try it online

Free audit at [fivedaylaunch.com/tools/website-checker](https://fivedaylaunch.com/tools/website-checker).

## License

MIT. Use it, fork it, integrate it. If you build on top and want a mention on our tools page, [tell us](mailto:hello@fivedaylaunch.com).
