# real estate database reactivation: how to text a dead CRM list without hiring setters, plus the booking rate you should actually expect

Most agents searching this term are not looking for a philosophy of follow-up. They have a CRM with a few thousand names in it, a phone that already buzzes too much, and a vague memory that some of those people once asked about a house. The question is practical: what do I send, who do I send it to, how many do I send per day, and what happens when forty people reply at once on a Tuesday afternoon?

That last part is where most reactivation campaigns quietly die. Sending the first text is easy. Handling the conversations that come back is the actual job, and it is the reason so many agents abandon the campaign in week two.

## Why a reactivation campaign stalls at message one

There is a number worth memorizing from a real campaign. CloseBot ran a database reactivation against 1,486 of its own old contacts and published the funnel. Only 38% of the people who eventually replied did so after the first message. The average number of texts needed to get a response was two.

In other words, if you send one "hey, just checking in" text and stop when nobody answers, you are filtering out roughly two-thirds of the people who were going to reply. One follow-up the next day, and another the day after, is not aggressive. It is the minimum viable sequence.

The second bottleneck shows up later. Once replies start landing, you are running maybe twenty or thirty separate conversations with buyers, sellers, tire-kickers, and one guy who is annoyed you texted him at all. Each one needs a human-sounding answer within a few minutes, because a cold contact who replies and then waits six hours for a response is a cold contact again. That is the point where agents either hire an ISA at $2,000+ a month or let the campaign rot.

## The three segments worth texting first

Not everyone in your CRM deserves the same message. Roughly:

- **Past clients.** Highest trust, lowest friction. They already closed with you.
- **Cold inquiries from 6–18 months ago.** Open house sign-ins, portal leads, form fills that went nowhere. This is your core reactivation pool.
- **Genuinely old and unengaged contacts (18 months and up).** A one-off "are you still looking?" is fine. Then let them go.

Two groups to leave alone: anyone who opted out or asked you to stop (permanent, no exceptions), and contacts where you have no documented consent to text. Which brings up the unglamorous part.

> Under the TCPA, marketing texts generally require prior express written consent, even for past clients. Business texting also routes through 10DLC registration, and quiet-hour rules mean no texts before 8 a.m. or after 9 p.m. in the recipient's time zone. If your consent trail is murky, that is a conversation to have before you load a list, not after.

Practically, that means: run your sends through a registered number, keep them inside business hours, and make sure STOP is honored automatically rather than by whoever happens to read the reply.

## The campaign skeleton

The structure that works is boring and repeatable.

**Days 1–3: re-introduction.** Name yourself, reference the specific reason they are in your database, and ask one easy question. The goal is a reply, not a pitch. Something like: "Hi Dana, it's Marcus from Ridgeline Realty. You looked at a few places in Fairview last spring and then we lost touch. Still keeping an eye on the market, or has that ship sailed?"

**Days 4–10: something useful.** A street-level market update, a price change on a property they once saved, a short note about rates. This is where you earn the right to keep texting.

**Days 11–14: one low-friction ask.** A ten-minute call, a valuation, a time to walk a listing. Then a clean exit: "Want me to keep you on the neighborhood update list, yes or no?" A "no" is useful data, not a loss.

On pacing, there is a real campaign you can copy. CloseBot's own setup dripped 50 contacts per day, only between 9 a.m. and 6 p.m. Monday through Saturday, spaced one message every two minutes, with up to three touches per contact, one day apart. They noted they would not push past roughly 500 per day without reconsidering the spacing. That is a sane default whether a person or software is doing the sending.

## Where an AI agent fits, and where it does not

Here is the part most write-ups skip. CloseBot, the platform this guide is built around, does not send the first message. It is a responsive agent: you push the opening text out from your CRM or your automation, and the agent takes over the moment a contact replies. Their own documentation is explicit about that, and it is the correct division of labor. Drip infrastructure belongs in the CRM. Conversation handling belongs in the agent.

