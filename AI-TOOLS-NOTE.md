# AI Tools & Process — Omnify AI Redesign Assessment

## What This Is

A fully functional, data-driven prototype using **real service data from UP Robotics** (uproboticstech.getomnify.com). Every program, camp, price, date, grade level, and schedule is pulled from their actual Omnify store.

## Real Data Integrated

- **38 Summer Camps** — All camp sessions with real dates, prices ($475-$695), and grade ranges
- **7 After-School Programs** — 4-week programs ($175-$275) with real day/time schedules
- **1 Birthday Party Package** — Robot Builders Birthday Bash ($450)
- **Real grade mappings** — Grade 1 through Grade 9, plus Summer Camp
- **Real spot availability** — Each service has actual capacity numbers
- **Real scheduling** — Days of week, time slots, date ranges

## AI Recommendation Engine

The prototype includes a working recommendation algorithm that:

1. **Matches child profiles to services** by grade eligibility (40 points)
2. **Scores interest alignment** — tags vs. child interests (35 points)
3. **Parses natural language input** — detects keywords like "beginner", "summer", "weekend", "python", "minecraft", "party"
4. **Factors in urgency** — low spot counts get highlighted
5. **Ranks and filters** — returns sorted results with match percentages

## Sibling Detection Logic

- Detects when multiple children are in the cart
- Auto-applies 10% sibling discount
- Suggests matching programs for siblings not yet enrolled
- Shows overlapping schedule opportunities

## Tools Used

### 1. LLM (Claude/GPT-4)
- Product thinking, UX copy, AI reasoning text generation
- Brainstorming interaction patterns for the decision helper

### 2. AI Coding Assistant (Cursor/Copilot)
- Frontend implementation, responsive layouts, animation logic
- State management for cart, profiles, and filtering

### 3. Real Data Scraping
- Manually extracted all 46 services from UP Robotics' live Omnify store
- Structured into a normalized JSON data model

## Product Decisions

1. **Natural language replaces filters** — Parents type what they want, AI understands
2. **Child profiles provide context** — Age, grade, interests drive every recommendation
3. **Transparent AI reasoning** — Shows *why* a program is recommended, building trust
4. **Sibling intelligence** — Auto-detects multi-child enrollment, applies discounts
5. **Real-time availability** — Spot counts, date conflicts, and schedule overlap shown live
6. **Decision support modal** — When parents hesitate, structured comparisons with AI guidance
