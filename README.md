# Founder Growth Agent

> AI-powered founder-led B2B growth strategist for solo founders and early-stage teams. Positioning, messaging, content, and outreach strategies — organic, $0-budget B2B growth.

**Live:** https://founder-growth-agent.vercel.app | **Docs:** [SELL.md](./SELL.md) | **Strategy:** [MARKETING.md](./MARKETING.md) | **Demo:** [DEMO_SCRIPT.md](./DEMO_SCRIPT.md)

---

## What This Does

Build a personalized **B2B growth strategy** in minutes. Get:

- 🎯 **Positioning & Messaging** – Clarify what you do so people understand
- 📧 **Cold Outreach Templates** – DM/email sequences that convert
- 📝 **Content Strategy** – LinkedIn & X/Twitter playbooks
- 🎬 **7-Day Action Plans** – Step-by-step what to do first
- 📊 **CRM Integration** – Analyze your real pipeline (HubSpot, Salesforce, Pipedrive)
- ⚡ **Real-Time Streaming** – Instant responses as they generate

**Ideal For:**
- Solo SaaS founders getting first customers
- B2B service founders with zero marketing budget
- Bootstrapped startups (1–5 people)
- Anyone doing "founder-led growth"

---

## Quick Start

### 1. Clone and install

```bash
git clone https://github.com/21leahcimhtiek-oss/founder-growth-agent.git
cd founder-growth-agent
npm install
```

### 2. Set environment variable

```bash
cp .env.example .env.local
# Add your OpenAI API key:
# OPENAI_API_KEY=sk-...
```

### 3. Run dev server

```bash
npm run dev
```

Open http://localhost:3000

---

## Tech Stack

- **Next.js 16** — React framework
- **TypeScript** — Type safety
- **Tailwind CSS v4** — Styling
- **OpenAI SDK** — GPT-4o streaming
- **Vercel** — Deployment
- **Merge API** — CRM integrations (HubSpot, Salesforce, Pipedrive)

---

## Features Explained

### Founder-Specific Prompts
Pre-built prompts tailored to founder problems:
- "Help me get my first 10 B2B clients with no marketing budget"
- "Write a LinkedIn content strategy for a solo SaaS founder"
- "Build a cold DM sequence for a B2B service founder"
- "Sharpen my positioning: I help [X] do [Y]"
- "Create a 7-day founder-led growth action plan"

### Real-Time Streaming
Responses stream as they generate (not waiting for full response). See frameworks and templates *as they're being written*.

### CRM Integration (Starter+)
Connect your CRM and Founder Growth Agent analyzes your real contacts:
- Prioritizes who to reach out to
- Generates personalized outreach for each person
- Suggests follow-up timing and messaging

### Structured Outputs
Every response includes:
- **Frameworks** – How to think about the problem
- **Templates** – Ready-to-use copy and sequences
- **Action steps** – Specific things to do today

---

## Pricing

| Plan | Price | Features |
|------|-------|----------|
| **Free** | $0 | All core AI prompts, suggested strategies, no credit card |
| **Starter** | $9/month | CRM integration, personalized outreach, priority support |
| **Pro** | $29/month | Team collaboration, white-label option, advanced analytics |

See [SELL.md](./SELL.md) for complete pricing and sales information.

---

## Deployment

### Deploy to Vercel (Recommended)

1. Push this repo to GitHub
2. Go to https://vercel.com/new
3. Import the repository
4. Add `OPENAI_API_KEY` as an environment variable
5. Deploy

Your app will be live at `https://founder-growth-agent.vercel.app` (or custom domain).

### Manual Vercel CLI Deploy

```bash
cd founder-growth-agent
vercel
# Follow prompts, add OPENAI_API_KEY when asked
vercel --prod  # Deploy to production
```

See [DEPLOYMENT.md](./DEPLOYMENT.md) for more options.

---

## Documentation

- **[SELL.md](./SELL.md)** – Sales enablement, ICPs, competitive positioning, pricing strategy
- **[MARKETING.md](./MARKETING.md)** – Launch roadmap, content calendar, metrics, success criteria
- **[DEMO_SCRIPT.md](./DEMO_SCRIPT.md)** – Customer demo walkthrough (10 minutes)
- **[DEPLOYMENT.md](./DEPLOYMENT.md)** – Deployment instructions for Vercel and beyond

---

## Use Cases

- **Solo SaaS Founders** – "How do I get my first 10 paying customers?"
- **B2B Services** – "Build repeatable cold outreach playbooks"
- **Bootstrapped Startups** – "Founder-led growth with $0 marketing budget"
- **Indie Hackers** – "Launch strategies and positioning worksheets"
- **Startup Communities** – Use as community tool / white-label

---

## API Routes (for CRM integration)

- `/api/chat` – Main chat endpoint (POST)
- `/api/merge/link` – Get linked CRM accounts (GET)
- `/api/merge/accounts` – Get CRM accounts (GET)
- `/api/merge/contacts` – Get CRM contacts (GET)
- `/api/merge/leads` – Get CRM leads (GET)
- `/api/merge/opportunities` – Get CRM opportunities (GET)

---

## Support & Feedback

- 📧 **Email:** support@auroramarket.org
- 🐛 **Issues:** GitHub Issues
- 💬 **Community:** Aurora Rayes Slack
- 🎯 **Sales:** sales@auroramarket.org

---

## License

MIT — Aurora Rayes LLC

---

**Product ID:** founder-growth-agent | **Status:** MVP ✓ | **Part of:** Aurora Rayes Ecosystem\n\n## no-key-first security\n- Never commit API keys, secrets, or production credentials.\n- Keep runtime secrets only in local env files or deployment settings.\n- Use placeholder/test values in repository metadata and docs.\n- Keep paid checkout disabled by default until launch readiness is approved.\n