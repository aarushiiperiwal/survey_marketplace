# Discovery Marketplace — Complete Research System
**Hybrid approach: 3 instruments, 2 segments, <3 minutes**

---

## System Architecture

### Instrument Stack
1. **Discovery Trade-Off** (primary) — validates pain point strength
2. **Trust Ladder** (buyer segment only) — maps purchase barriers
3. **Brand Origin Story** (brand segment only) — maps acquisition reality

### Response Flow
```
Entry Screen
    ↓
Segment Selection: "I'm here to shop" OR "I run a brand"
    ↓
[BUYER FLOW]                          [BRAND FLOW]
Discovery Trade-Off (8 pairs)         Brand Origin Story (5 scenes)
    ↓                                      ↓
Trust Ladder (6 rungs)                Discovery Trade-Off (8 pairs)
    ↓                                      ↓
Discovery Habits (4 questions)        Growth Bottlenecks (4 questions)
    ↓                                      ↓
Thank You + Waitlist Capture          Thank You + Early Access Offer
```

**Total time:** 2min 20sec (buyer), 2min 40sec (brand)

---

## Screen-by-Screen Design

### ENTRY SCREEN

**UI:**
- Clean white canvas
- Centered card, 480px max-width
- Premium minimal aesthetic

**Copy:**
```
Help us understand discovery

We're building something new for how people find brands.
This takes 2 minutes. Your honest answers shape what we build.

[Button: I'm here to shop]
[Button: I run a brand]
```

**Microcopy under buttons:**
"Shoppers — if you've ever struggled to find new brands"
"Brands — if getting discovered feels impossible"

---

## BUYER FLOW

### Screen 1: Discovery Trade-Off (Primary Instrument)

**Concept:**
8 forced pairs. Each pair presents two competing values. User picks one.
No neutral option. No "both" option. Forces priority revelation.

**UI mechanism:**
- Two cards side-by-side
- Tap to select
- Selected card gets border highlight
- Auto-advances after selection (0.3s delay)
- Progress dots at top (8 dots, filled as you go)

**The 8 Pairs:**

**Pair 1**
```
A brand 10,000 people love
vs
A brand you've never heard of with stunning products
```

**Pair 2**
```
Scrolling Instagram until something catches your eye
vs
A curated feed of brands chosen just for you
```

**Pair 3**
```
Finding the perfect thing takes time — that's part of the fun
vs
Finding the perfect thing should be instant
```

**Pair 4**
```
I trust brands my friends recommend
vs
I trust brands an expert curator recommends
```

**Pair 5**
```
I want to discover brands before everyone else knows them
vs
I only buy brands that already have social proof
```

**Pair 6**
```
Shopping is about the product
vs
Shopping is about the story behind the brand
```

**Pair 7**
```
I'm happy with how I discover new brands today
vs
Discovery feels broken — I'm missing great brands
```

**Pair 8**
```
I'd pay more for a product from a homegrown brand
vs
Price matters more than where the brand is from
```

**Data captured:**
- Each selection
- Time spent per pair (flags rushed responses)
- Sequence of answers (reveals priority hierarchy)

**Why this works:**
- Zero leading questions
- Reveals *true* preference, not *stated* preference
- Pair 7 is the kill-shot: direct pain validation without asking "do you have a problem?"
- Pair 8 tests willingness to pay premium (critical for marketplace viability)

---

### Screen 2: Trust Ladder

**Copy at top:**
```
Before you buy from a brand you've never heard of — 
what do you need to see first?

Drag these into order. Put the most important one at the top.
```

**The 6 Rungs (presented as draggable cards):**

1. A friend or family member used it and liked it
2. 100+ verified reviews with photos
3. Featured in a magazine or credible publication
4. The founder's story resonates with me
5. A trusted influencer or curator recommended it
6. Clean product photos and professional website

**UI:**
- Vertical stack of 6 cards
- Drag handles on left
- Numbers auto-update as you reorder
- "Looks good" button at bottom (appears after first reorder)

**Data captured:**
- Final ranking order
- Number of reorders (flags indecision)
- Time to completion

**Why this works:**
- Maps the trust journey precisely
- Reveals whether your platform needs UGC, editorial curation, or founder storytelling
- Ranking forces trade-offs (unlike "select all that apply")

---

### Screen 3: Discovery Habits (4 rapid-fire questions)

**Format:** 
Simple single-select. One question per screen. Fast progression.

**Q1:** How often do you actively look for new brands?
- Daily
- Weekly  
- Monthly
- Only when I need something specific
- Rarely

**Q2:** When you last discovered a new brand you loved, where did you find it?
- Instagram/social media
- Friend recommended it
- Physical store or market
- Existing marketplace (Amazon, Myntra, etc)
- Google search
- Blog or magazine
- Can't remember

