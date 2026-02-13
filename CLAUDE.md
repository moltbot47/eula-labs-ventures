# EULA Labs Ventures

## What This Is
$2M investor vision site for **EULA Labs — Empowering Universal Learning through AI**. A diversified venture studio combining real estate (EULA Properties), open-source assistive robotics (ARIA Research), and community-funded AI infrastructure (The Claw Protocol Collective). Raising $2M to purchase the Pembrook compound in Houston, TX and build community-owned AI research & education infrastructure.

## Capital Raise: $2M
- **$1M** — Purchase Pembrook compound (3 units, 7,392 sq ft) → AI research & education training center
- **$1M** — Compute infrastructure, GPU hardware, developer hiring, ARIA devices, operations

## SEC Compliance Path
- **Reg CF (Regulation Crowdfunding)** — Up to $5M/year, anyone can invest, requires registered funding portal (Wefunder, Republic, StartEngine)
- **Reg D 506(c)** — Accredited investors only, no dollar cap, allows public marketing
- **Recommended:** Reg CF + Reg D 506(c) side-by-side for broadest reach
- Tokens structured as **LLC membership interests** (non-transferable, SEC-compliant)

## Entity Structure
```
EULA Labs Ventures LLC (Master Fund — Delaware)
├── ELV Real Estate SPV LLC → Pembrook compound
├── ELV Compute & AI SPV LLC → GPUs, servers, agent infrastructure
├── ELV Research SPV LLC → ARIA devices, R&D, grants
└── ELV Management LLC → Management fees, carried interest
```

## Repos
- **GitHub (primary):** github.com/dbutler-a11y/eula-labs-ventures
- **GitHub (community):** github.com/moltbot47/eula-labs-ventures
- **Live Site:** dbutler-a11y.github.io/eula-labs-ventures
- Push to both: `git push origin main && git push moltbot main`

## Tech Stack
- Static HTML5 + embedded CSS + Google Fonts (Source Serif 4, Inter, JetBrains Mono)
- ARIA Research design system (light mode, navy/blue palette)
- No framework, no build step, no backend
- GitHub Pages deployment

## Design System (ARIA Match)
- **Fonts:** Source Serif 4 (headings), Inter (body), JetBrains Mono (metrics)
- **Colors:** Navy #1a365d, Blue #3182ce, Accent #63b3ed, Success #38a169
- **Layout:** Light mode, frosted glass nav, 1100px max-width, 17px base font
- **Patterns:** Card layouts, navy gradient stats bars, pill badges, hover transforms

## Key Files
```
index.html                    # Complete $2M vision site (single file, ARIA design)
CLAUDE.md                     # This file
```

## The Three Pillars

### 1. EULA Properties (~/eulaproperties/)
- Pembrook Compound: 3 units, 7,392 sq ft, Houston TX
- 9132 ($440K HQ), 9134 ($385K Compute Lab), 9136 ($385K Education Center)
- Total appraised: $1.21M | Hard asset collateral for investors
- Site: github.com/dbutler-a11y/eulaproperties-test-current

### 2. ARIA Research (~/aria-research/) — Flagship Initiative
- Open-source assistive robotics for Parkinson's disease
- 4 products: Bloom ($280), Guide ($380), Frame ($220), Rover ($430)
- Raspberry Pi 5 hardware, MIT licensed, grant-eligible (NIH SBIR, NSF I-Corps)
- Site: dbutler-a11y.github.io/aria-research

### 3. The Claw Protocol (~/open-claw/)
- Community-led AI agent coordination framework
- 5-tier contribution scoring (Infrastructure 5x > Compute 3x > Agents 2x > Research 1.5x > Community 1x)
- OpenClaw browser automation, compute sovereignty roadmap
- Research paper: paper/coordinated-intelligence-systems.md

## Financial Steward Role
- **Target:** DeAngelo Kirkland — M&A | Market Research | Excel | Private Equity
- **Role:** Manages fund admin relationship (Carta/Allocations), milestone-based capital releases, quarterly P&L, investor relations
- **Platform:** Carta or Allocations (end-to-end: capital calls, distributions, K-1s, investor portal)
- **Gets:** Tier 1 contributor (5x), revenue share, governance weight, negotiated equity
- **Division:** "I build the technology. You manage the money. The fund admin handles the compliance."

## Profit Center Roadmap (Year 1: $1.5M-$2M)
1. Agent-as-a-Service (OpenClaw) → $30K-$60K/mo at scale
2. AI Consulting (EULA Labs brand) → $25K-$50K/mo
3. GPU-as-a-Service (own compute) → $20K-$40K/mo at scale
4. ARIA Device Pre-Orders + Grants → $10K-$20K/mo
5. Pembrook Rental + Events → $5K-$10K/mo