Once a reply arrives, the agent does the qualifying and the booking, conversationally. Not a menu of buttons. It asks about timeline and neighborhood, pulls live property details, and offers appointment windows instead of reading three exact slots off a calendar. It also handles the parts of a reactivation campaign that make agents want to quit: reschedules, no-answers, and the guy who is furious you texted him.

On that last point, the setup in CloseBot's own campaign is worth stealing. When the agent detects aggression, it adds a tag, stops responding, and marks the contact not interested. It also stops on STOP. That single guardrail is what separates a campaign that survives eight weeks from one that gets your number flagged in week two.

For real estate specifically, the platform ships tools that matter: property values, owner names, specs, and drive-time checks, sourced from what the company describes as 100M+ US property data points. Those tools are included on every plan, including the free one. Two limits are worth knowing before you get excited. Property data tools work in the US only, and the product is CRM-native rather than channel-native: it plugs into HighLevel, HubSpot, LeadConnector, or a custom CRM via API, or you can run the chat widget with a webhook. If your CRM is Follow Up Boss or kvCORE, you are looking at the widget-plus-webhook route, not a native integration.

👉 [See how CloseBot handles real estate conversations](https://app.closebot.com/a?fpr=li87)

Other honest limits: it is text-only, there is no voice agent, English is the primary supported language, the knowledge base needs periodic upkeep or the agent will guess wrong, and reviewers consistently put initial setup in the 5 to 10 hour range. This is not a tool you switch on and walk away from.

## What the numbers actually look like

CloseBot published the results of its own nine-day reactivation campaign. It is a vendor's own list, on contacts who had previously created an account, so treat it as a best-case rather than a forecast.

| Campaign metric | Result |
| --- | --- |
| Contacts attempted | 1,486 |
| Replies received | 602 |
| Appointments booked | 41 |
| Booking rate (of contacts attempted) | About 3% |
| Booking rate the company calls typical | 2%–5% |
| Bookers who no-showed | 29% |
| Average AI responses per booking | 8 |

A 3% booking rate on a dead list sounds small until you price it. On a 5,000-contact database that is roughly 150 appointments, at zero ad spend, from leads you already paid to acquire. The company's own caveat is fair and worth repeating: their contacts were high-intent, previously registered users. A pulled-from-portals list with stale phone numbers will do worse.

The cost side deserves a napkin. A 1,486-contact sequence with up to three outbound touches plus 602 replies runs into the thousands of messages by any reasonable estimate. The free plan's 100 messages a month will not touch that, and you should assume you are paying for a paid tier with a message ceiling raised well above the 500-message default.

## Every CloseBot plan, side by side

Prices below come from the official plans page, which shows a monthly and an annual toggle for the paid business tier.

| Plan | What you get | Price | Billing | Get started |
| --- | --- | --- | --- | --- |
| Free | 100 messages/mo, 1 agent, 1 user seat, 1 MB knowledge storage, unlimited account connections | $0 | Always free, no card required | [Start on the free plan](https://app.closebot.com/register?fpr=li87) |
| Core (Business) | Lead qualification and booking, 15+ templates, message costs included in the base price, 1 job flow, add-on users at $5/seat, add-on storage and agents | $64/mo monthly, or $53/mo billed as $640/yr | Monthly or annual, cancel anytime | [See the Core plan](https://app.closebot.com/settings?tab=subscription&plan=business&toggle=monthly&fpr=li87) |
| Agency | Unlimited agents across unlimited sources, client re-billing at $0.012 per message, white-label client portal | $397/mo | Monthly | [See the Agency plan](https://app.closebot.com/settings?tab=subscription&plan=agency&toggle=monthly&fpr=li87) |
| Growth | 50+ templates, HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support | Custom quote | Annual or custom | [Talk to CloseBot about Growth](https://app.closebot.com/a?fpr=li87) |

Two details that decide your bill. First, business plan pricing scales with the monthly message volume you select, and pricing improves as you raise that ceiling. Independent reviews that verified the pricing slider recorded $84/mo at 1,000 messages, $109 at 2,000, and $176 at 5,000, with the entry $64 covering the lowest volume band. Second, the base price on business plans includes your message costs, so overages only apply if you blow through the ceiling you selected, drawn from a wallet.

What is not in the table but matters: **there are no refunds.** What you get instead is a free-forever plan under 100 messages and a seven-day trial on any paid plan, which is where you should do your testing. Annual billing works out to roughly two months free, which is the only discount I would quote as currently verifiable. Coupon codes circulating on third-party site aggregators are a different story, and I would not plan a budget around them.

## Which plan fits which operator

A solo agent with 2,000 to 5,000 contacts and realistic volume needs the Core plan, probably at a message ceiling above the default. You are paying roughly the price of one nice dinner per month to run conversations you are not having.

A team running reactivation for several agents, or an agency selling this as a service to brokerages, wants the Agency plan. The economics change completely once you can re-bill usage at $0.012 per message with your own markup and hand clients a white-labeled portal. That is also the plan that unlocks unlimited agents and sources, versus the Core plan where one agent covers unlimited accounts in a single niche.

Growth exists for operators with procurement requirements: audits, SLA-backed uptime, priority support. If you are a national brokerage with a compliance department, that conversation starts there rather than on the pricing page.

## A 14-day launch checklist

1. Export three segments: past clients, cold inquiries from 6–18 months, and everything older.
2. Strip anyone without documented text consent and anyone who previously opted out.
3. Confirm 10DLC registration and quiet-hour settings on your sending number.
4. Write three messages, not one, and personalize on something real (a street, a saved listing, a season).
5. Cap sends at 50 per day to start, one every two minutes, business hours only.
6. Build the agent's job flow: qualify, book, and stop on aggression or STOP.
7. Load the knowledge base with your service area, price bands, and what you actually do.
8. Set the pipeline tags so an engaged contact leaves the reactivation workflow automatically.
9. Track reply rate, appointments booked, and show-up rate separately.
10. After two weeks, review what the agent got wrong and fix the knowledge base before scaling volume.

## Questions that come up before every launch

**How long should a reactivation campaign run?** A focused sequence runs 10 to 14 days with five to seven touchpoints across text and email. Non-responders should move to a low-frequency nurture track rather than a second aggressive push.

**What reply rate is realistic?** CloseBot's own campaign saw 602 replies from 1,486 contacts, about 40%, on a high-intent list. Expect materially less on portal leads and open house sign-ins, and expect more than one message to get there.

**Do I need a CRM to use this?** In practice, yes. CloseBot takes over conversations inside a CRM. If you have no CRM at all, you are adopting two products, and that changes the budget math.

**What happens when someone is angry?** The agent tags the contact, stops responding, and marks them not interested. You review the tag once a week and remove anyone whose reaction suggests the consent trail was wrong.

**Does this replace an ISA?** It replaces the part of the ISA job that is texting the same three questions all day and putting calls on a calendar. It does not negotiate, draft proposals, or close. Anyone selling you that is overselling.

## The version I would actually run

Reactivation works because the leads are already yours. The reason most campaigns fail is not message quality, it is that nobody can hold thirty simultaneous conversations for two weeks straight. CloseBot is a credible answer to that specific problem, and it is unusually well suited to real estate thanks to the property data tools and the fact that the company started by building this for a real estate agent. The tradeoffs are real: a CRM underneath, English-first text-only conversations, US-only property data, no refunds, and a knowledge base you have to maintain.

Start on the free plan with a few hundred contacts from your best segment. If the reply rate is decent and the conversations are not embarrassing, then pay.

👉 [Try CloseBot on the free plan and run your first reactivation batch](https://app.closebot.com/a?fpr=li87)
