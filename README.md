# ClimateSim — AI Climate Negotiation Platform

> *Every climate model tells you what happens if countries cooperate. ClimateSim is the first tool that models why they don't — and makes the people making those decisions feel the consequences of every choice before they make it.*

---

## The Problem

Climate change is not an information problem. Every government on earth knows the science. The Paris Agreement has been signed by 196 countries. And yet global emissions are still rising.

The reason is structural. Cooperating on climate is collectively rational but individually irrational for almost every country on earth. If you conserve while others don't, you pay the cost and still suffer the damage. If you expand fossil fuels while others conserve, you gain the economic benefit and someone else absorbs the climate consequence. Every negotiator at COP knows this. And so every round of negotiations ends the same way — partial commitments, missed targets, and the same structural failure dressed in new language.

This is the **prisoner's dilemma at planetary scale**. And no existing tool models it.

---

## The Current Status Quo — Why Existing Tools Fail

| Tool | What it does | What it cannot do |
|---|---|---|
| IPCC climate models | Projects temperature and sea levels | Assumes cooperation as a given — cannot model why it breaks down |
| Diplomatic simulations (RAND, Brookings) | Human-facilitated war games | Expensive, slow, no reproducible output, no AI reasoning |
| Economic models (DICE, IAM) | Computational country-level decisions | Requires PhD-level interpretation, no natural language output, inaccessible to policymakers |
| Carbon trackers and sustainability apps | Individual behaviour change tools | Does not model collective action failure at all |

**The gap:** No tool combines game theory, real economic data, and accessible AI-generated consequence reasoning in something a non-technical policymaker can sit in front of.

---

## The Stakeholders

**Primary users**
- Government delegations preparing for COP negotiations
- Policy analysts and think tanks advising heads of state
- UN and World Bank institutional researchers

**Secondary users**
- University policy schools (Kennedy School, LSE, Sciences Po) running negotiation simulations
- NGOs and climate finance institutions stress-testing proposed agreements
- Journalists and educators communicating why climate cooperation is structurally hard

---

## The Solution — ClimateSim

ClimateSim is an AI-powered geopolitical policy simulation platform. It models global climate negotiations across 8 nations using real 2025 economic data, game theory mechanics, and a Claude-powered consequence engine that generates asymmetric policy briefings after every round of decisions.

### How it works

Eight countries — each representing a fundamentally different archetype of the real climate negotiation landscape — simultaneously submit one of three policy choices each round:

- **Conservation Policy** — reduce fossil consumption, minimal budget drain, slow regeneration
- **Renewable Investment** — build clean energy infrastructure, short-term GDP cost, long-term compounding returns and infrastructure that compounds over rounds
- **Fossil Expansion** — maximum short-term GDP gain, heaviest carbon budget drain, no regeneration, degrades infrastructure

After all 8 nations submit, the AI consequence engine fires. It receives the complete game state — every country's GDP, CO₂ per capita, fossil dependency, climate vulnerability index, Paris NDC commitment, infrastructure score, currency system, economic power, resource power, and trade dependence — and generates three layers of output:

1. **Short term** — immediate GDP impact, temperature contribution, political fallout per country
2. **Long term** — 10-year economic trajectory, asymmetric risks, geopolitical realignment, plus a Suggested Policy recommendation for each country based on what everyone else just chose
3. **SDG Pathways** — which UN Sustainable Development Goals each country is failing on, the specific gaps, and actionable policy recommendations grounded in their economic reality

The simulation runs for 5 rounds, each representing approximately 2 years of real-world policy cycles. The global carbon budget depletes with fossil expansion and regenerates with renewable investment. If the budget reaches zero, climate collapse is triggered — mirroring the IPCC finding that at current emission rates the 1.5°C carbon budget is exhausted by approximately 2030.

---

## The 8 Nations and Why They Were Chosen

Each country represents a structurally distinct position in the real climate negotiation landscape:

