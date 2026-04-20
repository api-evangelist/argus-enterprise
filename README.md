# ARGUS Enterprise (argus-enterprise)
ARGUS Enterprise is the industry-standard commercial property valuation and cash flow forecasting software by Altus Group, now integrated into the ARGUS Intelligence Platform. It provides lease-by-lease cash flow modeling, property valuations using DCF and yield-based methods, budgeting and forecasting, scenario testing, and 40+ industry-standard reports. Trusted by real estate investors, portfolio managers, valuation professionals, and asset managers worldwide.

**URL:** [https://www.altusgroup.com/solutions/argus-enterprise/](https://www.altusgroup.com/solutions/argus-enterprise/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Altus Group, Asset Management, Cash Flow Modeling, Commercial Real Estate, Portfolio Management, Valuation

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### ARGUS Enterprise Core API
Core REST API for the ARGUS Enterprise platform providing programmatic access to commercial real estate investment management capabilities including property data, portfolio management, cash flow projections, valuations, tenants, leases, and reporting.

**Human URL:** [https://www.altusgroup.com/solutions/argus-enterprise/](https://www.altusgroup.com/solutions/argus-enterprise/)

#### Tags:

 - Analytics, Cash Flow, Leases, Portfolio Management, Properties, Reporting, Valuations

#### Properties

- [Documentation](https://www.altusgroup.com/argus/downloads/argus-enterprise/)
- [OpenAPI](openapi/argus-enterprise-core-openapi.yml)
- [Authentication](https://www.altusgroup.com/support/start-using-argus-intelligence/)

### ARGUS Enterprise Webhook API
Webhook service for real-time event notifications for property changes, valuation updates, and lease events.

**Human URL:** [https://www.altusgroup.com/solutions/argus-enterprise/](https://www.altusgroup.com/solutions/argus-enterprise/)

#### Tags:

 - Events, Real-Time, Webhooks

#### Properties

- [Documentation](https://www.altusgroup.com/argus/downloads/argus-enterprise/)
- [OpenAPI](openapi/argus-enterprise-webhooks-openapi.yml)

## Common Properties

- [Website](https://www.altusgroup.com/solutions/argus-enterprise/)
- [Documentation](https://www.altusgroup.com/argus/downloads/argus-enterprise/)
- [GettingStarted](https://www.altusgroup.com/support/start-using-argus-intelligence/)
- [Portal](https://cloud.altusplatform.com/login)
- [Support](https://www.altusgroup.com/support/)
- [Training](https://www.altusgroup.com/argus/training/)
- [TermsOfService](https://www.altusgroup.com/terms-of-use/)
- [PrivacyPolicy](https://www.altusgroup.com/privacy-policy/)
- [JSON-LD](json-ld/argus-enterprise-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Lease-by-Lease Cash Flow Modeling | Model cash flows at the individual lease level across all property types. |
| Multiple Valuation Methods | DCF, cap rate, hardcore, term and reversion, and initial yield methodologies. |
| Budgeting and Forecasting | Property-level budgets with budget-to-actual tracking and prior-year comparison. |
| Scenario Analysis | Run what-if scenarios to assess best-case and worst-case investment outcomes. |
| Sensitivity Analysis | Stress-test yield rates, growth assumptions, and modeling parameters. |
| Portfolio Reporting | 40+ industry-standard asset and portfolio reports. |
| Market Leasing Assumptions | Configure market leasing for new, vacant, and renewing spaces. |
| Debt Modeling | Model leveraged and unleveraged returns with debt tranche configuration. |
| ISO 27001 Certified | ISO/IEC 27001:2022 certified and SOC 2 Type II audited. |
| ARGUS Intelligence Integration | Portfolio dashboards and benchmarking via ARGUS Intelligence Platform. |

## Use Cases

| Name | Description |
|------|-------------|
| Asset Valuation | Produce DCF and yield-based valuations for appraisals and acquisitions. |
| Portfolio Performance Monitoring | Monitor portfolio-level performance against budgets. |
| Acquisition Underwriting | Underwrite new property acquisitions with detailed cash flow analysis. |
| Asset Management Budgeting | Create and track property-level budgets against actual performance. |
| Investor Reporting | Generate standardized reports for investors, lenders, and boards. |
| Disposition Analysis | Model disposition scenarios and exit valuations for hold/sell decisions. |

## Integrations

| Name | Description |
|------|-------------|
| ARGUS Intelligence Platform | Native integration for portfolio dashboards and benchmarking. |
| ARGUS Developer | Integration for development-to-stabilization lifecycle management. |
| Yardi | Import property management and lease data from Yardi. |
| MRI Software | Integrate MRI property management data into cash flow models. |
| JLL | JLL uses ARGUS Enterprise for global asset management and portfolio analytics. |
| CBRE | CBRE uses ARGUS Enterprise for valuation and investment analysis. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ARGUS Enterprise Core OpenAPI](openapi/argus-enterprise-core-openapi.yml)
- [ARGUS Enterprise Webhooks OpenAPI](openapi/argus-enterprise-webhooks-openapi.yml)

### JSON Schema

36 schema files in [json-schema/](json-schema/)

### JSON Structure

36 structure files in [json-structure/](json-structure/)

### JSON-LD

- [ARGUS Enterprise Context](json-ld/argus-enterprise-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ARGUS Enterprise API](capabilities/shared/argus-enterprise-api.yaml) — 6 operations for property, portfolio, valuation, lease, and cash flow management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [CRE Investment Management](capabilities/cre-investment-management.yaml) | ARGUS Enterprise | 6 | Asset Manager, Portfolio Manager |

## Vocabulary

- [ARGUS Enterprise Vocabulary](vocabulary/argus-enterprise-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 6 actions, 1 workflow, and 2 personas

## Rules

- [ARGUS Enterprise Spectral Rules](rules/argus-enterprise-spectral-rules.yml) — 14 rules across 6 categories enforcing ARGUS Enterprise API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
