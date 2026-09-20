# **Tax Transformation and Tax Compliance: Global Perspectives**

## **Slide 1 — Title**

**On slide**

5th International Conference on Fiscal Policy and Economic Development

Tax Transformation: Its Impact on Taxpayers and Tax Authorities

## **Tax Transformation and Tax Compliance: Global Perspectives**

Three trends reshaping the tax function

Dr Aleksandra Bal

21 – 23 September 2026

**Speaker notes**

Good morning, everyone. Over the next 30 minutes, I'll share an industry perspective on tax transformation: the view from the private sector.

I lead the indirect tax technology team at Stripe. For those who don't know Stripe, we're a payments company. Businesses running on Stripe generated 1.9 trillion dollars in payment volume last year — roughly 1.6% of global GDP. Stripe has around \[11,000\] employees, and an office here in the region, in Dubai.

What's less known is that Stripe builds its own tax technology. Our product handles indirect tax across more than 100 countries and over 13,000 US jurisdictions.

So I sit at the intersection of tax and technology, with degrees in both. Outside work, I'm passionate about sharing what I learn, especially about AI and tax, which I write about on my blog, Tax Engineer.

---

## **Slide 2 — Agenda (1 min)**

**On slide**

## **Three Trends Reshaping the Tax Function**

1. **Rapid growth and scale** — global from day one  
2. **Real-time controls** — right the first time  
3. **AI** — changing how tax departments work

Then: three use cases — where AI helps, and where it doesn't

**Speaker notes**

I'll talk about three trends. The first two are pressures: companies go global faster than ever, and tax administrations are moving to real-time controls. The third is AI. I'll mention it as a trend in its own right because of its importance, but my real focus is how AI can help tax teams deal with the first two. Implementing AI is not an objective on its own. It should support the tax transformation.

I'll look at all of this from the company perspective: what these trends mean for a business that has to comply with them. But I'll finish with a message for the tax administrations in the room: a short wish list of what tax administrations can do to help companies succeed in this new world, one that is changing fast and increasingly shaped by AI.

---

## **Slide 3 — Trend 1: Rapid Growth and Scale (3 min)**

**On slide**

## **Global From Day One**

|  | AI companies | SaaS companies |
| ----- | ----- | ----- |
| Countries, year 1 | 55 | 25 |
| Countries, year 2 | 79 | 42 |

* Self-serve signup: customers land anywhere  
* Nil thresholds: one customer can trigger registration  
* Tax exposure before the first finance hire

*Source: Stripe, Indexing the AI economy (top 100 AI companies on Stripe, median)*

**Speaker notes**

Imagine an AI startup that launches on Monday. By Friday, it has customers in 30 countries — and tax obligations in some of them.

That isn't far-fetched. The median top AI company sells in 55 countries in its first year and 79 in its second — roughly twice as many as SaaS companies at the same stage.

Why? AI products grow through frictionless self-serve signup. The first international customers can land in jurisdictions nobody in the company has thought about. At the same time, a growing number of countries impose tax obligations on foreign sellers with nil registration thresholds. A single customer can be enough.

The consequence: an AI company can trigger tax registration obligations in dozens of countries before it hires its first finance person. Tax is something to consider from day one.

---

## **Slide 4 — Trend 2: Real-Time Controls (3 min)**

**On slide**

## **Right the First Time**

* The invoice goes to the tax authority as it's issued  
* A correct invoice needs correct tax determination  
* No invoice, no revenue: tax is business continuity  
* Tax: from gatekeeper to system architect

**Speaker notes**

The second trend is the move to real-time controls, and e-invoicing is at the centre of it. Qatar is preparing to introduce e-invoicing, so this is directly relevant here.

The invoice becomes the most important artifact in the compliance cycle. It is something you cannot get wrong, because it goes to the tax administration in real time.

An invoice can't be accurate without correct tax determination. So real-time reporting makes getting the tax right more urgent, not less.

And this changes what tax is about. In clearance models, an invoice the system rejects may not be validly issued at all. If you can't issue an invoice, you can't bill your customers, and you don't get paid. No business can operate like that for long. So tax is no longer only a compliance issue. It is a business-continuity issue.

Key message: compliance is no longer limited to the tax department. It sits inside billing systems and the enterprise financial architecture. The tax function is no longer a gatekeeper that checks at the end. It is a system architect — an elevated role within the business.

---

## **Slide 5 — Trend 3: AI (2 min)**

**On slide**

## **Where AI Actually Is Right Now**

* New models every week  
* Open-weight models: good enough, far cheaper  
* From assistive to autonomous  
* AI is a means, not the goal

