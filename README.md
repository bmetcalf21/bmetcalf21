# Brandon Metcalf

### Applied AI · Product Development · Workflow Automation

I turn messy workflows into working tools. My background is in technical operations and data quality, with a B.S. in Computer Science.

Most of my work now runs like a small product team with AI agents as the engineers: I decide what to build and what to cut, and the agents build it inside a system I designed and use every day.

## Recent work (private repos)

- **WhatsApp assistant and staff console for an orthodontic practice.** The owner wanted it to feel like talking to a person but never get a price wrong. Rules built from the owner's manuals and price lists decide what it can say, an LLM only writes the wording, and a final check rejects any price it finds that wasn't approved for that answer. When an earlier full rewrite stalled, an audit showed it was rebuilding parts that already worked; I narrowed the work to the missing piece, natural replies, and the new version was built, reviewed and on a test server the same day. It's validated against scenarios built from the owner's documents and 800+ automated tests, and staff review conversations, assign follow-up and keep notes in a separate console.
- **Grocery price comparison for Argentina.** I'm building a free, phone-first page that compares supermarket prices using the government's daily price data. A quick spike showed some chains' promotions can't be read publicly, so the first version shows their shelf prices and leaves those offers for later instead of waiting on them.
- **The system my agents work in.** Work goes out as small tasks on a board. Written rules set what agents can decide on their own and what comes to me, like spending or anything public. Review gets stricter as the risk goes up, and nothing counts as done until it's verified where it runs. I'm running two versions side by side, one with custom integrations and one built only from maintained tools and plugins, to see which custom pieces are worth their upkeep.

Source code and client material for these stay private. Happy to talk about or discuss any of them.

## Team experience

During a competitive internship with [InvestorMatch.ai](https://investormatch.ai/) that also served as my Oregon State capstone, I worked on a four-person team: I built FastAPI endpoints for the submission forms, storing data in PostgreSQL, and led the final technical report. The platform was live, with about 120 investors, founders and vendors in its database during the project.

## Open source

[Hermes Agent](https://github.com/NousResearch/hermes-agent), Nous Research's open-source agent framework, is one of the building blocks of my own system, and I contribute to it upstream: a [reproducible bug report](https://github.com/NousResearch/hermes-agent/issues/137428) and a [proposed provider-routing fix with regression tests](https://github.com/NousResearch/hermes-agent/pull/136274). Here are [all my reports and pull requests](https://github.com/NousResearch/hermes-agent/issues?q=author%3Abmetcalf21). I'm also approved for OpenAI's Daybreak Blue access and accepted into Anthropic's Cyber Verification Program for defensive security work.

## Public code

These portfolio projects use synthetic data or sanitized examples.

| Project | What it does |
| --- | --- |
| **[Data Integrity Validator](https://github.com/bmetcalf21/data-integrity-validator)** | Turns messy CSV feeds into cleaned datasets plus a list of rejected rows with the reason for each. Python/pandas with automated tests. |
| **[Support Operations Workflow Pack](https://github.com/bmetcalf21/support-qa-evidence-pack)** | Works out when a support assistant should answer, ask a clarifying question, or hand off to a person. Includes a local AI harness, citation checks, and a tested evaluator. |
| **[Azure Operations & Governance Lab](https://github.com/bmetcalf21/azure-ops-lab)** | Reproducible deployment, monitoring and teardown for a small Azure workload, with CI validation. |

[LinkedIn](https://www.linkedin.com/in/brandonfmetcalf)
