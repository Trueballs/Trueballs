# Oscar Wold Skaarderud

**I build production AI tools by steering agents — then review the output critically and own the quality of what ships.**

Business Management, Innovation & Entrepreneurship student at the University of Reading (Henley Business School), based in Oslo. I don't hand-write most of the code — I direct AI agents (Claude Code, n8n, custom pipelines) to build real things, and I'm the one accountable for whether they actually work in front of a customer.

---

## Featured

### 🧾 Pennbridge Order Desk — AI purchase-order desk with a human in the loop
Reads orders from email + PDF, extracts them with Gemini, validates every line against a catalogue and agreed prices, and creates an Odoo draft quotation **only after a person approves**.
- **25/30 emails + 6/6 PDFs** correct on a held-out set written separately from the prompt
- ~**$0.004 / order**, median **1.7 s**; the model never auto-approves — every error is flagged to review
- CI: **101 unit + 84 DB + 9 browser tests**; one-script install, TLS, nightly backups, OAuth2 mailbox
- Verified live end-to-end: real Gmail order → Gemini → human approval → Odoo draft quotation

### 🎨 [Vi Lager Kunst](https://vilagerkunst.no) — AI-to-handpainted art (live startup)
Full-stack app I built and run: a customer describes an idea, AI visualises it, a real artist paints and ships it. React + TypeScript + Supabase (Postgres, Edge Functions, Auth, Storage, RLS, 20+ migrations) + Stripe + OpenAI/Gemini.

---

## Automation I've shipped (private — client / internal)
- **Ably — internal growth automation.** An autopilot outreach engine across **Gmail + Monday CRM + Apollo + n8n + custom agents**: dedupe against the CRM, AI-personalised emails in two formats with an A/B split, paced sending, every send logged back to Monday. Plus an AI content/LinkedIn engine with quality gates and anti-repetition.
- **n8n workflows** for recurring operations.

*(Private because they hold client data and live API keys — happy to walk through the architecture in a call.)*

---

## How I work
Find an idea → build it end-to-end with AI as the sidekick → test it against the market → make an honest call to scale it or kill it. Several of my projects were deliberately shelved once the market said no; I treat that as part of the job, not a failure.

## Stack
`React` · `TypeScript` · `Next.js 16 / React 19` · `Supabase / Postgres` · `n8n` · `Claude Code (MCP, sub-agents, hooks, skills)` · `OpenAI / Gemini / Claude` · `Monday` · `Apollo` · `Stripe` · `Playwright` · `Vercel / Cloudflare / Firebase`

📫 oscar.wold.skaarderud@gmail.com
