### Marcin Pakuła — AI Automation Engineer

I build process automations with language models that run in production: an email quoting agent, a sales assistant with human approval, a client for the Polish e-invoicing API. One-person business: [AtomFlow](https://atomflow.pl) (Opole region, Poland).

**Stack:** n8n (self-hosted) · OpenAI / Claude · Python · TypeScript / Node.js · React · Docker · nginx · Linux

| Project | What it shows |
|---|---|
| [ai-email-quote-agent](https://github.com/MarcinPakulaOff/ai-email-quote-agent) | n8n quoting agent in production: the LLM parses emails and drawings, deterministic code prices, the owner approves. Whole-thread memory, 30 tests |
| [ai-sales-assistant](https://github.com/MarcinPakulaOff/ai-sales-assistant) | Human-in-the-loop: the bot drafts, a human sends. Header-only mailbox scanner, Telegram approvals, privacy guard, consent rules |
| [ksef-api-client](https://github.com/MarcinPakulaOff/ksef-api-client) | KSeF API 2.0 with an XAdES-BES signature written from scratch (no libraries), FA(3) parser, monthly tax summary |
| [ai-job-radar](https://github.com/MarcinPakulaOff/ai-job-radar) | Daily job radar: a cheap model shortlists titles, code verifies every page (HTTP 200, JobPosting, not expired), a strong model scores, a guard checks drafted letters. Token cost in every report, 12 tests |

**Python automations** (each with tests and GitHub Actions CI, Python 3.10 / 3.12):

| Project | What it shows |
|---|---|
| [site-health-monitor](https://github.com/MarcinPakulaOff/site-health-monitor) | Uptime, SSL expiry and sitemap watchdog that alerts on change, not on every run (N failures in a row, one recovery message) |
| [gsc-seo-reporter](https://github.com/MarcinPakulaOff/gsc-seo-reporter) | Weekly Google Search Console report on Telegram: position moves, new queries, sitemap pages Google ignores. Service-account JWT auth |
| [offer-pdf-generator](https://github.com/MarcinPakulaOff/offer-pdf-generator) | JSON brief → priced offer PDF. Prices only from one pricing file, `Decimal` money, a brief cannot go below the price list |
| [ksef-xml-parser](https://github.com/MarcinPakulaOff/ksef-xml-parser) | KSeF FA(3) XML → typed records, CSV and monthly VAT totals, standard library only |

📫 kontakt@atomflow.pl · open to B2B or full-time, remote or near Opole
