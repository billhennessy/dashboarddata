# Resideo Dealer Performance Dashboard

A static HTML dashboard for viewing dealer and contractor performance data across three Resideo loyalty/rewards programs.

## Pages

| File | Program | Description |
|------|---------|-------------|
| [index.html](index.html) | Dashboard Home | Quick-access overview cards showing current tier and % back for all three programs |
| [pro-perks-record.html](pro-perks-record.html) | Pro Perks Contractor | Tiered rebate program with growth boosters and product family targets |
| [premier-security-record.html](premier-security-record.html) | Premier Security Dealer | Security dealer rewards tracking purchases, participation activities, and quarterly growth targets |
| [premier-comfort-record.html](premier-comfort-record.html) | Premier Comfort Contractor | HVAC/comfort contractor rewards tracking purchases, connectable product adoption, and engagement |

## Programs

### Pro Perks Contractor
Tier-based rebate program (Bronze → Silver → Gold). Tracks:
- Current tier and projected next-year tier
- YTD purchases vs. previous year (annual growth targets at 2%, 5%, 10%)
- Growth booster and product mix booster percentages
- Six product family goals: Connected, Genesis, Water, Energy, Air, Security

### Premier Security Dealer
Percentage-back rewards program for security dealers. Tracks:
- Current % back based on YTD purchases
- QTD and YTD growth vs. prior year
- Participation activities (Coffee Conversations, Tech Talks, business reviews, website requirements)
- Quarterly and annual purchase growth targets

### Premier Comfort Contractor
Percentage-back rewards program for HVAC/comfort contractors. Tracks:
- Current % back based on YTD purchases
- Connectable product ratio and revenue targets
- Engagement activities and Shop Talk participation
- Business review and website participation requirements

## Data Source

Record data is sourced from Salesforce (fields include `SF ID`, `Dealer ID`, `Org ID`). Records are updated periodically — each page displays a `Last Updated` timestamp.

## Usage

Open `index.html` in a browser. No build step or server required — all pages are plain HTML/CSS.