**Speaker notes**

Tax departments are not strangers to technology — robotic process automation, tax engines. What's new is generative AI: models that can work with unstructured, multilingual information like legislation, guidance and official announcements.

The pace is remarkable. \[Refresh before the talk: number of major model releases in the last few weeks.\] Open-weight models are now good enough for many tasks at a fraction of the cost — \[refresh: e.g., "up to 10–100 times cheaper than frontier models"\]. And we're moving from assistants that answer questions to agents that plan and act.

But the model isn't what changes your work. How you use it is. So let me show you three use cases — including one where AI should not be used at all.

---

## **Slide 6 — Use Case 1: Tax Determination (3 min)**

**On slide**

## **Tax Determination: Not an AI Problem**

* Same input, same output — every time  
* Rules are jurisdictional; models blend them  
* A wrong answer looks exactly like a right one  
* Use rules, not generative AI or agents

**Speaker notes**

Link to trend 2: this use case is about real-time controls.

Tax determination — calculating the right tax on a transaction — is where I'd say AI should not be used. The outcome must always be the same for the same facts. It must be auditable. And under real-time controls, it must be right before the invoice leaves.

Generative AI and agents can produce a different outcome every time. Models blend rules from different jurisdictions. They recall rates and thresholds rather than looking them up. And a wrong answer looks exactly like a right one. Fluency is not authority.

Tax determination is a workflow. It needs a rules-based system.

---

## **Slide 7 — Match the Tool to the Task (1 min)**

**On slide**

## **Match the Tool to the Task**

| Workflow | AI workflow | Agent |
| ----- | ----- | ----- |
| Fixed steps, every time | Fixed steps, one uses AI | A goal, not a path |
| Predictable | Handles the messy part | Plans and acts |
| Breaks on exceptions | Stays auditable | Different route each run |
| *Tax determination* | *E-invoicing* | *Regulatory monitoring* |

**Speaker notes**

This gives us a simple principle: match the tool to the task.

On the left, workflows: fixed steps, fully predictable. That's tax determination. In the middle, AI workflows: the same fixed steps, but one step uses AI to handle the messy part. The process stays auditable. On the right, agents: you give them a goal, and they decide the route.

Most tax work is a workflow with one hard step. The conference circuit tends to jump straight from spreadsheets to agents, but the middle column is where most tax teams should be working. The next two use cases fill in the middle and the right.

---

## **Slide 8 — Use Case 2: E-Invoicing (4 min)**

**On slide**

## **E-Invoicing: Rules First, AI for the Unknown**

* Schema validation: rules — the answer is known  
* Anomaly detection: AI finds what rules can't anticipate  
* Unstructured invoices: AI reads them and extracts the data

**Speaker notes**

Also a real-time controls use case. E-invoicing shows all three tools working side by side.

First, schema validation. Checking whether an invoice meets the e-invoicing schema is a rules problem. The schema is defined; either the invoice complies or it doesn't. Rules are more reliable here, and there is no reason to use AI.

Second, anomaly detection. You can't write a rule for an anomaly you can't predict. That's where AI is strong: analysing large volumes of invoice data and finding patterns. \[Add 1–2 examples, e.g., a tax code that is unusual for this customer type, a sudden spike in credit notes, or invoice totals that don't reconcile with the periodic return.\] A precision point: much of this pattern detection is classical machine learning and statistics rather than generative AI. Generative AI adds value on top, for example by explaining why an invoice was flagged.

Third, unstructured data. Not every invoice arrives as structured data, especially during the transition to e-invoicing: PDF or scanned invoices from suppliers, and related documents such as contracts or emails. AI can read these documents and extract the data. The extracted data then goes back through the same rules-based validation.

So e-invoicing is not rules versus AI. It's a workflow with rules at the core and AI at the steps where the input is messy or the problem can't be anticipated.

---

## **Slide 9 — Use Case 3: Regulatory Change and Expansion Readiness (6 min)**

**On slide**

## **No Specialist in Every Country**

* Fast expansion outpaces tax hiring  
* AI monitors change and maps new obligations  
* Grounded in official sources, not model memory  
* Different regions, different problems

**Speaker notes**

Link to trend 1: this use case is about global expansion.

*Fast expansion outpaces tax hiring.* If you're an AI company, you sell to many countries and you expand quickly. You will not hire a tax specialist for every country you operate in. But you still need to know when rules change, and when a new customer creates a new obligation.

*AI monitors change and maps new obligations.* AI can help with monitoring developments, understanding them and providing context. It can also flag where new customers may be creating registration obligations. This is where the model is closest to an agent: the sources are unstructured, multilingual and constantly changing.