**Q3:** How do you feel about the brands Instagram shows you?
- Same things over and over
- Mostly relevant to me
- Too random
- I don't use Instagram for discovery

**Q4:** If there was a place that only showed you new, emerging brands — would you check it?
- Yes, I'd visit regularly
- Maybe occasionally
- Probably not
- Definitely not

**Data captured:**
- Discovery frequency (validates market size)
- Current channel dominance
- Algorithm fatigue level
- Intent to use platform

---

### Screen 4: Thank You + Waitlist

**Copy:**
```
You're done. Thank you.

We're building a discovery platform for people like you.
Want early access when we launch?

[Email input field]
[Button: Yes, let me know]
[Link: No thanks]
```

**Microcopy below:**
"No spam. Just one email when we're live."

**Data capture:**
- Email (only if provided)
- Waitlist opt-in rate (key demand signal)

---

## BRAND FLOW

### Screen 1: Brand Origin Story

**Copy at top:**
```
Let's trace your customer journey.

Where did your first customers come from? Where are they coming from today? 
This helps us understand what's working — and what's not.
```

**The 5 Scenes (presented as a visual journey):**

**Scene 1:** Your very first customer
```
Where did customer #1 come from?
- Friend or family
- Instagram post
- Word of mouth
- Local market or event
- Online marketplace
- Other
```

**Scene 2:** Your first 10 customers
```
How did most of them find you?
- Instagram organically
- Paid Instagram ads
- WhatsApp forwards
- Physical presence (market/store)
- Existing marketplace listing
- Other
```

**Scene 3:** Today's customers
```
Where do MOST of your customers come from now?
- Instagram (organic)
- Instagram (paid ads)
- Marketplaces (Amazon, Flipkart, Myntra, etc)
- Your own website
- Repeat customers
- Word of mouth
- Other
```

**Scene 4:** Your wishlist
```
If you could wave a wand — where would you WANT customers to come from?
- A dedicated discovery platform for emerging brands
- More organic Instagram reach
- Stronger word of mouth
- My own brand website
- Physical retail presence
- Other
```

**Scene 5:** The gap
```
What's stopping you from getting customers the way you want?
- Can't afford ads
- Algorithm doesn't show my posts
- Don't know how to drive traffic to my website
- Hard to build trust with new customers
- Too much competition on marketplaces
- Other
```

**UI:**
Journey presented as 5 steps. Progress bar at top. Each scene is one screen.

**Data captured:**
- Acquisition channel evolution
- Current channel dependency
- Aspiration vs reality gap
- Specific bottleneck

**Why this works:**
- Story format feels less interrogative
- Maps actual behavior, not aspirations
- Scene 4-5 combo reveals whether a discovery marketplace solves their *real* problem

---

### Screen 2: Discovery Trade-Off

Same 8 pairs as buyer flow, but reframed for brand perspective where needed.

**Adapted pairs for brands:**

Pair 2 (reframed):
```
Hoping the Instagram algorithm shows my posts
vs
A platform that guarantees visibility to interested shoppers
```

Pair 7 (reframed):
```
Getting customers is working fine for me
vs
Customer acquisition feels like an uphill battle
```

**All other pairs stay identical** — they test brand founder psychology around discovery, trust, and pricing.

---

### Screen 3: Growth Bottlenecks (4 questions)

**Q1:** How much do you spend monthly on customer acquisition?
- ₹0 (organic only)
- ₹1,000 - ₹5,000
- ₹5,000 - ₹20,000
- ₹20,000 - ₹50,000
- ₹50,000+

**Q2:** What percentage of your revenue goes to marketplace fees?
- I don't sell on marketplaces
- Under 10%
- 10-20%
- 20-30%
- Over 30%

**Q3:** If a curated discovery platform charged 12% commission, would you join?
- Yes, immediately
- Maybe, depends on traffic quality
- No, too expensive
- I'd need to see proof first

**Q4:** What would make you trust a new platform with your brand?
- See other brands succeeding there first
- Direct founder support and onboarding
- Low upfront cost or free trial
- Transparent traffic and sales data
- Other

**Data captured:**
- CAC budget reality
- Marketplace dependency
- Pricing sensitivity
- Trust requirements

---

### Screen 4: Thank You + Early Access

**Copy:**
```
Thank you for sharing your journey.

We're building a discovery marketplace that puts emerging brands front and center.
Want early access?

[Email input field]
[Button: Yes, I'm interested]
[Link: Not right now]
```

**Microcopy:**
"Priority onboarding for the first 50 brands."

**Data capture:**
- Email
- Early access opt-in rate

---

## UI Design System

### Color Palette
- Primary action: `#534AB7` (purple)
- Selected state: `#EEEDFE` (light purple)
- Progress: `#1D9E75` (teal)
- Background: `#FFFFFF`
- Text primary: `#26215C`
- Text secondary: `#888780`
- Borders: `#D3D1C7`

