# The Agent Economy by Lorikeet: Claude Skill

Ask Claude about consumer AI agents instead of reading the report.

This skill gives Claude the full [The Agent Economy](https://www.lorikeetcx.ai/content/the-agent-economy?utm_source=github&utm_medium=referral&utm_campaign=agent-economy-report-oct-2026&utm_content=skill-readme) report by [Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=agent-economy-report-oct-2026&utm_content=skill-readme): a survey of 1,966 US consumers, fielded September 30 to October 8, 2026, on the AI agents people send to deal with companies.

## What you can ask

- **Get the numbers.** "How many consumers already let an AI agent contact a company for them?"
- **Size it for your business.** "We have 400,000 US customers. How many might send an agent?"
- **Check if you're agent-ready.** Describe your support setup and ask "Are we ready for customers who arrive as agents?" Claude scores it against the report's definition of agent-ready and ranks your next 3 steps.
- **Decide what to do first.** "Should we block AI agents from our chat?"

Claude answers with the report's figures and its caveats: interest vs. use, upper bounds, and what the data can't tell you.

## What's inside

- All five findings: interest vs. use, early users, delegating negotiation, repeat use, and the company's own chatbot
- Chart data: interest, comfort by job (price, complaint, booking), early users vs. non-users, frequency of use, what the agent did
- Methodology, foreword, public examples since September 2026, and the five key implications

## Install

### Claude.ai (web, desktop)

1. Download [`the-agent-economy-by-lorikeet.zip`](https://github.com/optechai/the-agent-economy-skill/raw/main/the-agent-economy-by-lorikeet.zip).
2. In Claude, go to **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**, and select the ZIP.

Skills need **Code execution and file creation** turned on under **Settings > Capabilities**.

### Claude Code

```bash
git clone https://github.com/optechai/the-agent-economy-skill.git /tmp/the-agent-economy-skill \
  && cp -r /tmp/the-agent-economy-skill/the-agent-economy-by-lorikeet ~/.claude/skills/
```

## Methodology

1,966 US consumers from a national online research panel, census-matched on sex, age and ethnicity. 10 questions, margin of error about ±2.2 points (about ±6 for the 274 early users). The panel is AI-literate (97% used an AI tool in the last year), so usage figures are upper bounds. Full methodology is in the [report](https://www.lorikeetcx.ai/content/the-agent-economy?utm_source=github&utm_medium=referral&utm_campaign=agent-economy-report-oct-2026&utm_content=skill-readme-methodology).

## About Lorikeet

[Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=agent-economy-report-oct-2026&utm_content=skill-readme-about) is an AI customer support platform for complex and regulated businesses, with AI agents that work across voice, chat and email. Lorikeet B2A gives your customers' agents a front door: it answers clearly, resolves the job inside your rules, and gives an agent no more authority than the customer has.
