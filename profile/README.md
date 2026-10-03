# Formgong

**Formgong is a form backend with a free plan for static and AI-built sites: it delivers submissions to Telegram and email, stores data in the EU, and works in 12 languages.**

Point a form at one URL, and submissions arrive by email, in Telegram and in a web inbox. You don't need a server, a database or email code.

- 📬 Email and Telegram delivery on every plan, including Free. Telegram connects with one button, with no bot token or chat id.
- 🔗 Signed JSON webhooks (HMAC-SHA256, up to 5 delivery attempts), with step-by-step recipes for [Make, n8n, Zapier and KeyCRM](https://formgong.com/en/integrations/).
- 🇪🇺 Data stored in the EU. A standard Art. 28 DPA is part of the [Terms](https://formgong.com/en/terms/).
- 🛡️ Spam protection with no CAPTCHA puzzle and no cookies: a honeypot, cookie-free checks and optional Cloudflare Turnstile.
- 🌍 The thank-you page, errors and auto-reply follow the visitor's language, in 12 languages.
- 🗂️ [Projects for agencies and freelancers](https://formgong.com/en/for/agencies/): up to 100 client projects, view-only client invites, handover to the client.

- 🌐 Website: https://formgong.com
- 📚 Docs: https://formgong.com/en/docs/
- ⚖️ Compared with other form backends: https://formgong.com/en/compare/
- 🤖 MCP server for Cursor, Claude, VS Code, Lovable and Bolt (official MCP Registry: `com.formgong/mcp`): https://formgong.com/en/docs/mcp/ · [repo](https://github.com/formgong/mcp)
- 🧩 Integrations: https://formgong.com/en/integrations/
- ✉️ support@formgong.com

## Starters

| Repo | Stack |
| --- | --- |
| [html-starter](https://github.com/formgong/html-starter) | Plain HTML form, no JavaScript |
| [nextjs-starter](https://github.com/formgong/nextjs-starter) | Next.js App Router client component |
| [astro-starter](https://github.com/formgong/astro-starter) | Static Astro site with progressive enhancement |
| [react-contact-form](https://github.com/formgong/react-contact-form) | One React + Tailwind file for Lovable, Bolt and v0 |

## npm

All packages are MIT and live in [formgong/js](https://github.com/formgong/js).

- [`formgong`](https://www.npmjs.com/package/formgong): `npx formgong init` creates a form and adds a contact form to your Next.js, React, Vue, Svelte, Astro, Angular or HTML project
- [`create-formgong`](https://www.npmjs.com/package/create-formgong): `npm create formgong@latest` scaffolds any starter above
- [`@formgong/core`](https://www.npmjs.com/package/@formgong/core): tiny typed client for the browser, Node, Deno, Bun and edge runtimes
- Framework packages: [`@formgong/react`](https://www.npmjs.com/package/@formgong/react), [`@formgong/next`](https://www.npmjs.com/package/@formgong/next), [`@formgong/vue`](https://www.npmjs.com/package/@formgong/vue), [`@formgong/svelte`](https://www.npmjs.com/package/@formgong/svelte), [`@formgong/astro`](https://www.npmjs.com/package/@formgong/astro), [`@formgong/angular`](https://www.npmjs.com/package/@formgong/angular)

## Prompts for AI builders

Copy-paste prompts that make the builder add a working form, with no Supabase, Edge Function or email service: [Lovable](https://formgong.com/en/docs/lovable/) · [Bolt](https://formgong.com/en/docs/bolt/) · [v0](https://formgong.com/en/docs/v0/) · [Cursor](https://formgong.com/en/docs/cursor/) · [Replit](https://formgong.com/en/docs/replit/) · [Base44](https://formgong.com/en/docs/base44/) · [ChatGPT / Claude](https://formgong.com/en/docs/chatgpt-claude/)

Free plan: 300 submissions/month and unlimited forms. Pro from $5/month ([pricing](https://formgong.com/en/#pricing)).
