
## What is Sublix?

Sublix is a free, privacy-first subscription calculator that helps anyone track their monthly digital spending — no account required, no data stored on servers.

Add your subscriptions, set prices in any currency, and instantly see your total spending per month, per year, and per day.

https://www.sublix.org/ 
(sublix.org)

---

### OG Image / Social Preview
![Sublix Social Preview](https://sublix.org/og-image.png)


---

## Features

- **Smart logo detection** — type a service name and the logo appears automatically
- **Multi-currency support** — EUR, USD, GBP, RON with live exchange rates
- **Instant analytics** — monthly, yearly and daily totals updated in real time
- **PDF report generation** — download a clean, printable spending report
- **100% private** — all data stays in your browser, nothing sent to any server
- **Fully responsive** — works on mobile, tablet and desktop
- **No login required** — open and use instantly, like a calculator

---

## Supported Services

Sublix automatically detects logos for 100+ services including:

Netflix · Spotify · Claude · ChatGPT Plus · Figma · iCloud · Disney+ · YouTube Premium · Apple Music · Nintendo Online · Microsoft Office · Adobe · GitHub · Dropbox · and many more.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 16 + TypeScript |
| Styling | Tailwind CSS |
| Exchange Rates | open.er-api.com (live) |
| Logo Detection | Clearbit Logo API |
| PDF Export | jsPDF |
| Hosting | Vercel (free HTTPS) |
| Security | CSP headers, rate limiting, input sanitization |

---

## Privacy & Security

Sublix is built with privacy as the core principle:

- ✅ All subscription data stored exclusively in your browser session
- ✅ PDF reports generated locally, never uploaded anywhere
- ✅ Closing the browser clears all data automatically
- ✅ No cookies, no tracking, no analytics
- ✅ No account, no email required
- ✅ Strict Content Security Policy headers
- ✅ Rate-limited API routes
- ✅ Input sanitization on all fields
- ✅ No data ever sent to any server
- ✅ Permissions-Policy | Active |
- ✅ Nonce-based CSP | Active — per-request cryptographic nonces |

Sublix has been built and tested with security as a priority.

---

## SEO & Discoverability

- ✅ Google Search Console verified and active
- ✅ Sitemap submitted
- ✅ Open Graph metadata for social sharing previews
- ✅ Structured data (JSON-LD) for rich search results
- ✅ Indexed by Google — searchable at google.com

---

## Code Quality

- ✅ Full TypeScript strict mode — zero type errors
- ✅ Runtime type guards on all storage data
- ✅ ReDoS-safe regex patterns in middleware
- ✅ WCAG accessibility — aria labels, screen reader support
- ✅ Error boundaries on PDF generation
- ✅ Cache-Control headers on all API error responses
- ✅ Mathematically correct date calculations (365-day year)

---

### Infrastructure Security
| Protection | Details |
|---|---|
| HTTPS | Enforced at Vercel infrastructure level |
| HSTS | max-age=31536000 includeSubDomains preload |
| DNSSEC | Enabled via Namecheap |
| Firewall | Vercel Firewall active — DDoS mitigation |
| Bot Protection | Custom rules blocking malicious scanners |
| Rate Limiting | API routes protected against abuse |
| Input Sanitization | All user inputs sanitized server-side |
| CSP Nonces | Cryptographic nonces per request via middleware |
---


## Where to find it?

https://www.sublix.org/

---

© 2026 Sublix · All data stays in your browser · Made with pure dedication using Next.js & TypeScript