## Action Items
- [ ] Publish outstanding research paper: **Coordinated Intelligence Systems** (Claw Protocol)
- [ ] Publish outstanding research paper: **Blood Pressure Research**
- [ ] Publish outstanding research paper: **Cure Reversal Research**
- [ ] Research in depth: **Liquidation Rights** — pro-rata distribution upon dissolution after creditor satisfaction (what this means for investors, order of payouts, how SPV structure affects it)
- [ ] Research in depth: **Non-Transferable Membership Interests** — what "no speculation" means practically (can members sell/trade their interests? what happens if a member leaves? how does this affect investor liquidity and exit options?)
- [ ] Research in depth: **Anti-Dilution** — how contribution decay mechanism (Tier 1 at half-speed) maintains relative positioning and protects early investors from being diluted by later contributors
- [ ] Research in depth: **Anti-Capture Safeguards** — understand each mechanism and how they protect the community:
  - 5% weight ceiling (no single member >5% governance weight — what happens if someone exceeds it?)
  - Quadratic scaling (influence grows sub-linearly — how exactly does the math work?)
  - Leadership rotation (mandatory every 6-12 months — who enforces this? what if no one wants to rotate?)
  - Fork rights (community can fork all open-source assets — what does this look like legally? how does it interact with SPV structure?)
  - Contribution decay (scores decay over time, Tier 1 at half speed — what's the decay rate? what's the floor?)
- [ ] Engage securities attorney (2-week Form C filing deadline)
- [ ] Engage CPA for reviewed financial statements (first-time issuer, 3-7 days)
- [ ] Select Reg CF funding portal (Wefunder, Republic, or StartEngine)
- [ ] Form EULA Labs Ventures LLC in Delaware
- [ ] Send DeAngelo the investor vision site link

## Review Before Final Commit: Research Paper Alignment Report

Comparison of `coordinated-intelligence-systems.md` vs `index.html` vs `form-c-draft.html`. Must resolve before attorney filing.

### Critical (fix before filing)
- [ ] **Revenue projections have no paper basis** — $1.5M-$2M Year 1 target is a business assumption, not validated by the paper. Don't present alongside paper citations in a way that implies paper validation.
- [ ] **"Tokens" language in Form C** — heading "Tokens = LLC Membership Interests" invites unnecessary SEC/crypto scrutiny. Let attorney reframe using only "membership interests" or "membership units."

### Moderate (fix before final version)
- [ ] **Form C cites wrong section** — Revenue allocation source says "Section 5" but correct section is **7.2**
- [ ] **Half-speed decay shown as steward perk** — Site presents it as a personal benefit, but it's a structural Tier 1 feature for ALL infrastructure investors. Clarify.
- [ ] **Invented voting categories** — "Advisory voting" and "Participation voting" (Tiers 4-5) don't exist in the paper and could mislead about voting rights. Replace with "proportional voting weight."
- [ ] **"Paper backs the entire framework" is overstated** — Paper backs governance/contribution model only, NOT real estate thesis, revenue projections, or product pricing. Narrow the claim.
- [ ] **68% freezing-of-gait claim unattributed** — Not in the paper. Either cite the source study (Ghai et al. 2018) or remove.
- [ ] **EULA acronym inconsistency** — Two different expansions used in same documents (intentional branding choice — confirm or standardize)
- [ ] **Ethics framework missing from site** — Paper has 5 ethical principles + review process (Section 12) that are strong trust signals for healthcare-adjacent fundraising. Consider adding.

### Minor (nice to fix)
- [ ] Tier 3 name: "Agent & Code Development" (paper) vs "Agents & Code" (site) — standardize
- [ ] Decay trigger (6 months) and floor (0.3) from paper not mentioned on site
- [ ] Supermajority thresholds (75%) and 14-day cooling period from paper omitted
- [ ] "Agent Metaverse" term used on site but not in paper

## Related Projects
- ~/eula-labs/ — EULA Labs main brand/consultancy landing page
- ~/eulaproperties/ — Property investment site
- ~/aria-research/ — ARIA robotics research site
- ~/open-claw/ — Claw Protocol Collective
- ~/agent-workstation/ — Remote AI agent control center

## Auth
- `gh auth switch --user dbutler-a11y` for primary account
- `gh auth switch --user moltbot47` for community account

## Deployment
```bash
# GitHub Pages deploys automatically from main branch
git push origin main    # Updates live site at dbutler-a11y.github.io/eula-labs-ventures
```
