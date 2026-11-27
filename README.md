# Multimodal Logistics Park (MMLP) – Financial Feasibility Model

An illustrative 45-year financial feasibility model for a hypothetical 150-acre multimodal logistics park (MMLP), benchmarked against selected public information about the Nagpur MMLP. The workbook compares a private-sector DBFOT/PPP concession with a government-funded EPC/public-sector comparator.

> **Important:** This is an independent portfolio case study, not an official estimate, valuation, feasibility report, bid model, or forecast for the actual Nagpur MMLP. The operating, financing, construction, and cost assumptions are illustrative. Do not use the outputs for an investment or lending decision.

![MMLP model dashboard](assets/dashboard-preview.png)

## Project objectives

- Assess indicative project-level and equity-level returns for a hypothetical MMLP.
- Test debt-service capacity over the construction and operating period.
- Compare the Authority's modelled cash flows under a stylised PPP structure and a government-funded structure.
- Examine how changes in capital cost, revenue, revenue share, cost overrun, and operating efficiency affect the outputs.
- Present assumptions, calculations, model checks, and source notes transparently.

## Case-study setup

The model uses a 150-acre site archetype and selected Nagpur MMLP benchmarks, but models a **hypothetical new-build project** with financial close assumed in FY2027 and a 45-year concession. The workbook assumes:

- 10 lakh sq. ft. of warehouse area.
- 200,000 TEU per year of container-terminal capacity.
- ₹407 crore of initial PPP-scope capital expenditure.
- Two years of PPP construction, with operations beginning in operating Year 3.
- Three years of government-funded construction, with operations beginning in Year 4.
- Nominal annual cash flows over the concession period.

The ₹407 crore modelled developer-side capex is **not** the actual total cost of the Nagpur MMLP. The model excludes land and external enabling infrastructure such as connecting roads, rail links, water, and power from both cases.

## Illustrative base-case outputs

| Metric | Model output |
|---|---:|
| PPP project IRR (post-tax) | 12.8% |
| PPP project NPV at WACC | ₹212.4 crore |
| PPP equity IRR | 15.9% |
| Minimum DSCR during sculpted repayment years | 1.40x |
| Minimum DSCR in first operating / interest-only year | 0.78x |
| Government NPV – stylised PPP receipt case | ₹537.6 crore |
| Government NPV – government-funded case | ₹650.5 crore |
| Government NPV difference (PPP less government-funded) | **–₹112.9 crore** |

These are outputs of the stated assumptions, not observed project results. The government-funded case produces a higher modelled government NPV in the base case. The PPP case avoids direct in-scope construction funding and allocates specified delivery, demand, and operating risks to the developer. A proper decision would require a risk-adjusted value-for-money assessment, fiscal opportunity-cost analysis, and project-specific evidence.

The first operating year's DSCR is below 1.0x. The model therefore flags the need for a funded debt-service reserve, sponsor support, or a revised financing / repayment structure before the case could be considered bankable.

## Workbook contents

| Sheet | Purpose |
|---|---|
| `Cover` | Case-study scope, objectives, sheet guide, and interpretation warning |
| `Dashboard` | Headline returns, bankability, PPP vs government comparison, and model checks |
| `Inputs` | Central assumptions, units, and source / rationale notes |
| `PPP_Model` | 45-year concessionaire cash flows, operating model, debt schedule, returns, and DSCR |
| `Govt_Model` | Government-funded comparator with separate construction timing and cost assumptions |
| `Sensitivity` | Sensitivity analysis for selected capex, revenue, revenue-share, cost-overrun, and efficiency drivers |
| `Notes_Sources` | Methodology, simplifications, caveats, and source links |

## How to use the workbook

1. Download `MMLP_Feasibility_Model.xlsx` and open it in Microsoft Excel.
2. Start with `Cover`, then read `Notes_Sources` before interpreting the outputs.
3. Change only the blue-font assumption cells on `Inputs`; yellow fills identify key assumptions.
4. Review the `Dashboard` after changing assumptions.
5. Use `Sensitivity` to test downside and upside cases.
6. Check the DSCR and model checks before drawing conclusions.

The workbook uses formulas; spreadsheet rendering and recalculation may differ between Excel-compatible applications. For best compatibility, open and recalculate it in Microsoft Excel.

## Methodology and key limitations

- Project IRR is based on unlevered free cash flow; equity IRR is based on cash flow to equity after modelled debt drawdown, interest, and principal.
- DSCR is calculated as cash flow available for debt service divided by interest plus principal.
- The public-sector comparator is a simplified comparison of modelled Authority receipts under PPP against net cash flows in the government-funded case. It is **not** a formal or complete value-for-money assessment.
- The workbook uses a flat percentage of gross revenue as a proxy for Authority receipts. The Modified Model Concession Agreement for MMLPs uses Minimum Guaranteed Revenue in INR on an XNPV basis as the bidding parameter; this model does not reproduce the actual contract mechanism.
- The model does not include tax-loss carry-forwards, MAT, GST, working capital, terminal value, or detailed phased development. Construction-period interest treatment is simplified.
- Land and external enabling infrastructure are excluded from the modelled cost comparison. Add project-specific costs consistently to both structures for a full appraisal.
- The public benchmarks and the model assumptions are not interchangeable. Each input should be validated against current DPRs, concession documents, engineering estimates, tenant demand, traffic studies, tariffs, and lender terms before use in a real project.

## Public references used in the workbook

- [PIB: Nagpur MMLP – project parameters and commercial operations](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2125325)
- [Ministry of Road Transport and Highways: Modified Model Concession Agreement for MMLPs](https://www.morth.gov.in/sites/default/files/Modified_MCA_for_MMLP.pdf)
- [PIB: Indore MMLP project information](https://pib.gov.in/PressReleasePage.aspx?PRID=1903217)
- [PIB: MoRTH Year-End Review 2025](https://www.pib.gov.in/PressReleaseIframePage.aspx?PRID=2209837)
- [Central Warehousing Corporation: ICD Loni terminal tariff](https://cewacor.nic.in/Docs/CWC_ICD_Loni_Terminal_Tariff.pdf)
- [PIB: Infrastructure project monitoring / flash-report context](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2303115)

Additional market references and detailed input rationales are documented in the workbook's `Notes_Sources` and `Inputs` sheets. Some market references are secondary sources and should be treated as indicative cross-checks only.

## Tools and skills demonstrated

- Microsoft Excel financial modelling
- Long-term project cash-flow forecasting
- Infrastructure project appraisal
- PPP vs public-sector comparator analysis
- NPV, IRR, payback, DSCR, and sensitivity analysis
- Assumption documentation and source traceability

## Repository structure

```text
mmlp-financial-feasibility-project/
├── README.md
├── MMLP_Feasibility_Model.xlsx
└── assets/
    └── dashboard-preview.png
```

---

**Portfolio project by Harsh Kumar** · Prepared November 2026.
