# AI Prompt Log — Domo PMM Writing Test

## Tools Used
Claude Code (Claude Opus 4.6) with:
- Domo Knowledge Graph (messaging database)
- Figma Developer MCP (for design component inspection)
- Web search for competitive landscape and market data

---

## Prompt 1: Knowledge Graph Queries (Domo Messaging)
**Purpose:** Pull canonical messaging, value propositions, and persona frameworks for Domo Apps

Queries executed:
1. "Domo Apps ecosystem messaging value propositions and positioning"
2. "App Studio low-code no-code messaging and value propositions"
3. "App Catalyst AI vibe coding messaging"
4. "Citizen development citizen developer low-code messaging"
5. "Governance security data apps permissions"
6. "IT leader CIO technical persona messaging"
7. "Business analyst persona messaging"
8. "Custom apps pro-code developer framework messaging"
9. Document search for "apps" across all messaging content
10. Product profiles for Domo Apps, App Catalyst, Agent Catalyst, Domo BI, Data Integration, Magic Transformation, Domo Embed

**Result:** Full canonical messaging framework including platform narrative, product positioning, persona-specific messaging, and brand constraints. See research-brief.md.

---

## Prompt 2: Competitive Landscape & Market Research
**Purpose:** Understand how competitors position their app-building capabilities and current market trends

Web searches:
1. "Microsoft Power Apps positioning low-code 2025 2026"
2. "Salesforce Lightning Platform app development"
3. "ServiceNow App Engine low-code Gartner"
4. "Appian Mendix OutSystems low-code positioning"
5. "Google AppSheet no-code positioning"
6. "citizen development trends Gartner Forrester 2025 2026"
7. "low-code no-code market size 2025 2026 2030 forecast"
8. "vibe coding AI-assisted development trends statistics 2025 2026"
9. "Domo G2 reviews app building custom apps user quotes"
10. "Domo Gartner Peer Insights reviews apps"
11. "spreadsheet workflow problems enterprise shadow IT statistics"
12. "BI dashboard adoption bypass export Excel statistics"
13. "internal tools custom coded expensive slow build statistics"

**Result:** 7 competitors mapped with positioning and differentiation. Market stats compiled. User feedback from G2 (897 reviews) and Gartner Peer Insights (489 reviews). See research-brief.md.

---

## Prompt 3: Product Page Content Extraction
**Purpose:** Get detailed product facts from Domo's public product pages

Pages fetched:
1. domo.com/news/press/domo-launches-app-catalyst (App Catalyst launch press release)
2. domo.com/business-apps/app-dev-framework (Pro-code framework)
3. domo.com/automation/app-development-services (App development services overview)

**Result:** Detailed product capabilities, governance features, CEO quotes, and service models. See research-brief.md.

---

## Prompt 4: Figma Component Inspection
**Purpose:** Catalog the Domo design system components for code implementation

File inspected: composable-product-pages-feb-2026

Components cataloged:
- 97+ component definitions, 65+ component sets
- UI components: Button (6 variants), Card Basic (8 variants), Text Section Title, Text Hero Jumbo, Subnav, Accordion, Tab Grid, Panel List
- 37 icon component sets (duotone + regular styles)
- Typography scale: 14 type roles (Display XL through Body S)
- Color palette: 69 unique colors extracted
- Spacing system: 8-value scale from 4px to 80px
- Radius system: 4px to 9999px

**Result:** Full component inventory with design tokens and code-ready CSS variables.

---

## Prompt 5: Deliverable Generation
**Purpose:** Write the three deliverables using Domo messaging, research findings, and Figma component patterns

Approach:
- All copy grounded in canonical Domo messaging for Apps and App Catalyst
- Persona messaging matched to IT Leader (precision/control/governance) and Business Analyst (empowerment/efficiency) frameworks
- Statistics sourced from web research (Gartner, Retool, G2, Luzmo)
- Visual design matched to Figma component patterns (Card Basic, Text Hero Jumbo, Button variants)
- Brand compliance verified against Domo brand guidelines

**Result:** Single-page HTML with all 3 deliverables. See output/index.html.

---

## Time Allocation (approximate)
- Research & messaging queries: ~45 minutes
- Competitive analysis & market data: ~30 minutes
- Figma inspection & design tokens: ~15 minutes
- Writing & coding deliverables: ~45 minutes
- Review & refinement: ~15 minutes
- **Total: ~2.5 hours**