| Country | Archetype | Key dynamic |
|---|---|---|
| 🇺🇸 USA | Dominant historical emitter | USD reserve currency gives economic leverage; #1 cumulative emitter creates diplomatic obligation |
| 🇨🇳 China | Paradox actor | Simultaneously world's largest coal consumer and largest solar manufacturer |
| 🇪🇺 EU | Proactive climate bloc | CBAM carbon border tariffs punish fossil-expanding trading partners |
| 🇮🇳 India | Rising power in the middle | Development rights vs climate obligation; financing trap makes investment costly |
| 🇷🇺 Russia | Arctic beneficiary | The only country that economically gains from warming; 98% fossil dependency |
| 🇧🇷 Brazil | Amazon custodian | Deforestation policy moves the global carbon budget more than any fossil choice |
| 🇸🇦 Saudi Arabia | OPEC anchor | 99% fossil dependency; racing to extract value before peak oil demand arrives |
| 🇳🇬 Nigeria | Climate inequity embodiment | 0.6t CO₂/capita vs USA 17.3t — lowest emitter, highest vulnerability index 0.81 |

---

## What Makes This Unique

### 1. AI is the mechanism, not a feature

Remove the AI and this is a coin counter. With Claude reasoning over the full game state, the platform generates geopolitically grounded, historically aware, asymmetric consequences that reflect why different countries make different choices even when facing identical incentives. A fixed rule system cannot produce why Nigeria fossil expansion is fiscal survival while Russia fossil expansion is uniquely rational — the same action, completely opposite reasoning.

### 2. Asymmetric consequences grounded in real data

The same policy choice produces completely different outcomes depending on who made it. Nigeria choosing fossil expansion triggers a self-defeating trap — oil revenues fund the budget but vulnerability 0.81 means the resulting warming destroys the agricultural sector the oil was supposed to develop. Russia choosing fossil expansion has a genuinely positive long-term economic case — the only country in the simulation where this is true. No rule system can model this. Claude can.

### 3. The prisoner's dilemma is real, not metaphorical

The carbon budget regenerates when countries invest in renewables. It depletes when they expand fossils. The game theory is live — if you conserve while others defect, you pay the cost and still suffer the damage. The simulation makes this felt rather than explained.

### 4. Economic power asymmetry built in

Three variables — Economic Power, Resource Power, and Trade Dependence — determine how consequences land differently per country. India at 8/10 trade dependence means US fossil expansion ripples into India's import costs. Nigeria at 3/10 economic power means the same climate shock that the USA absorbs as a trade tariff destroys Nigeria's food supply. These are not arbitrary scores — they are sourced from real data.

### 5. Infrastructure compounds realistically

Renewable investment builds an infrastructure index per country. As it grows, investment costs less and regenerates more — mirroring the real-world solar learning curve (90% cost reduction between 2010 and 2023). Countries that invest early gain compounding advantage. Countries that expand fossils degrade their own future transition capacity.

---

## Large Scale Impact

### The immediate use case

Before COP30, each country's delegation spends weeks in internal war games trying to anticipate how other nations will respond to their proposals. Right now that happens in conference rooms with human facilitators and whiteboards. ClimateSim is the tool that makes that process faster, data-grounded, and reproducible — so delegations arrive at the table having already stress-tested their strategies against AI-simulated counterparts modelled on real economic incentives.

### The deeper impact

The simulation makes viscerally clear why every person who has ever read an IPCC report and wondered "why don't governments just act?" has been asking the wrong question. The question is not why governments don't know. The question is why the structure of international relations makes cooperation individually irrational even when it is collectively necessary. ClimateSim is the first tool that puts decision-makers inside that structure and makes them feel it.

---

## Data Sources

Every number in the simulation is sourced and citable:

| Data point | Source |
|---|---|
| GDP per country | IMF World Economic Outlook, October 2025 |
| CO₂ per capita | EDGAR Global CO₂ Emissions 2025 |
| Fossil fuel dependency | IEA World Energy Outlook 2024 |
| Climate vulnerability index | ND-GAIN Country Index 2023 — gain-new.crc.nd.edu |
| Paris NDC pledges | UNFCCC NDC Registry |
| Cumulative emissions ranking | Our World in Data / Global Carbon Project |
| Carbon budget calibration | IPCC AR6 Working Group I, Chapter 5 |
| Energy mix percentages | IEA World Energy Balances 2024 |

