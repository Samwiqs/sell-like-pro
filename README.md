<img width="1983" height="793" alt="ChatGPT Image Jun 20, 2026, 12_06_14 PM" src="https://github.com/user-attachments/assets/44040a11-97b5-4423-8820-bebf4ff0e4fb" />



# Founders Getting Started

A founder-first collection of startup frameworks, playbooks, decision trees, and operating systems distilled from the most influential books on entrepreneurship, growth, product development, sales, positioning, and customer acquisition.

Instead of reading thousands of pages across dozens of business books, this repository organizes the core frameworks into structured, AI-friendly reference documents that founders can immediately apply to real business problems.

---

## Why This Repository Exists

Most startup books contain a handful of powerful frameworks hidden inside hundreds of pages of stories and examples.

Founders often:

* Read a book once
* Highlight a few pages
* Forget the framework months later
* Struggle to apply concepts consistently

**Founders Getting Started** extracts the parts that actually drive decisions:

* Decision Trees
* Strategic Frameworks
* Validation Processes
* Positioning Models
* Pricing Systems
* Sales Methodologies
* Growth Playbooks
* Messaging Frameworks
* Templates & Worksheets
* Real-World Case Studies

The goal is simple:

> Help founders make better decisions faster.

---

# What You'll Find

| Module              | Based On                       | Best Used For                                              |
| ------------------- | ------------------------------ | ---------------------------------------------------------- |
| Diagnose            | Founder Operating System       | Identifying bottlenecks and deciding what to focus on next |
| Customer Discovery  | The Four Steps to the Epiphany | Finding and validating early customers                     |
| Lean Startup        | The Lean Startup               | MVPs, experimentation, pivots, learning loops              |
| Customer Interviews | The Mom Test                   | Running unbiased customer conversations                    |
| Positioning         | Obviously Awesome              | Defining category, differentiation, and market perception  |
| Market Expansion    | Crossing the Chasm             | Moving from early adopters to mainstream customers         |
| Category Creation   | Blue Ocean Strategy            | Escaping crowded markets and creating new demand           |
| Pricing             | Monetizing Innovation          | Pricing strategy and willingness-to-pay research           |
| B2B Sales           | SPIN Selling                   | Complex sales and stakeholder management                   |
| Offer Design        | $100M Offers                   | Creating irresistible offers                               |
| Lead Generation     | $100M Leads                    | Acquiring customers through inbound and outbound channels  |
| Growth Channels     | Traction                       | Selecting and scaling acquisition channels                 |
| Persuasion          | Influence                      | Ethical persuasion and behavioral psychology               |
| Messaging           | Building a StoryBrand          | Website copy, landing pages, and brand communication       |
| Communication       | Made to Stick                  | Making ideas memorable and actionable                      |

---
# 🤖 How to Use

## Quick Install

```bash
npx skills add Samwiqs/sell-like-pro
```

---

## Manual Install

```bash
git clone https://github.com/Samwiqs/sell-like-pro.git

for skill in sell-like-pro/*/SKILL.md; do
  dir=$(dirname "$skill")
  name=$(basename "$dir")
  ln -sfn "$(pwd)/$dir" ~/.claude/skills/$name
done
```

---

Once installed, Claude automatically loads the appropriate skill based on the user's question.

Examples:

| Question | Skill Loaded |
|-----------|------------|
| "How do I run better discovery calls?" | spin-selling |
| "How do I create a better offer?" | 100m-offers |
| "How do I generate more leads?" | 100m-leads |
| "How should I position my product?" | obviously-awesome |
| "How do I improve my website copy?" | storybrand |
| "How do I price my service?" | monetizing-innovation |
| "How do I persuade buyers?" | influence |
| "Which growth channel should I focus on?" | traction |
| "How do I scale beyond early adopters?" | crossing-the-chasm |
| "How do I escape competition?" | blue-ocean-strategy |

You can also invoke any skill directly:

```text
/spin-selling
/100m-offers
/100m-leads
/storybrand
/influence
/traction
/obviously-awesome
/crossing-the-chasm
/blue-ocean-strategy
```

---

## Use With ChatGPT, Gemini, or Any LLM

Open the relevant `SKILL.md` file and paste it into your conversation.

For deeper implementation, also provide:

- `frameworks.md`
- `examples.md`
- `cases.md`
- `integration.md`

