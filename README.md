# TCFD Reporting Skill

A Claude Code skill for preparing TCFD (Task Force on Climate-related Financial Disclosures) reports for real estate portfolios.

## What it does

Guides climate risk disclosure across the four TCFD pillars — Governance, Strategy, Risk Management, and Metrics/Targets — with specific support for real estate portfolio analysis including physical risk scoring, transition scenario modeling, and SEC/ISSB compliance.

## Commands

| Command | Description |
|---|---|
| `/physical-risk` | Assess physical climate risk (flooding, wildfire, heat, sea level rise) across a portfolio |
| `/scenarios` | Run TCFD scenario analysis: ordered transition (<2°C) vs. delayed transition (>3°C) |
| `/disclosure` | Draft a full TCFD disclosure for annual report, GRESB, or CDP submission |

## Installation

```bash
npx skills add soapboxbuild/tcfd-reporting-skill
```

Or add to your Claude Code project plugin list:

```json
{
  "plugins": ["soapboxbuild/tcfd-reporting-skill"]
}
```

## Coverage

- Physical risk: acute (flood, wildfire, hurricane, heat) and chronic (sea level rise, water stress)
- Transition risk: policy/legal (carbon pricing, BEPS, MEES), market (green premium, brown discount, CRREM), technology
- Regulatory: SEC Climate Rules, ISSB IFRS S2
- GHG: Scope 1, 2, 3 (Categories 13 and 15)

## License

Apache-2.0 — Soapbox (https://soapbox.build)
