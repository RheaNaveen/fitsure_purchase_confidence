# FitSure — Purchase Confidence for Online Fashion

> A product management case study exploring how online fashion shoppers can make purchase decisions with less effort and greater confidence.

---

## Overview

Online fashion shoppers have access to a large amount of product information — product photos, ratings, reviews, size charts, fabric details, customer photos, and product specifications.

However, shoppers often need to move between multiple sections and manually combine these signals before deciding whether a product will meet their expectations.

**FitSure** is a proposed product experience that adds a **Purchase Confidence** layer to an existing fashion product page.

Instead of providing more information, FitSure aims to make existing information **easier to interpret and act on**.

---

## Problem

### User Problem

> **Online fashion shoppers often have enough information available, but must manually piece together fragmented signals to determine whether a product is right for them.**

This can create uncertainty around:

- Fit and size
- Appearance
- Material and quality
- Whether the product will match expectations
- Whether the product is worth purchasing

### Product Opportunity

The opportunity is to reduce the **cognitive effort** involved in evaluating a product before purchase.

---

## User Research

I conducted a short survey with **26 online fashion shoppers** to understand how people evaluate clothing products before purchasing them.

### Key Findings

| Finding | Result |
|---|---:|
| Used information from multiple product sections | **25/26** |
| Checked customer reviews | **21/26** |
| Checked ratings | **21/26** |
| Checked product photos | **20/26** |
| Checked material/fabric information | **18/26** |
| Checked size charts | **17/26** |
| Checked size recommendations | **16/26** |
| Average ease of purchase decision | **3.12 / 5** |
| Average purchase confidence | **3.27 / 5** |

### Research Insight

The research suggested that the problem was **not simply a lack of information**.

Users were already consulting several sources before making a decision. The bigger opportunity was helping them **interpret and combine those signals more efficiently**.

> **Key insight: Users are doing the synthesis themselves.**

---

## JTBD

### Job to Be Done

> **When buying clothing online without trying it on, I want to understand how the specific garment will fit and look on me, so I can confidently decide whether to purchase it without worrying about a disappointing purchase or return.**

The JTBD helped frame the problem around the user's underlying decision rather than around a specific technology or feature.

---

## Opportunity

### How might we...

> **Help shoppers quickly evaluate whether a clothing product is likely to meet their expectations without making them manually piece together scattered information?**

This became the basis for exploring potential product solutions.

---

## Solution

# FitSure Purchase Confidence

FitSure adds a decision-support layer to the existing product page.

It synthesizes relevant product signals into a concise summary so shoppers can understand the most important considerations without manually piecing together information from different sections.

### Purchase Confidence

The experience provides:

- **Fit & Size**
- **Appearance**
- **Material & Quality**
- **Customer Feedback**
- **Evidence / "Why this confidence?"**

The confidence indicator is intended as **decision support**, not a guarantee that a purchase will meet the user's expectations.

---

## MVP

The MVP focuses on validating one core hypothesis:

> **Can we reduce the effort required for shoppers to evaluate a clothing product?**

### Included

- Product information synthesis
- Review and rating synthesis
- Size and fit signals
- Customer-photo signals
- Confidence breakdown
- Evidence supporting insights
- Purchase Confidence indicator

### Not Included

- Full virtual try-on
- Body scanning
- Advanced personalization
- Wardrobe recommendations
- Complex AI/ML personalization

The first version deliberately focuses on the **information-synthesis problem** before introducing more complex capabilities.

---

## Feature Prioritization

Potential features were evaluated using **RICE prioritization** based on:

- Reach
- Impact
- Confidence
- Effort

The core information-synthesis experience was prioritized because it directly addressed the problem identified through user research while keeping the MVP relatively focused.

---

## Prototype

I created a working mobile prototype demonstrating how FitSure could be integrated into an existing fashion-commerce product page.

### Prototype Flow

**Existing Product Page**  
↓  
**Purchase Confidence**  
↓  
**Confidence Breakdown**  
↓  
**Supporting Evidence**

### Key Screens

1. Existing Product Page
2. Purchase Confidence
3. Confidence Breakdown
4. Evidence / Reviews

### Prototype