---

## How AI Is Used

AI is not a bolt-on in this project. It is the consequence engine:

**1. Asymmetric consequence reasoning**
Nigeria and Russia both choosing fossil expansion in the same round get fundamentally different consequences — not because of a formula but because Claude understands the structural difference between fiscal survival and strategic exploitation. That requires language model reasoning, not arithmetic.

**2. Treaty compliance auditing**
Every policy choice is checked against that country's Paris NDC commitment. Saudi Arabia at 99% fossil dependency pledging net zero by 2060 then choosing expansion gets a specific narrative about Vision 2030 credibility collapse — not a generic penalty flag.

**3. Historical context accumulation**
The full round history is passed into every prompt. By round 4, if USA has expanded fossils three times while Nigeria has conserved twice, Claude names that injustice explicitly and escalates the consequence severity to reflect the accumulated damage.

**4. SDG pathway generation**
Each country's simulation state is matched to the specific UN Sustainable Development Goals they are failing on, with grounded actionable recommendations that differ based on economic profile. Nigeria's SDG 7 failure looks completely different from Saudi Arabia's SDG 7 failure even though both involve energy.

**5. Suggested policy generation**
After the long-term consequences are shown, each country receives a context-aware policy recommendation for the next round — factoring in what all other countries just chose, the current budget depletion level, the temperature trajectory, and that country's infrastructure score. Russia and Saudi Arabia get structurally different suggestions from Nigeria even when facing the same global conditions.

---

## Project Structure

```
climatesim/
├── index.html                     — production simulator (calls Claude API each round)
├── climate_crisis_simulator.html  — self-contained demo (no API key or server required)
├── countries.json                 — all country profiles, SDG data, real statistics
└── README.md                      — this file
```

**Both `index.html` and `countries.json` must be in the same folder.** The production simulator fetches `countries.json` on startup — if they are separated, it will not load. `climate_crisis_simulator.html` is fully self-contained and has no such dependency.

### index.html

The production single-page application. Fetches `countries.json` on startup for all country data. On each round submission, sends the full game state to the Claude API (`claude-sonnet-4-20250514`) and renders the returned JSON consequences. Every simulation run produces unique output based on the full round history — no two games are identical. Requires a local HTTP server and a Claude API key.

### climate_crisis_simulator.html

The self-contained demo version. All country data and consequence logic is embedded directly in the file. Works by double-clicking — no server, no API key, no setup. Used to record the demo video. The consequence data mirrors the reasoning patterns Claude applies in production mode, serving as a validated baseline of the AI's logic. The structural difference from the production version is that consequences do not compound across rounds based on simulation history — they are fixed illustrative examples rather than live contextual reasoning.

### countries.json

All static country data — GDP, CO₂ per capita, fossil dependency, vulnerability index, energy mix, Paris NDC pledges, economic power scores, and SDG gap analysis. Loaded by `index.html` on initialisation and passed to the AI prompt each round. Kept separate from application logic so the data layer can be updated independently as new statistics are published.

---

## Running the Simulator

### Option 1 — Demo version (instant, no setup)

Open `climate_crisis_simulator.html` directly in any browser by double-clicking it. No server, no API key, no installation required. All game mechanics, carbon budget tracking, temperature, infrastructure scoring, SDG pathways, and suggested policy work fully. This is the version used to record the demo video.

### Option 2 — Production version (live AI, requires API key)

The consequence engine calls Claude API every round, generating unique asymmetric consequences based on the full simulation history. No two runs produce the same output.

1. Get a Claude API key from `console.anthropic.com`
2. Add $5 minimum credit to your account
3. Clone this repository — ensure `index.html` and `countries.json` are in the same folder. The app fetches `countries.json` on startup so both files must sit side by side.
4. Serve the folder over a local HTTP server — required because browsers block `fetch()` calls from `file://` URLs:

