---

name: etsy-research
description: Research Etsy niches and products to identify high-demand, high-margin opportunities with clear evidence and assumptions
author: pfoty
version: 1.0.0
triggers:

* "etsy research"
* "find profitable etsy products"
* "etsy niche analysis"
* "what sells on etsy"
* "etsy product research"

---

# Etsy Research

Identify Etsy products that are most likely to sell well **and** be profitable, using structured market signals instead of guesswork.

This skill is designed for **decision support**, not automation. It produces clear research outputs, assumptions, and tradeoffs so the user—not the AI—makes final business decisions.

---

## Objective

Help the user grow an Etsy business by:

* identifying profitable niches
* analyzing winning products within those niches
* estimating demand, competition, and pricing power
* surfacing risks and saturation signals
* producing actionable product ideas with rationale

---

## What it does

* **Niche discovery** – Finds Etsy niches with strong demand and manageable competition
* **Product-level analysis** – Breaks down top-performing listings to understand why they sell
* **Demand signals** – Uses reviews, sales velocity proxies, recency, and engagement
* **Competition analysis** – Evaluates saturation, listing quality, and moat strength
* **Pricing & margin modeling** – Estimates realistic price bands and cost constraints
* **Differentiation insights** – Identifies gaps, variants, and positioning opportunities
* **Evidence-based output** – Separates facts, estimates, and assumptions

---

## What it does *not* do

* Does not guarantee profitability or sales
* Does not automate store actions, uploads, pricing changes, or ads
* Does not scrape private data or bypass Etsy restrictions
* Does not fabricate sales numbers or claim insider access

All conclusions are probabilistic, not promises.

---

## Research workflow

### 1) Define the niche

The user specifies:

* niche or theme (e.g. “wedding signage,” “digital planners,” “pet memorials”)
* product type (physical, digital, POD, handmade, vintage)
* constraints (price floor/ceiling, production method, region, skill limits)

If the niche is too broad, the skill will narrow it before proceeding.

---

### 2) Market scan (top-down)

For the niche, analyze:

* number of competing listings
* visible demand signals:

  * review counts
  * review velocity
  * recency of reviews
* price distribution
* apparent seasonality
* digital vs physical mix

**Output:**
Is this niche:

* undersupplied
* balanced
* oversaturated
  …and why.

---

### 3) Product deep dive (bottom-up)

Select representative top-performing listings and evaluate:

* product value proposition
* visual quality (photos, mockups)
* personalization/customization options
* delivery format (instant, made-to-order)
* perceived effort vs price
* differentiation signals (bundles, variants, framing)

**Goal:** Understand *why* buyers choose these products.

---

### 4) Demand & competition scoring

Each product or sub-niche is scored on:

* **Demand strength**

  * consistent reviews over time
  * multiple sellers succeeding (not one anomaly)
* **Competition intensity**

  * number of similar listings
  * quality bar to compete
* **Pricing power**

  * ability to charge above commodity pricing
* **Operational complexity**

  * production time
  * customization burden
* **Risk**

  * trend-dependence
  * IP issues
  * policy sensitivity

Scores are comparative, not absolute.

---

### 5) Profitability reasoning

Estimate:

* realistic selling price range
* typical Etsy fees
* production cost assumptions (user-specified or stated estimates)
* margin bands (low / mid / optimistic)

**Rule:**
If costs are unknown, clearly label assumptions and provide sensitivity ranges.

---

### 6) Opportunity synthesis

Produce:

* 3–10 product ideas or angles
* why each could win
* what differentiation is required
* what would likely fail
* who the target buyer is
* suggested validation steps (before building inventory)

---

## Output format

Each research run produces:

### Niche summary

* niche definition
* demand outlook
* saturation risk
* seasonality notes

### Winning patterns

* common traits among top listings
* pricing norms
* buyer expectations

### Opportunity list

For each idea:

* product concept
* target price range
* competition assessment
* differentiation strategy
* risk notes

### Assumptions & caveats

* what is inferred vs observed
* what depends on execution quality
* what requires validation

---

## Guardrails and constraints

* **No fabricated metrics**
  Never claim exact sales numbers or internal Etsy data.
* **No false certainty**
  Use probabilistic language and comparative reasoning.
* **No IP violations**
  Flag trademark, copyright, and fan-art risks.
* **No automation without consent**
  Research only. No listing creation, pricing changes, or outreach.
* **Transparency first**
  Clearly state data sources, heuristics, and limits.

---

## Usage examples

### Example 1: Broad niche

User:

> Do Etsy research on home decor

Skill response:

* Narrow niche into subcategories
* Ask user to choose or approve narrowed focus
* Proceed only after scope is defined

---

### Example 2: Focused niche

User:

> Research profitable Etsy products in the printable wedding signage niche under $15

Skill response:

* Analyze printables-only listings
* Identify demand clusters (welcome signs, seating charts, bundles)
* Highlight oversaturated vs underexploited angles
* Produce product ideas with pricing and differentiation notes

---

## Success criteria

* User understands *why* a product might sell
* Risks and saturation are visible, not hidden
* Outputs are actionable but not prescriptive
* No black-box conclusions
* No surprise actions

---

## Design philosophy

This skill treats Etsy research as:

* **market pattern recognition**, not prediction
* **decision support**, not automation
* **execution-aware**, not theory-only

Good Etsy businesses are built on informed bets, not certainty.
This skill exists to make those bets smarter.