### Typography
- Primary font: Inter or System Sans
- Heading: 20px, weight 500
- Body: 15px, weight 400
- Microcopy: 13px, weight 400, muted color
- Button: 15px, weight 500

### Spacing
- Screen padding: 24px mobile, 48px desktop
- Vertical rhythm: 24px between sections
- Card padding: 20px
- Button height: 48px

### Interaction Principles
- Auto-advance where possible (reduce clicks)
- No back button (prevents overthinking)
- Progress always visible
- Mobile-first (80% will complete on phone)
- Single column, never side-by-side on mobile

---

## Data Interpretation Framework

### Buyer Segment Analysis

**Discovery Pain Index (DPI)**
Calculate from Discovery Trade-Off:
- Pair 7 selection (broken vs working) = 10 points if "broken"
- Pair 2 selection (curated vs scrolling) = 5 points if "curated"
- Pair 3 selection (instant vs takes time) = 3 points if "instant"

**DPI Score:**
- 15-18 points = Acute pain (ideal early adopter)
- 8-14 points = Moderate pain (viable user)
- 0-7 points = Low pain (not target segment)

**Trust Profile**
From Trust Ladder ranking:
- If "friend recommendation" is #1 = Community-driven trust
- If "reviews" is #1 = Data-driven trust
- If "founder story" is #1 = Narrative-driven trust
- If "influencer" is #1 = Authority-driven trust

**Platform fit:**
- Community-driven = needs social features
- Data-driven = needs robust review system
- Narrative-driven = needs brand storytelling
- Authority-driven = needs editorial curation

**Discovery Frequency**
From Q1 of Discovery Habits:
- Daily/Weekly = high engagement potential
- Monthly = moderate, needs triggers
- Rarely = not primary segment

**Algorithm Fatigue**
From Q3:
- "Same things over and over" = 70%+ → validates hypothesis
- <40% → weak signal, Instagram working fine

**Intent Score**
From Q4 (would you check it?):
- "Yes, regularly" = hot lead
- "Maybe occasionally" = warm
- "Probably not" = abandon

**Waitlist conversion:**
Target: 40%+ opt-in rate from "yes, regularly" respondents

---

### Brand Segment Analysis

**Acquisition Channel Dependency**
From Brand Origin Story:
- If Scene 3 = Instagram paid ads → high CAC, algorithm dependent
- If Scene 3 = Marketplaces → margin squeeze, commoditized
- If Scene 3 = Organic → low CAC but low scale

**Aspiration-Reality Gap**
Compare Scene 3 (current) vs Scene 4 (wishlist):
- Large gap = strong platform demand
- Minimal gap = current channels working

**Critical Bottleneck**
From Scene 5:
- "Algorithm doesn't show posts" = 60%+ → strong signal
- "Hard to build trust" = platform must solve trust problem
- "Can't afford ads" = need low-CAC channel

**CAC Budget Reality**
From Bottleneck Q1:
- ₹20k+ monthly = can pay for platform
- Under ₹5k = needs freemium model

**Marketplace Dependency**
From Q2:
- 20%+ revenue to marketplace fees = margin pain
- Over 30% = urgent need for alternative

**Pricing Sensitivity**
From Q3 (12% commission):
- "Yes immediately" = price-insensitive, quality-focused
- "Maybe" = needs proof of ROI
- "No, too expensive" = wrong segment OR need lower commission tier

**Early Access Opt-In:**
Target: 60%+ from brands with high CAC + marketplace dependency

---

## Bias Prevention Logic

### What We're Avoiding

**Social desirability bias:**
- No questions like "Do you care about supporting homegrown brands?" (people say yes even if behavior says no)
- Trade-offs force revealed preference

**Leading questions:**
- Never "Are you frustrated with Instagram discovery?" 
- Always neutral framing: "How do you feel about..."

**Recall bias:**
- Discovery Diary (Concept 2) dropped because it depends on memory
- Brand Origin Story stays because it maps *patterns* not specific dates

**Priming:**
- Entry screen doesn't mention "broken discovery" or "algorithm problems"
- Neutral: "Help us understand discovery"

