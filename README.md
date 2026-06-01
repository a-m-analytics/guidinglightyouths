# Guiding Light Youth

A free, anonymous mental health resource site for teens.

No accounts. No sign-up. No data sent anywhere. Everything is stored locally in your browser.

**Live site:** [guidinglightyouths.github.io](https://guidinglightyouths.github.io) *(deploy via GitHub Pages — see below)*

---

## What it does

- **15 curated resources** — crisis lines, therapy finders, apps, hotlines, and more
- **4-row filter system** — filter by cost, format, topic, and who it's for
- **Search** — find resources by name or keyword
- **Detail panels** — click any resource to see full access instructions, hours, languages, and tips from other teens
- **Peer tips** — teens can anonymously post what to expect when accessing a resource
- **Community forum** — share your story (up to 1500 characters), read others, react with "this resonated"
- **Guides** — plain-language guides on anxiety, depression, talking to parents, finding free therapy, and more

---

## Tech

Single `index.html` file — no framework, no build step, no backend.

- Vanilla HTML, CSS, JavaScript
- [Fraunces](https://fonts.google.com/specimen/Fraunces) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- `localStorage` for peer tips and community stories
- Hash-based routing (`#home`, `#resources`, `#guides`, `#community`, `#about`)

---

## Deploy on GitHub Pages

1. Go to **Settings → Pages** in this repo
2. Set source to `main` branch, `/ (root)`
3. Save — the site goes live at `https://a-m-analytics.github.io/guidinglightyouths`

---

## Privacy

- No cookies
- No analytics
- No server — the site is 100% static
- Community stories and resource tips live only in the user's own browser (`localStorage`)
- Nothing is ever sent anywhere

---

## Resources included

| Resource | Type | Cost |
|---|---|---|
| 988 Suicide & Crisis Lifeline | Crisis | Free |
| Crisis Text Line | Crisis / Text | Free |
| The Trevor Project | Crisis / LGBTQ+ | Free |
| Teen Line | Peer support | Free |
| NAMI Helpline | Mental health info | Free |
| Open Path Collective | Therapy finder | Low-Cost |
| Psychology Today Finder | Therapy finder | Varies |
| BetterHelp | Online therapy | Subscription |
| Woebot | App / CBT | Free |
| SAMHSA National Helpline | Substance / mental health | Free |
| 7 Cups | Peer / chat | Free |
| MHA Screening | Self-assessment | Free |
| Trans Lifeline | Crisis / LGBTQ+ | Free |
| Love Is Respect | Crisis / relationships | Free |
| Headspace | App / mindfulness | Subscription |

---

## Disclaimer

Guiding Light Youth is not a therapist, crisis line, or substitute for professional mental health care. If you are in immediate danger, call 911 or go to your nearest emergency room.