```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .
```

5. Open `http://localhost:8080` in your browser
6. Enter your API key in the field that appears at the top
7. Select policies for all 8 countries and click **Run AI Consequence Engine**

### Key difference between the two versions

The demo version shows fixed illustrative consequences that represent what Claude produces under typical conditions. The production version generates consequences that compound across rounds — by round 4, if USA has expanded fossils three times while Nigeria has conserved, Claude explicitly names that pattern of injustice in language that could not have been written in advance. That contextual reasoning over a unique simulation history is what no hardcoded system can replicate.

---

## Why Two Files Exist

The demo version (`climate_crisis_simulator.html`) and the production version (`index.html`) produce structurally identical outputs — same UI, same data, same three tabs, same game mechanics. The difference is not what they show but how they generate it.

The demo version has fixed consequences written to illustrate what Claude produces under typical conditions. The production version generates consequences live, reasoning over the full simulation history each round. By round 4, the production version produces output that could not have been written in advance — consequences that reference the specific pattern of cooperation and defection that occurred in this particular game, in this particular order, with these particular countries.

The demo version exists for two reasons:

1. **Accessibility** — any judge, researcher, or policymaker can explore the full simulation instantly without API credentials, a local server, or any technical setup
2. **Auditability** — the fixed consequence data makes the simulation's reasoning transparent and inspectable. Anyone can open the file and verify that the logic is sound before trusting the live AI output

The genuine AI contribution — the thing the demo version cannot replicate — is contextual reasoning that compounds across rounds. That is what `index.html` with a live API key demonstrates.

---

## Game Mechanics Reference

| Mechanic | Description |
|---|---|
| Carbon budget | Starts at 100 units. Calibrated to IPCC AR6 remaining 1.5°C budget. Fossil expansion drains it. Renewable investment regenerates it. |
| Temperature | Starts at 1.2°C. Fossil expansion adds 0.06°C per country per round. Investment adds 0.02°C. Conservation adds 0.005°C. |
| Infrastructure index | Per-country score 0–10. Investment adds +1 per round. Fossil expansion subtracts −1. Higher scores reduce investment drain cost and increase regeneration. |
| Carbon budget regeneration | Conservation: −2 drain +1 regen = net −1. Investment: −3 drain +4 regen = net +1. Fossil: −5 to −9 drain, zero regen. |
| Cooperation score | Each country accumulates a cooperation score across rounds. Investment: +2. Conservation: +1. Expansion: −2. Used for final verdict. |
| Game end | Round 5 complete, or carbon budget reaches zero — whichever comes first. |

---

## Realistic Next Steps

1. **Live data pipeline** — connect to World Bank API, EDGAR API, and IEA data feeds so every simulation uses genuinely current statistics
2. **Multiplayer mode** — assign one country to each player running on separate screens, creating genuine prisoner's dilemma dynamics between real people
3. **Negotiation phase** — add a round before submission where countries can propose bilateral deals, offer climate finance, or threaten trade sanctions
4. **Scenario presets** — pre-loaded historical scenarios (Paris 2015, Copenhagen 2009 collapse, COP30) for replay and analysis
5. **Academic validation** — partner with a policy school to validate consequence weightings against published climate economics research
6. **Production deployment** — Vercel serverless function to proxy the Claude API so no user credentials are ever required

---

## Built With

- Vanilla JavaScript — no framework dependencies
- Claude API (`claude-sonnet-4-20250514`) — AI consequence engine
- Real data from IMF, EDGAR, IEA, ND-GAIN, IPCC AR6, Our World in Data

---

**Team:** Akshat Hooda
**Built at:** GenAI Genesis 2026

---

*"I built a platform where world leaders can simulate 10 years of climate policy decisions in 10 minutes — grounded in real economic data, game theory, and AI that shows both the numbers and the human consequences of every choice."*