This allows the model to access detailed frameworks, templates, case studies, and cross-skill relationships.

---

## Use With Cursor, Windsurf, Roo & Cline

Clone the repository:

```bash
git clone https://github.com/Samwiqs/sell-like-pro.git

cd sell-like-pro
```

Place the repository inside:

```text
/docs
/knowledge
/rules
```

Your AI assistant can then reference the playbooks automatically whenever sales, pricing, positioning, persuasion, or growth questions arise.

---

# 📂 Skill Structure

Every skill follows a progressive-disclosure architecture:

```text
skill-name/

├── SKILL.md
├── frameworks.md
├── examples.md
├── cases.md
└── integration.md
```

### SKILL.md

Entry point for the skill.

Contains:

- When to use
- Decision trees
- Quick frameworks
- Common mistakes
- Skill routing

### frameworks.md

Detailed framework breakdowns.

### examples.md

Templates, worksheets, prompts, and worked examples.

### cases.md

Real-world success and failure case studies.

### integration.md

Relationships, dependencies, and conflicts between skills.

---

This architecture allows AI systems to load only what is needed:

- SKILL.md → quick routing
- frameworks.md → deeper understanding
- examples.md → implementation
- cases.md → reference
- integration.md → cross-skill reasoning

Fast, efficient, and scalable.

# Repository Structure

```text
founders-getting-started/

├── diagnose/
│   ├── README.md
│   ├── frameworks.md
│   ├── examples.md
│   ├── templates.md
│   └── case-studies.md
│
├── customer-discovery/
├── lean-startup/
├── customer-interviews/
├── positioning/
├── pricing/
├── growth/
├── sales/
├── messaging/
└── ...
```
# 📚 Included Playbooks

Master the complete revenue lifecycle—from understanding customer psychology to building scalable growth systems.

| Playbook | Source | Use When |
|-----------|---------|-----------|
| **diagnose** | Revenue Operating System | Not sure why sales are stalling, multiple bottlenecks, "nothing is working" |
| **spin-selling** | SPIN Selling — Neil Rackham | B2B sales, discovery calls, enterprise deals, stakeholder management |
| **100m-offers** | $100M Offers — Alex Hormozi | Offer creation, value stacking, increasing conversions |
| **100m-leads** | $100M Leads — Alex Hormozi | Lead generation, outbound prospecting, inbound acquisition |
| **influence** | Influence — Robert Cialdini | Persuasion, negotiation, buyer psychology, objection handling |
| **storybrand** | Building a StoryBrand — Donald Miller | Website messaging, landing pages, sales copy, customer communication |
| **made-to-stick** | Made To Stick — Chip & Dan Heath | Sales presentations, pitches, memorable messaging |
| **monetizing-innovation** | Monetizing Innovation — Ramanujam & Tacke | Pricing strategy, packaging, willingness-to-pay research |
| **obviously-awesome** | Obviously Awesome — April Dunford | Positioning, differentiation, category design |
| **traction** | Traction — Gabriel Weinberg & Justin Mares | Growth channels, customer acquisition, demand generation |
| **crossing-the-chasm** | Crossing The Chasm — Geoffrey Moore | Scaling from early adopters to mainstream markets |
| **blue-ocean-strategy** | Blue Ocean Strategy — Kim & Mauborgne | Escaping competition, creating new market opportunities |
| **customer-discovery** | Four Steps to the Epiphany — Steve Blank | Understanding customers before selling |
| **lean-startup** | The Lean Startup — Eric Ries | Validation, experimentation, growth optimization |
| **mom-test** | The Mom Test — Rob Fitzpatrick | Customer interviews, validation conversations, buyer research |

---

## 🎯 What You'll Learn

### 💼 Sales

- Discovery Calls
- Objection Handling
- Deal Qualification
- Enterprise Sales
- Multi-Stakeholder Buying
- Closing Frameworks
- Negotiation Strategies

### 📢 Marketing

- Lead Generation
- Positioning
- Messaging
- Conversion Optimization
- Demand Generation
- Customer Acquisition
- Content Strategy

### 💰 Revenue

- Pricing Strategy
- Offer Creation
- Revenue Optimization
- Customer Lifetime Value
- Upselling & Cross-Selling
- Expansion Revenue

### 🧠 Psychology

- Persuasion Principles
- Negotiation Tactics
- Buyer Psychology
- Trust Building
- Behavioral Triggers
- Decision-Making Frameworks

