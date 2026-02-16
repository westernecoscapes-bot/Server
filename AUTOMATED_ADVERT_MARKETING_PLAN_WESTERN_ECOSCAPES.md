# Automated Advert Marketing Plan: Western EcoScapes

## 1) Objective
Build a measurable, mostly automated paid-advertising engine that consistently generates qualified landscape design/installation leads for **Western EcoScapes**, while keeping customer acquisition cost (CAC) predictable and improving return on ad spend (ROAS) over time.

## 2) Primary Outcomes (90-day targets)
- 120–180 qualified leads (form + calls + booked consultations)
- Cost per qualified lead (CPQL): $60–$110 (market dependent)
- Consultation booking rate from leads: 25%+
- Closed-project rate from consultations: 20%+
- Blended ROAS target: 3.0x+ (using pipeline-weighted revenue)

## 3) Audience Segments
1. **Residential Homeowners (Core)**
   - Age 30–65, homeowners, mid/high household income
   - Needs: curb appeal, water-efficient landscaping, outdoor living upgrades

2. **HOA / Property Managers (Secondary)**
   - Multi-property maintenance + sustainability compliance
   - Needs: predictable service, drought-tolerant plans, reduced water bills

3. **New Home Buyers / Renovators (Expansion)**
   - Recently moved, remodeling behavior, home-improvement intent

## 4) Offer Stack for Ads (What we advertise)
- Free 20-minute site consultation
- Seasonal package offers (e.g., "Spring Native Plant Refresh")
- Water-saving landscape audit
- "Before/After" design concept promotion
- Commercial bid request for HOA/property managers

## 5) Channel Mix & Automation

### A. Google Ads (High-intent search)
**Campaign types**
- Brand search
- Non-brand local service search
- Competitor and alternative-intent search
- Performance Max for local lead generation (with strict asset groups)

**Automation**
- Smart bidding: Maximize conversions -> tCPA once 30+ conversions
- Responsive Search Ads with automated asset testing
- Offline conversion imports from CRM (closed deal, project value)
- Rules/scripts:
  - Pause keywords/ad groups with high spend + no qualified conversions
  - Increase budget on high-converting campaigns during peak hours

### B. Meta Ads (Demand capture + retargeting)
**Campaign types**
- Lead-gen forms for consultation requests
- Traffic + conversion campaigns to landing pages
- Retargeting: 7/30/90-day site visitors and video viewers

**Automation**
- Advantage+ audience expansion (with exclusions)
- Dynamic creative testing (headline/image/video combinations)
- Automated rules:
  - Scale ad sets +15% when CPL < target for 3 days
  - Reduce spend when lead quality score drops below threshold

### C. Local Awareness Layer (Optional)
- YouTube short video ads with service-area targeting
- Nextdoor/local display where available

## 6) Funnel Architecture

### Top of Funnel (TOFU)
- Creative hooks: "Save water, boost curb appeal," "Eco-friendly transformations"
- Proof assets: before/after galleries, testimonials, local project highlights

### Middle of Funnel (MOFU)
- Landing pages by intent:
  - Residential design/install
  - Drought-tolerant conversions
  - HOA/commercial services
- Clear CTA: book consultation / request estimate / call now

### Bottom of Funnel (BOFU)
- Retargeting ads with urgency offers (limited seasonal slots)
- SMS/email reminder automation for unbooked leads
- Sales follow-up SLA: first contact in <5 minutes

## 7) Tracking, Attribution, and Data Pipeline

### Required setup
- GA4 + Google Ads conversion linking
- Meta Pixel + Conversions API
- Call tracking numbers by campaign
- CRM pipeline stages:
  - New Lead -> Qualified -> Consultation Booked -> Proposal Sent -> Won/Lost

### Automation flow
1. Ad click / lead form submission
2. Lead enters CRM with source/medium/campaign parameters
3. Lead scoring model assigns quality tier (A/B/C)
4. Auto-routing:
   - A leads: immediate call task + SMS
   - B leads: same-day follow-up
   - C leads: nurture sequence
5. Closed deals pushed back to ad platforms as offline conversions

## 8) Creative System (Automated production cadence)
- Weekly: 2 new image concepts + 1 short video variant per audience
- Monthly: refresh offer angles and headline families
- Creative matrix:
  - Problem (high water bills, outdated yard)
  - Promise (lower maintenance + premium look)
  - Proof (project photos, ratings, testimonials)
  - CTA (book free consult)

## 9) Lead Nurture Automation

### Email/SMS sequence (example)
- Day 0: thank-you + booking link
- Day 1: testimonial + project gallery
- Day 3: water-savings case study
- Day 7: limited-slot reminder
- Day 14: reactivation offer

### Chat/assistant automation
- Website chatbot qualifies by budget, timeline, zip code, property type
- Auto-schedules calls on integrated calendar

## 10) Budget Model (starter recommendation)
- Total monthly ad budget: $6,000–$15,000
  - Google Ads: 50%
  - Meta Ads: 35%
  - Retargeting/experimental: 15%

### Scaling rule
- Increase total spend by 10–20% per week only when:
  - CPQL on target for 7 days
  - Booking rate stable or increasing
  - Sales team response SLA maintained

## 11) KPI Dashboard (weekly)
- Spend by channel/campaign
- Leads and qualified leads
- CPQL and CAC
- Consultation booking rate
- Proposal-to-close rate
- Revenue and pipeline value by source
- ROAS (initial + 30/60/90-day lag)

## 12) 30-60-90 Day Execution Roadmap

### Days 1–30 (Foundation)
- Tracking stack, CRM fields, offline conversion sync
- Launch core search + retargeting + one residential Meta campaign
- Deploy 2 landing pages and baseline reporting dashboard

### Days 31–60 (Optimization)
- Tighten keywords/audiences using lead quality data
- Expand creative testing matrix
- Introduce automated bid strategy transitions and rule tuning

### Days 61–90 (Scale)
- Expand into adjacent geo areas and service-specific campaigns
- Increase budget on highest quality segments
- Implement lifecycle reactivation campaigns for older leads

## 13) Operating Rhythm
- Daily: spend pacing, lead quality checks, rule alerts
- Weekly: creative + landing page performance review, budget reallocations
- Monthly: strategic review of service mix, seasonality, and ROI by segment

## 14) Risk Controls
- Exclude unserviceable geographies and low-value query themes
- Use negative keyword expansion weekly
- Cap frequency in retargeting to prevent ad fatigue
- Enforce duplicate lead detection and spam filtering in CRM

## 15) Success Criteria
The plan is successful when Western EcoScapes can predictably convert ad spend into profitable booked work with increasing efficiency, supported by closed-loop attribution and automated optimization loops.