**Order effects:**
- Discovery Trade-Off comes first (before Trust Ladder plants ideas)
- Pair 7 is buried in position 7 of 8 (doesn't anchor the whole survey)

**Acquiescence bias:**
- No yes/no questions where "yes" feels agreeable
- Everything is choice-based or ranking-based

---

## Technical Build Spec

### Platform: Typeform or custom React app

**Why Typeform:**
- Pre-built mobile UX
- Logic jumps (segment routing)
- Analytics dashboard
- Email capture built-in
- 2 week build time

**Why custom React:**
- Full brand control
- Advanced interactions (drag-and-drop)
- Lower per-response cost at scale
- 4-6 week build time

**Recommendation:** Start with Typeform, rebuild in React at 500+ responses.

### Data Schema

**Buyer Response Object:**
```json
{
  "id": "uuid",
  "timestamp": "ISO 8601",
  "segment": "buyer",
  "trade_offs": {
    "pair_1": "popular | unknown",
    "pair_2": "scrolling | curated",
    // ... through pair_8
  },
  "trust_ladder": [1, 3, 2, 5, 4, 6],
  "discovery_frequency": "weekly",
  "last_discovery_channel": "instagram",
  "algorithm_feeling": "same_things",
  "platform_intent": "yes_regularly",
  "waitlist_email": "user@example.com | null",
  "completion_time_seconds": 142,
  "device": "mobile | desktop"
}
```

**Brand Response Object:**
```json
{
  "id": "uuid",
  "timestamp": "ISO 8601",
  "segment": "brand",
  "origin_story": {
    "first_customer": "friend",
    "first_10": "instagram_organic",
    "current_main": "instagram_paid",
    "wishlist": "discovery_platform",
    "bottleneck": "algorithm"
  },
  "trade_offs": { /* same structure */ },
  "cac_monthly": "5000-20000",
  "marketplace_fee_pct": "20-30",
  "commission_12pct": "maybe",
  "trust_requirement": "see_success_first",
  "early_access_email": "brand@example.com | null",
  "completion_time_seconds": 168,
  "device": "mobile | desktop"
}
```

---

## Distribution Strategy

### Targeting

**Buyer segment:**
- Instagram ads targeting: 
  - Age 22-38
  - Location: Jaipur, Indore, Lucknow, Chandigarh (tier 2 focus)
  - Interests: homegrown brands, indie fashion, artisan products
  - Behaviors: online shopping, boutique following
- Reddit: r/IndianFashionAddicts, r/DesiBuyersClub
- WhatsApp: forward to 20 contacts who fit profile
- College communities (visual + link in stories)

**Brand segment:**
- Instagram DM outreach to 200 homegrown brands
- LinkedIn posts targeting: "founder", "small business owner", "artisan", location India
- Brand WhatsApp groups
- Startup community Slack/Discord channels
- Email to brands you already know

### Success Metrics

**Volume targets:**
- 70 buyer responses
- 30 brand responses
- Total: 100

**Quality gates:**
- Completion rate >65%
- Average time 2-4 minutes (flags rushed/slow outliers)
- Waitlist opt-in >35% (buyer), >50% (brand)

**Stop signals:**
- Completion rate <40% = UX is broken
- Waitlist opt-in <15% = no demand
- DPI average <6 = pain is too mild

---

## What This Tells You

### Green Light Signals (Build the Platform)

1. **Buyer DPI average >10** = acute discovery pain exists
2. **Algorithm fatigue >60%** = Instagram is failing them
3. **Platform intent "yes regularly" >40%** = demand is real
4. **Waitlist opt-in >40%** = revealed preference matches stated
5. **Brand bottleneck "algorithm" >50%** = supply-side pain validated
6. **Brand early access opt-in >60%** = brands will join

**If 4+ signals are green:** You have a validated problem worth solving.

### Yellow Light Signals (Pivot Required)

1. **Buyer DPI average 6-9** = pain exists but mild
2. **Trust Ladder: "friend rec" dominates** = you need community features, not just curation
3. **Brand current channel = "organic working"** = no urgency to switch platforms
4. **Commission 12% "no, too expensive" >50%** = pricing model broken

**If 2+ signals are yellow:** The pain exists but your solution hypothesis may be wrong. Resurface with interviews to refine.

### Red Light Signals (Kill It)

1. **Buyer DPI average <6** = discovery is not a real problem
2. **Platform intent "probably not" >50%** = no demand
3. **Waitlist opt-in <20%** = talk is cheap, action reveals truth
4. **Brand wishlist ≠ "discovery platform"** = they want something else
5. **Discovery frequency "rarely" >60%** = market too small

**If 2+ signals are red:** Your hypothesis is wrong. Don't build this. Save yourself 18 months.

---

## Timeline

**Week 1:** Build survey (Typeform: 3 days, Custom: 10 days)  
**Week 2-3:** Run distribution, hit 100 responses  
**Week 4:** Analyze data, make go/no-go decision  

**Total:** 4 weeks from start to validated decision.

---

## Next Steps for You

1. **Copy this system into Typeform** (I can generate the exact Typeform JSON if you want)
2. **Design 2-3 test brand cards** for Discovery Trade-Off visual pairs
3. **Write your distribution copy** (Instagram ad, DM template, Reddit post)
4. **Set your kill metrics** (what numbers make you stop vs go?)

Want me to generate any of these assets now?