*Grounded in official sources, not model memory.* What makes this reliable is the system around the model, not the model alone. The model only knows what you put in front of it. So you feed it official sources rather than relying on what it remembers from training, and you tell it to answer only from those sources and to say when the answer isn't there. \[Optional, for technical audience members: this is what context engineering means in practice.\] A tax specialist still reviews the result before anything changes in production.

*Different regions, different problems.* An interesting observation: how well this works depends on the region.

* Asia-Pacific is the hardest. AI still struggles with jurisdictions that don't publish in English, and in some cases with non-Latin scripts. Getting reliable information is very difficult. \[Choose examples carefully: Malaysia and Vietnam work as examples of non-English sources; for non-Latin scripts, use e.g. Thailand, China, Japan or Korea.\]  
* We don't have that problem with the European Union.  
* The United States is a different type of problem: volume. There are around 13,000 taxing jurisdictions, with \[number — confirm source\] rate changes per year, plus boundary changes.

The US also shows how big a single change can be. From 1 January next year, California will tax SaaS and electronically delivered prewritten software, under SB 122 signed in June 2026\. Colorado starts taxing SaaS on the same date. California is the largest economy in the United States, larger than most countries, and AI tools are generally treated as prewritten software. For AI companies, that is a major change, with only about six months between enactment and the effective date. This is exactly the kind of development monitoring has to catch early.

---

## **Slide 10 — What This Means for Tax Administrations (2 min)**

**On slide**

## **A Wish List for Tax Administrations**

* Machine-readable rates, rules and schemas  
* Rules in PDFs must be parsed and interpreted first  
* One consolidated, consistent source of truth  
* Help technology so it can help businesses

**Speaker notes**

For businesses, the message of the three use cases is simple: build the rules layer first, and add AI where the rules run out. Match the tool to the task.

But businesses can't do this alone. So, as promised, I'll finish with a wish list for tax administrations.

*Machine-readable rates, rules and schemas.* Publish them as data that systems can use directly. In the United States, some states publish rate updates in a way machines cannot process cleanly. For example, instead of publishing exactly which rate changes, they publish the combined state plus county rate, so businesses must reverse-engineer each component. The same applies to e-invoicing: stable, clearly versioned schemas, and consistency between real-time and periodic reporting.

*Rules in PDFs must be parsed and interpreted first.* When rules are published only as documents, every business has to read them, extract the rule and translate it into its systems before it can apply it.

AI can help extract information from these documents, as we saw in the monitoring use case. But every extraction adds cost and delay, and every interpretation is a chance to get it wrong — multiplied across every business that has to do the same work.

*One consolidated, consistent source of truth.* It often gets harder still. The rules are spread across multiple PDFs: the original law, amendments, decrees, guidance notes, FAQs. There is no consolidated version, so every business has to piece together what the current law actually is. And sometimes those documents don't agree with each other. What we need is one consolidated, up-to-date version of the law, and one source of truth that is consistent: the legislation, the guidance, the rate tables and the e-invoicing schema should all say the same thing. When invoices go to the tax administration in real time, businesses have to be right the first time, and they can only do that if the rules themselves are clear.

*Help technology so it can help businesses.* Countries designing e-invoicing now, like Qatar, have an opportunity to get this right from the start. Technology can do a lot, but humans should not work against it. Help technology, so that technology can help businesses.

Thank you.

---

## **Sources**

* [Indexing the AI economy — Stripe (PDF)](https://assets.stripeassets.com/fzn2n1nzq965/1MsdRUHsQdAU6lT1b3zU0f/ae4800e3c9c8da779a52ee3955d80654/Indexing_the_AI_economy_EN-GB.pdf) — 55/79 countries (AI) vs 25/42 (SaaS)  
* [Indexing the AI economy — Stripe guide](https://stripe.com/guides/indexing-the-ai-economy)  
* [PwC — California imposes sales and use tax on digital products and SaaS](https://www.pwc.com/us/en/services/tax/library/california-imposes-sales-and-use-tax-on-digital-products-and-saas.html) — SB 122 signed 29 June 2026, effective 1 January 2027  
* [CLA — SaaS sales tax rules in California and Colorado](https://www.claconnect.com/en/resources/articles/26/saas-sales-tax-california-colorado) — Colorado effective 1 January 2027  
* [Anrok — California SB 122](https://www.anrok.com/resources/california-sb-122-heres-what-software-companies-need-to-know-before-the-deadline) — AI tools treated as prewritten software