**Figma:** [View the interactive prototype](https://www.figma.com/make/ihaMQRM6PrKkxNcVrLWaQn/Mobile-Fashion-E-Commerce-Product-Page?fullscreen=1&t=NI0xuZXzCPbHeePu-1&code-node-id=0-6)

> **Prototype data disclaimer:** Any percentages, review counts, review excerpts, or confidence values shown within the prototype are illustrative data created to demonstrate the product experience. They are not actual Myntra data and are not results from the user survey.

---

## Success Metrics

The product should be evaluated based on whether it helps users make decisions with **greater confidence and less effort**.

### Primary Metric

**Purchase Decision Confidence**

Users would be asked:

> "How confident are you that this product will meet your expectations?"

Measured on a **1–5 scale**.

This directly measures the core user problem identified during research.

### Secondary Metrics

- Decision time
- Add-to-cart rate
- Purchase conversion rate
- Purchase Confidence feature engagement

### Guardrail Metrics

- Return rate
- Product-page abandonment

The guardrails help ensure that increased confidence does not come at the cost of increased returns or other negative downstream outcomes.

---

## A/B Testing Plan

I designed an A/B testing framework to validate the core product hypothesis.

### Hypothesis

> **If scattered product information is synthesized into a concise, evidence-backed Purchase Confidence feature, shoppers will make decisions with less effort and greater confidence.**

### Experiment Design

| Group | Experience |
|---|---|
| **Control** | Existing product page |
| **Treatment** | Existing product page + Purchase Confidence |

Eligible users would be randomly assigned approximately **50/50** between the two groups.

### Primary Metric

**Purchase Decision Confidence (1–5)**

### Secondary Metrics

- Decision time
- Add-to-cart rate
- Purchase conversion
- Feature engagement

### Guardrail

**Return rate**

### Decision Logic

If the treatment improves confidence and/or decision efficiency without negatively affecting conversion or returns, the feature could move toward broader rollout.

If confidence improves but returns increase, the next step would be to investigate whether the synthesized insights are creating **misplaced confidence**.

> **Important:** This A/B test was designed as a validation plan and was **not actually conducted**. No experimental results are claimed.

---

## Product Roadmap

The roadmap expands the product based on validation of the core experience.

### V1 — Reduce Information Overload

**Purchase Confidence**

Synthesize existing product signals into a concise decision-support experience.

### V2 — Personalize the Experience

Potential capabilities:

- Personalized size context
- Relevant review filtering
- Previous purchase context
- User-specific confidence signals

### V3 — Address Remaining Visual Uncertainty

Potential capabilities:

- AI-assisted visual preview
- Wardrobe compatibility
- Occasion-based recommendations

### Roadmap Principle

**General Decision Support → Personalization → Visual Assistance**

The roadmap intentionally moves from the simplest validated problem toward more advanced capabilities rather than starting with complex AI functionality.

---

## Key Product Learnings

- **More information isn't always the answer.** The opportunity can be making existing information easier to interpret and act on.
- **Start with the smallest useful product.** The MVP focuses on information synthesis before introducing more complex capabilities.
- **Validate before scaling.** Future iterations should depend on experiment results and remaining sources of user uncertainty.
- **Start with the user's decision, not the technology.** The solution was developed from the user's purchase decision and pain points rather than starting with an AI capability.

---

## Product Development Process

**User Research → Research Synthesis → Problem Definition → JTBD → User Journey & Pain Points → Ideation → RICE Prioritization → MVP Definition → Prototype → Metrics & A/B Test Design → Product Roadmap**

---

## Tools & Methods

### Tools

- Google Forms — User research
- Excel / Google Sheets — Research analysis
- Figma — Product prototyping
- GitHub — Project documentation

### Product Methods

- User Research
- JTBD
- User Journey Mapping
- Problem Framing
- RICE Prioritization
- MVP Definition
- Product Metrics
- A/B Test Design
- Product Roadmapping

---

## Project Artifacts

| Artifact | Description |
|---|---|
| `research/` | Survey questions and cleaned/anonymized research data |
| `product/` | Problem definition, JTBD, user journey, prioritization and roadmap |
| `prototype/` | Prototype screenshots and supporting files |
| `presentation/` | Product case study presentation |

---

## Disclaimer

FitSure is an **independent product management portfolio project** and is not an existing Myntra feature.

The project uses primary user research conducted through a **26-response survey** and observations of online fashion-shopping experiences.

Any product-level metrics, review excerpts, percentages, or confidence values shown in the prototype are **illustrative data created for demonstration purposes** and should not be interpreted as actual company data or experimental results.

The A/B test described in this case study is a **proposed validation framework and was not conducted**.

---

## Author

**Rhea Naveen**

Computer Science Undergraduate  
Product Management / Data Analytics

[LinkedIn](https://www.linkedin.com/in/rheanaveen/) · [Figma Prototype](https://www.figma.com/make/ihaMQRM6PrKkxNcVrLWaQn/Mobile-Fashion-E-Commerce-Product-Page?fullscreen=1&t=NI0xuZXzCPbHeePu-1&code-node-id=0-6)