### 📈 Growth

- Growth Channels
- Market Expansion
- Category Creation
- Retention Strategies
- Growth Loops
- Scalable Acquisition Systems

---

## 🚀 Recommended Learning Path

```text
1. customer-discovery
        ↓
2. mom-test
        ↓
3. obviously-awesome
        ↓
4. storybrand
        ↓
5. made-to-stick
        ↓
6. monetizing-innovation
        ↓
7. 100m-offers
        ↓
8. spin-selling
        ↓
9. influence
        ↓
10. traction
        ↓
11. 100m-leads
        ↓
12. crossing-the-chasm
        ↓
13. blue-ocean-strategy
        ↓
14. diagnose
```

---

## ⚡ Why These Playbooks Matter

Most sales teams struggle because they optimize tactics before mastering fundamentals.

This collection gives you a complete operating system for:

- Finding the right customers
- Understanding buyer motivations
- Creating irresistible offers
- Pricing effectively
- Running high-converting sales conversations
- Generating consistent leads
- Scaling revenue predictably

Whether you're a founder, freelancer, consultant, agency owner, SaaS operator, or enterprise sales professional, these frameworks provide a proven path from first customer to scalable growth.
```

Each module contains:

### README.md

A quick overview of the framework and when to use it.

### frameworks.md

Detailed breakdowns of concepts, models, and decision trees.

### templates.md

Worksheets and practical implementation guides.

### examples.md

Worked examples showing the framework in action.

### case-studies.md

Real-world successes, failures, and lessons learned.

---

# Recommended Founder Journey

For founders starting from zero:

### Phase 1 — Find a Problem Worth Solving

1. Diagnose
2. Customer Discovery
3. Customer Interviews

Goal:

* Identify painful customer problems
* Validate assumptions
* Avoid building something nobody wants

---

### Phase 2 — Build Something People Want

4. Lean Startup
5. Positioning
6. Messaging

Goal:

* Create a solution
* Differentiate from competitors
* Clearly communicate value

---

### Phase 3 — Monetize

7. Pricing
8. Offer Design
9. Sales

Goal:

* Turn interest into revenue
* Improve conversion rates
* Build repeatable sales processes

---

### Phase 4 — Grow

10. Growth Channels
11. Lead Generation
12. Market Expansion

Goal:

* Acquire customers efficiently
* Scale distribution
* Cross into larger markets

---

### Phase 5 — Defend and Expand

13. Category Creation
14. Persuasion & Influence

Goal:

* Build competitive advantages
* Create market leadership
* Strengthen customer loyalty

---

# How to Use With AI

This repository is designed to work exceptionally well with:

* ChatGPT
* Claude
* Gemini
* Cursor
* Windsurf
* Cline
* Continue
* Roo Code
* Any RAG-based AI system

Simply provide the relevant module as context and ask questions such as:

* "How do I validate this startup idea?"
* "Why aren't customers buying?"
* "Should I pivot?"
* "How should I price my product?"
* "Which growth channel should I focus on?"
* "How do I improve my landing page?"

The AI can then apply the framework instead of giving generic startup advice.

---

# Principles

This repository is built around five principles:

### 1. Action Over Theory

Every framework should lead to a decision.

### 2. Honest Scope

Not every framework works everywhere.

Each module documents:

* When it works
* When it fails
* Common misuse cases

### 3. Founder-Focused

Designed for startup operators rather than academics.

### 4. Practical Templates

Every concept should have an implementation path.

### 5. Continuous Improvement

Frameworks evolve as markets evolve.

---

# Who This Is For

* First-time founders
* Startup operators
* Product managers
* Growth teams
* SaaS builders
* Agency owners
* Consultants
* Startup accelerators
* Venture studios

---

# Disclaimer

This repository is an educational resource designed to help founders apply proven business frameworks.

It is not a replacement for reading the original books, learning from customers, or developing first-hand experience.

If a framework proves valuable to your business, consider purchasing and supporting the original authors.

---

# Contributing

Contributions are welcome.

Possible contributions include:

* New frameworks
* Better examples
* Updated case studies
* Startup templates
* Modern adaptations for AI-native businesses
* Additional founder resources

Please open an issue or submit a pull request.

---

# License

MIT License

Use freely. Build boldly. Learn continuously.
