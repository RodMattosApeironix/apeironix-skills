---
name: exposure-summary-builder
title: Commercial Insurance Exposure Summary Builder
collection: ai-insurance-automation-guide
prompt_number: 8
category: commercial-pc
capability: underwriting-intelligence
primary_role: commercial-insurance-analyst
secondary_roles:
  - commercial-insurance-producer
  - commercial-account-executive
  - commercial-account-manager
  - placement-specialist
  - underwriting-specialist
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Exposure Summary Builder

## Purpose

Transform raw, fragmented, or unstructured commercial insurance exposure data into a clean, underwriter-ready summary that makes the account’s risk profile easier to understand, evaluate, and present.

This Skill is designed to help the insurance professional:

- Organize exposure data into logical categories
- Normalize inconsistent or fragmented information
- Highlight the exposures that matter most
- Identify geographic, operational, financial, and other concentrations
- Detect meaningful trends or patterns
- Surface inconsistencies or data-quality concerns
- Identify underwriting sensitivities
- Separate documented facts from assumptions
- Produce a concise summary suitable for submissions, internal reviews, or renewal strategy

The objective is **not** to merely restate the schedule.

The objective is to convert raw exposure information into a structured **Exposure Intelligence Summary** that helps an underwriter, broker, or advisor understand what the data means.

---

# Core Outcome

A successful use of this Skill should allow the reader to quickly answer:

- What are the major exposures?
- How large is each exposure category?
- Where are exposures concentrated?
- Which locations, operations, customers, vehicles, employees, or other factors drive the most risk?
- Are there material trends?
- Are there unusual values or inconsistencies?
- What appears most important from an underwriting perspective?
- Which exposures may create higher frequency or severity?
- What information is missing?
- What needs to be clarified before the data is relied upon?

The final output should be useful for both:

1. **Underwriting evaluation**, and
2. **Broker or advisor strategy**.

---

# Best Used For

Use this Skill when reviewing:

- Property schedules
- Statements of values
- Vehicle schedules
- Driver schedules
- Payroll schedules
- Workers’ compensation exposure data
- Revenue schedules
- Location schedules
- Equipment schedules
- Inland marine schedules
- Contractor equipment lists
- Customer concentration data
- Vendor concentration data
- Product schedules
- Multi-state exposure summaries
- Submission exposure data
- Renewal exposure data
- Raw spreadsheet exports
- Agency Management System exports
- Client-provided schedules
- Mixed or unstructured account data

This Skill is especially valuable before:

- Marketing an account
- Preparing a carrier submission
- Conducting a renewal review
- Building an underwriting narrative
- Evaluating concentration risk
- Comparing year-over-year exposures

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A formal appraisal
- A replacement-cost valuation
- An actuarial analysis
- A legal opinion
- A coverage determination
- A carrier underwriting decision
- A formal catastrophe model
- A geospatial catastrophe analysis unless appropriate data and tools are available
- A formal financial audit
- A complete exposure verification process
- Client confirmation of exposure data

This is an **exposure organization, analysis, and underwriting-intelligence Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Analysts
- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Placement Specialists
- Marketing Specialists
- Underwriting Specialists
- Risk Advisors
- Agency Principals
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Raw exposure data, schedule, or exposure summary**

Recommended format:

```text
Data:
[PASTE SCHEDULE / EXPOSURES]
```

The data may contain:

- Locations
- Revenue
- Payroll
- Property values
- Vehicles
- Drivers
- Equipment
- Employees
- Customers
- Vendors
- Products
- Operations
- Class codes
- States
- Territories
- Other relevant exposures

If the data is too incomplete to support meaningful analysis, identify the missing information before producing firm conclusions.

---

# Recommended Inputs

The following inputs materially improve the analysis:

- Client name
- Industry
- Policy period
- Renewal date
- Prior-year schedule
- Current-year schedule
- Revenue
- Payroll
- Employee count
- Number of locations
- States of operation
- Location addresses
- Building values
- Business personal property values
- Inventory values
- Equipment values
- Business-income values
- Vehicle count
- Vehicle type
- Vehicle garaging
- Driver count
- Driver ages where appropriate and permissible
- Payroll by class code
- Revenue by operation
- Revenue by state
- Revenue by customer
- Revenue by product
- Customer concentration
- Vendor concentration
- Subcontractor costs
- International exposure
- Catastrophe-zone information
- Prior loss data
- Current program structure
- Historical exposure trends
- Known data-quality issues

---

# Preferred Source Documents

Where available, prioritize:

1. Current client-confirmed exposure schedules
2. Current statement of values
3. Current payroll schedules
4. Current vehicle schedules
5. Current driver schedules
6. Current revenue schedules
7. Current equipment schedules
8. Current ACORD applications
9. Current supplemental applications
10. Current policy schedules
11. Current Agency Management System data
12. Prior-year schedules
13. Producer or Account Manager notes

When prior-year and current-year values conflict, do not assume which is correct without context.

---

# Source Hierarchy

When information conflicts, prioritize:

1. Current client-confirmed exposure data
2. Current carrier or policy schedules
3. Current applications
4. Agency-verified data
5. Current operational or financial schedules
6. Prior-year exposure data
7. Internal notes
8. Industry norms and reasonable inference

When sources conflict:

- Identify the discrepancy
- Do not silently reconcile it
- Use the most current authoritative source where appropriate
- Flag material differences for confirmation

---

# Data Integrity Standard

Before analyzing the exposure profile, evaluate whether the data itself is reliable enough to use.

Review for:

- Missing values
- Blank fields
- Duplicate records
- Conflicting totals
- Impossible values
- Unusual outliers
- Inconsistent units
- Inconsistent date periods
- Inconsistent location names
- Inconsistent legal entity names
- Potentially outdated values
- Changes that appear too large to accept without explanation
- Totals that do not reconcile

Do not silently “clean” material inconsistencies.

If data is corrected or normalized:

- Identify what was changed
- Preserve the original meaning
- Flag anything requiring confirmation

---

# Data Normalization Standard

Where useful, standardize:

- State names
- Location names
- Coverage categories
- Class codes
- Dollar values
- Dates
- Units
- Vehicle types
- Property categories
- Operational categories

Examples:

- “NV,” “Nevada,” and “Nev.” may be normalized to `Nevada`
- `$2.5MM` and `$2,500,000` may be presented consistently
- Similar locations should not be merged unless there is sufficient evidence they are the same exposure

Normalization should improve readability without changing the underlying data.

---

# Evidence Classification

Every material observation should be treated as one of the following.

## Documented Exposure

Directly supported by the supplied data.

Example:

> 62% of total insured property value is concentrated at the Reno location.

---

## Calculated Observation

Derived directly from documented values.

Example:

> Nevada accounts for approximately 71% of total payroll.

Calculations should use consistent denominators and available data.

---

## Reasonable Exposure Inference

A likely exposure characteristic based on the data and known industry patterns.

Example:

> The high concentration of vehicle count in one operating region may create localized catastrophe or operational concentration.

---

## Data Quality Concern

A discrepancy, missing field, inconsistency, or unusual value requiring confirmation.

Example:

> The total vehicle count in the schedule is 42, while the summary indicates 38.

---

## Requires Additional Information

A potentially important issue that cannot be resolved from the available data.

Example:

> Property concentration can be quantified, but catastrophe severity cannot be evaluated without construction, protection, and geographic hazard information.

---

# Confidence Classification

Where useful, classify observations:

### High Confidence

Directly supported by complete and internally consistent data.

### Moderate Confidence

Supported by the available data but dependent on one or more assumptions.

### Low Confidence

Potential issue requiring significant additional information.

Do not give false precision.

---

# Core Principle

## Organize the Data, Then Explain What It Means

Do not begin with conclusions.

First:

1. Understand the dataset
2. Normalize it
3. Reconcile totals where possible
4. Identify concentrations
5. Detect trends and anomalies
6. Translate findings into underwriting implications

The value of the Skill comes from interpreting the exposure profile, not merely reformatting it.

---

# Workflow

Follow the workflow in order unless circumstances clearly require another sequence.

---

## Step 1 — Identify the Dataset

Determine:

- What type of schedule is being reviewed
- Time period
- Client or account
- Coverage line or exposure type
- Number of records
- Major data fields
- Units
- Whether historical comparison data exists

Do not assume a schedule represents the entire account unless supported.

---

## Step 2 — Assess Data Completeness

Identify:

- Required fields that are present
- Important fields that are missing
- Blank values
- Partial records
- Duplicate records
- Inconsistent totals
- Potential formatting problems

Classify the dataset when useful.

### Ready for Analysis

Core information appears complete enough for meaningful review.

### Conditionally Ready

Useful analysis is possible, but one or more important limitations exist.

### Not Ready

Critical data is missing or materially inconsistent.

---

## Step 3 — Normalize the Data

Standardize:

- Categories
- Locations
- Units
- States
- Dollar formatting
- Date formatting
- Labels
- Exposure types

Do not merge materially different exposures simply because the names look similar.

---

## Step 4 — Reconcile Totals

Where possible, calculate:

- Total exposure
- Number of records
- Exposure by category
- Exposure by location
- Exposure by state
- Exposure by operation
- Exposure by class
- Exposure by other meaningful dimensions

Compare totals against any provided summary figures.

Flag discrepancies.

---

# Calculation Integrity Standard

Whenever calculations are performed:

- Use the documented values
- State the denominator when percentages matter
- Avoid unnecessary rounding
- Do not fabricate missing values
- Do not extrapolate unless clearly labeled
- Flag totals that do not reconcile

Example:

> Reno represents 58% of the reported TIV based on the locations included in the supplied schedule.

Prefer this over:

> Reno represents 58% of the company's total property exposure.

unless the schedule is known to represent all property exposure.

---

## Step 5 — Organize Key Exposure Categories

Group the data logically.

Potential categories include:

### Property

- Building
- Business personal property
- Inventory
- Equipment
- Business income
- Total insured value

### Auto

- Vehicle count
- Vehicle type
- Garaging
- Radius
- Heavy vs. light vehicles
- Owned / hired / non-owned

### Workers’ Compensation

- Payroll
- Class codes
- States
- Employee concentration
- High-hazard classifications

### Liability

- Revenue
- Operations
- Products
- Completed operations
- Subcontractor costs
- Customer types

### Inland Marine

- Mobile equipment
- Tools
- Contractor equipment
- Transit
- Installation exposure

### Other

- Cyber
- Professional services
- International
- Pollution
- Specialized exposures

Use only categories relevant to the data.

---

## Step 6 — Identify Geographic Concentration

Analyze exposure by:

- State
- City
- County
- Facility
- Region
- Garaging location
- Project location

Where appropriate, identify:

- Largest geographic concentration
- Percentage of total exposure
- Multi-location dependence
- Single-site dependency

Do not infer catastrophe hazard solely from geography unless supported by appropriate current information.

---

## Step 7 — Identify Operational Concentration

Look for concentration in:

- One operation
- One product
- One service
- One class code
- One facility
- One customer type
- One project type
- One vehicle type
- One workforce segment
- One distribution channel

Ask:

> If this concentrated exposure experiences a disruption or severe loss, how much of the business is affected?

---

## Step 8 — Identify Revenue Concentration

When revenue information is available, analyze:

- Revenue by operation
- Revenue by geography
- Revenue by customer
- Revenue by product
- Revenue by business segment

Potential concerns:

- One customer represents a large percentage of revenue
- One state drives most revenue
- One operation dominates the business
- One product creates disproportionate liability exposure

Do not infer customer concentration if customer-level data is unavailable.

---

## Step 9 — Identify Property Concentration

When property data is available, identify:

- Highest-value location
- Percentage of TIV by location
- Number of locations
- Business-income concentration
- Equipment concentration
- Inventory concentration
- Single-site dependency

A location with a large share of TIV may deserve greater underwriting attention.

---

## Step 10 — Identify Workforce Concentration

When payroll or employee data is available, evaluate:

- Payroll by state
- Payroll by class code
- Payroll by occupation
- High-hazard class concentration
- Employee concentration by location
- Employee concentration by operation

Highlight whether a relatively small segment drives a disproportionate share of workers’ compensation exposure.

---

## Step 11 — Identify Fleet Concentration

When vehicle data is available, evaluate:

- Vehicle count
- Vehicle type
- Heavy vs. light vehicles
- Garaging
- Radius
- Specialized vehicles
- Concentration by region
- Exposure growth
- Driver-to-vehicle relationship where data permits

Flag unusually large or rapidly changing fleet exposure.

---

## Step 12 — Identify Product or Service Concentration

Where applicable, determine whether the business depends heavily on:

- One product
- One service
- One customer segment
- One end use
- One contract type

Consider whether the concentrated segment carries different liability or severity characteristics.

---

## Step 13 — Identify Trends

If multiple periods are provided, compare:

- Revenue
- Payroll
- Vehicle count
- Property values
- Employee count
- Location count
- Equipment values
- Inventory
- Subcontractor costs
- Business income
- Other material exposure bases

Calculate meaningful year-over-year changes when possible.

---

# Trend Analysis Standard

For each material trend, identify:

### What Changed

[Exposure]

### Direction

Increasing / Decreasing / Stable

### Magnitude

[Percentage or value where supportable]

### Underwriting Meaning

[Why it may matter]

### Confirmation Needed

[If applicable]

Do not describe a single-period value as a trend.

---

## Step 14 — Identify Outliers

Review for values substantially different from the surrounding data.

Examples:

- One location with unusually high TIV
- One class code with unusually high payroll
- One vehicle category with disproportionate value
- One state with rapid growth
- One customer representing unusually high revenue
- Unusual drop in business-income values
- Large property value change

Outliers may represent:

- Real exposure
- Business change
- Data error
- Reporting inconsistency

Do not automatically assume which.

---

## Step 15 — Identify Underwriting Sensitivities

Translate the data into likely underwriting concerns.

Potential examples:

- Property concentration
- Catastrophic auto severity
- High-hazard payroll
- Rapid exposure growth
- Geographic concentration
- Customer concentration
- Large subcontractor exposure
- High-value equipment
- Insufficient business-income values
- Inconsistent valuation trends
- Limited diversification
- Exposure volatility
- Incomplete schedule data

Only identify sensitivities supported by the dataset.

---

## Step 16 — Distinguish Frequency and Severity Exposure

Where useful, identify:

### Frequency Drivers

Exposures likely to generate recurring claims.

Examples:

- Large vehicle count
- High payroll in repetitive manual roles
- High transaction volume

### Severity Drivers

Exposures capable of producing a large loss.

Examples:

- High-value location
- Heavy commercial vehicles
- Hazardous operations
- Concentrated product liability
- Single critical facility

This distinction helps underwriters understand the risk profile more quickly.

---

## Step 17 — Identify Data Quality Concerns

Create a specific list of:

- Missing records
- Missing values
- Duplicate entries
- Conflicting totals
- Large unexplained changes
- Unclear units
- Potentially stale information
- Inconsistent dates
- Unreconciled schedules

Do not bury data concerns inside general observations.

---

## Step 18 — Determine What Requires Confirmation

Identify specific questions.

Examples:

- Why did payroll increase 38%?
- Does the vehicle schedule include all leased vehicles?
- Why did business-income value decline while revenue increased?
- Is the large Reno location the company's primary production facility?
- Does reported revenue include subcontracted work?
- Are property values replacement cost or another valuation basis?

Questions should be directly connected to underwriting relevance.

---

## Step 19 — Prioritize Findings

Classify findings using:

### Priority 1 — Material

Could meaningfully influence underwriting appetite, pricing, limits, structure, or risk strategy.

### Priority 2 — Important

Should be understood but may not independently drive the underwriting decision.

### Priority 3 — Informational

Useful context with limited immediate underwriting impact.

### Data Validation Required

Cannot be relied upon until clarified.

Do not label every observation as material.

---

# Materiality / Prioritization Framework

Evaluate findings using:

| Factor | Question |
|---|---|
| Exposure Size | How large is the exposure? |
| Concentration | How much is concentrated in one place or activity? |
| Severity | Could it produce a large loss? |
| Frequency | Could it drive recurring losses? |
| Volatility | Has the exposure changed materially? |
| Data Reliability | Is the information trustworthy? |
| Underwriting Impact | Could it affect appetite, pricing, structure, or capacity? |
| Operational Importance | Is it critical to the insured's business? |

Use professional judgment rather than arbitrary scoring unless requested.

---

# Decision Rules

## Meaning Before Formatting

Do not mistake a clean table for analysis.

The output should explain:

- What matters
- Why it matters
- What needs attention

---

## Do Not Invent Missing Values

Never estimate missing exposure values unless explicitly requested and clearly labeled.

---

## Do Not Silently Reconcile Conflicts

If two totals differ, show the discrepancy.

---

## Percentages Need Denominators

Whenever presenting a concentration percentage, make clear what total it is based on.

---

## Large Change Does Not Equal Error

A material year-over-year change may represent:

- Growth
- Acquisition
- Inflation
- New operation
- Reporting change
- Data error

Flag it for explanation rather than assuming the cause.

---

## Concentration Does Not Automatically Mean Poor Risk

Concentration should be identified and interpreted.

It may be:

- Appropriate
- Manageable
- Concerning
- Highly material

depending on the operation and controls.

---

## Current Exposure Data Takes Priority

Use current exposure data over prior schedules unless there is a reason to question it.

---

## Materiality Over Volume

A short list of meaningful findings is better than dozens of minor observations.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Commercial Exposure Intelligence Summary

## Account Snapshot

**Account:** [If known]  
**Industry:** [If known]  
**Data Period:** [If known]  
**Exposure Type:** [Property / Auto / WC / Mixed / Other]

---

# 1. Data Readiness

**Status:** Ready for Analysis / Conditionally Ready / Not Ready

### Data Reviewed

List the schedules or information reviewed.

### Material Data Limitations

List important gaps or inconsistencies.

---

# 2. Executive Exposure Perspective

Provide a concise summary answering:

- What drives the exposure profile?
- Where is the largest concentration?
- What trend stands out?
- What should an underwriter pay attention to first?
- What requires confirmation?

Keep this section concise.

---

# 3. Key Exposure Categories

Use a logical summary table.

| Exposure Category | Total / Scale | Share of Relevant Total | Primary Driver | Underwriting Relevance |
|---|---|---|---|---|
| [Category] | [Value] | [Percentage if useful] | [Driver] | [Why it matters] |

Do not calculate percentages where the denominator is unreliable.

---

# 4. Concentration Analysis

## Geographic Concentration

| Location / Region | Exposure | Share | Why It Matters |
|---|---|---|---|
| [Location] | [Value] | [Percentage] | [Explanation] |

## Operational Concentration

| Operation / Segment | Exposure | Share | Why It Matters |
|---|---|---|---|

## Other Material Concentrations

Include when relevant:

- Revenue
- Customer
- Product
- Payroll
- Property
- Fleet
- Vendor

---

# 5. Notable Trends and Patterns

| Trend / Pattern | Evidence | Potential Meaning | Confidence |
|---|---|---|---|
| [Trend] | [Data] | [Interpretation] | High / Moderate / Low |

Only include actual trends or meaningful patterns.

---

# 6. Underwriting Sensitivities

Rank the most important issues.

| Priority | Sensitivity | Evidence | Potential Underwriting Impact | Confirmation Needed |
|---|---|---|---|---|
| Material / Important / Informational | [Issue] | [Data] | [Impact] | [Question] |

---

# 7. Frequency vs. Severity Drivers

## Frequency Drivers

- [Exposure]
- [Exposure]

## Severity Drivers

- [Exposure]
- [Exposure]

Explain briefly where useful.

---

# 8. Data Quality Concerns

| Issue | Why It Matters | Recommended Action |
|---|---|---|
| [Issue] | [Impact] | [Action] |

Omit if no meaningful issues exist.

---

# 9. Questions Requiring Confirmation

Provide a concise list of high-value questions.

Examples:

1. [Question]
2. [Question]
3. [Question]

Focus on questions capable of changing the analysis.

---

# 10. Submission-Ready Exposure Narrative

Provide a concise paragraph suitable for inclusion in an underwriter submission.

Example structure:

> The account operates from six locations with approximately 58% of reported property value concentrated at its primary Reno facility. Payroll is distributed across Nevada and California, with the largest workers’ compensation exposure tied to field operations. Fleet exposure increased from 32 to 41 vehicles year over year, representing the most notable growth area. The principal underwriting considerations are the concentration of property values at one location and the increase in commercial auto exposure.

The narrative should summarize the data without overstating conclusions.

---

# Assumptions & Items Requiring Confirmation

Use whenever inference is involved.

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Dataset and time period are identified
- [ ] Current data is prioritized
- [ ] Data completeness was assessed
- [ ] Duplicates and inconsistencies were considered
- [ ] Material totals were reconciled where possible
- [ ] Percentages use valid denominators
- [ ] No missing values were silently fabricated
- [ ] Normalization did not change underlying meaning
- [ ] Key exposure categories are logically organized
- [ ] Geographic concentration was considered where relevant
- [ ] Operational concentration was considered where relevant
- [ ] Revenue/customer/vendor concentration was considered where data supports it
- [ ] Property, payroll, and fleet concentration were considered where relevant
- [ ] Trends are based on multiple periods
- [ ] Outliers are identified without assuming the cause
- [ ] Frequency and severity are distinguished where useful
- [ ] Underwriting sensitivities are supported by the data
- [ ] Data-quality concerns are clearly disclosed
- [ ] Assumptions are labeled
- [ ] Questions requiring confirmation are specific
- [ ] Submission-ready narrative is concise
- [ ] Final output prioritizes meaning over volume

---

# Failure Conditions

The Skill should not be considered complete if:

- The output merely reformats the data
- Material concentrations are not identified
- Percentages are calculated from unreliable totals without disclosure
- Missing values are invented
- Conflicting totals are silently reconciled
- Single-period values are described as trends
- Outliers are automatically treated as errors
- Underwriting concerns are generic rather than data-driven
- Material data-quality issues are omitted
- Assumptions are presented as facts
- No practical underwriting interpretation is provided
- The final output is difficult to scan or use in a submission

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Exposure Data

Never invent:

- Revenue
- Payroll
- Property values
- Vehicles
- Drivers
- Locations
- Employees
- Customers
- Equipment
- Inventory
- Class codes
- Business-income values
- Historical exposures

---

## Do Not Silently Modify Source Data

If data is:

- Corrected
- Normalized
- Merged
- Excluded
- Reclassified

identify the change when it could materially affect interpretation.

---

## Do Not Overstate Calculated Results

A calculation is only as reliable as the underlying data.

Use language such as:

> Based on the supplied schedule...

when completeness is not independently verified.

---

## Do Not Infer Hazard From Location Alone

A geographic concentration may be material, but specific catastrophe exposure should not be asserted without appropriate supporting data.

---

## Do Not Infer Coverage

Exposure data does not establish that insurance coverage exists.

Do not assume:

- Property is scheduled
- Vehicles are insured
- Locations are covered
- Limits are adequate
- Payroll classifications are correct

unless supported by separate coverage information.

---

## No Legal Advice

Regulatory or contractual issues may be identified as questions.

Do not provide unsupported legal conclusions.

---

## Protect Confidential Information

Use only information necessary for the analysis.

Do not unnecessarily expose:

- Personally identifiable information
- Driver personal data
- Financial account information
- Employee-sensitive information
- Confidential customer information
- Proprietary business information

Aggregate information where individual-level detail is unnecessary.

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized professional remains responsible for:

- Exposure verification
- Submission accuracy
- Client confirmation
- Underwriting communication
- Coverage recommendations
- Final calculations
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced commercial insurance analyst preparing information for a broker or underwriter.

The tone should be:

- Analytical
- Concise
- Structured
- Objective
- Insurance-specific
- Practical
- Underwriter-aware
- Non-alarmist

Avoid:

- Data dumping
- Generic commentary
- Unsupported certainty
- Excessive technical jargon
- Long unprioritized lists
- Conclusions that exceed the available data

The output should make complex exposure data easier to understand, not harder.

---

# Example

## Example Request

```text
Data:

Locations:
Reno, NV — Building $6,500,000 — BPP $2,000,000 — Business Income $3,500,000
Sparks, NV — Building $1,800,000 — BPP $900,000 — Business Income $1,200,000
Sacramento, CA — Building $1,200,000 — BPP $700,000 — Business Income $800,000

Payroll:
Nevada — $5,200,000
California — $1,800,000

Vehicles:
2025 — 41 vehicles
2024 — 32 vehicles

Revenue:
2025 — $28,000,000
2024 — $22,000,000
```

---

## Example Output Excerpt

### Executive Exposure Perspective

The account is primarily concentrated in Nevada, with the Reno facility representing the largest property and business-income exposure.

Based on the supplied property schedule, the Reno location accounts for approximately 66% of reported total insured value across the three listed locations.

Payroll is also concentrated in Nevada, representing approximately 74% of the reported payroll.

The most notable growth trend is commercial auto: vehicle count increased from 32 to 41, or approximately 28% year over year. Revenue increased approximately 27% over the same period, suggesting the fleet growth may be connected to broader business expansion.

The principal underwriting considerations are the concentration of property exposure at the Reno facility and the material increase in fleet exposure.

---

### Key Exposure Categories

| Exposure Category | Total / Scale | Primary Driver | Underwriting Relevance |
|---|---|---|---|
| Property TIV | $18.6M | Reno facility | Concentrated severity exposure |
| Payroll | $7.0M | Nevada operations | Primary workers' compensation concentration |
| Fleet | 41 vehicles | Business expansion | Increased auto frequency and severity potential |
| Revenue | $28.0M | Current operations | 27% year-over-year growth |

---

### Concentration Analysis

| Location / Region | Reported TIV | Share of Reported TIV | Why It Matters |
|---|---:|---:|---|
| Reno, NV | $12.0M | 64.5% | Largest single property and business-income concentration |
| Sparks, NV | $3.9M | 21.0% | Secondary Nevada concentration |
| Sacramento, CA | $2.7M | 14.5% | Smaller geographic diversification |

---

### Notable Trend

**Fleet Growth**

Vehicle count increased from 32 to 41 year over year.

That represents approximately 28% growth.

Because revenue also increased approximately 27%, the increase may reflect operating growth rather than a disproportionate expansion of fleet exposure, but vehicle types, drivers, and radius should be reviewed before reaching a final conclusion.

---

### Submission-Ready Exposure Narrative

The account is primarily concentrated in Nevada, with approximately two-thirds of reported property TIV located at the primary Reno facility and roughly three-quarters of payroll generated in Nevada. Revenue increased from $22 million to $28 million year over year, while fleet size increased from 32 to 41 vehicles. The growth appears broadly consistent across revenue and fleet exposure, with the primary underwriting considerations being the concentration of property values at the Reno location and the increased commercial auto exposure.

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a commercial insurance analyst responsible for preparing clean, underwriter-ready exposure summaries from raw or unstructured data.
>
> Review the information below and translate it into a structured summary that allows an underwriter or broker to quickly understand the exposure profile, identify concentrations, and assess potential risk concerns.
>
> Data:
> [PASTE SCHEDULE / EXPOSURES]
>
> Where data is incomplete or unclear, make reasonable assumptions based on typical industry patterns and clearly note those assumptions.
>
> Focus on clarity, organization, and practical insight—not just restating the data.
>
> Structure your output as:
>
> - Key exposure categories (organized logically)
> - Concentration risks (geographic, operational, revenue, or otherwise)
> - Notable trends or patterns observed in the data
> - Areas of concern or potential underwriting sensitivity
>
> The final output should be clean, concise, and presentation-ready, suitable for inclusion in a submission or internal review.

---

# Evolution From Prompt to Skill

The original prompt established the goal of transforming raw exposure data into a clean underwriting summary.

This Skill expands that prompt into a reusable Underwriting Intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Preferred source documents
- Source hierarchy
- Data Integrity Standard
- Data Normalization Standard
- Evidence classification
- Confidence classification
- Dataset readiness assessment
- Total reconciliation
- Calculation Integrity Standard
- Exposure categorization
- Geographic concentration analysis
- Operational concentration analysis
- Revenue concentration analysis
- Property concentration analysis
- Workforce concentration analysis
- Fleet concentration analysis
- Product/service concentration analysis
- Trend Analysis Standard
- Outlier detection
- Underwriting-sensitivity analysis
- Frequency/severity analysis
- Data-quality review
- Confirmation-question framework
- Materiality prioritization
- Submission-ready exposure narrative
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform an exposure-summary prompt into a reusable **Exposure Intelligence Skill**.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Prospect Intelligence Brief](../01-prospect-intelligence-brief/SKILL.md)
- [Commercial Insurance Meeting Strategy Builder](../02-meeting-strategy-builder/SKILL.md)
- [Commercial Insurance Coverage Gap Analysis](../03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Renewal Strategy Builder](../04-renewal-strategy-builder/SKILL.md)
- [Commercial Insurance Post-Meeting Follow-Up](../05-post-meeting-follow-up/SKILL.md)
- [Commercial Insurance Executive Proposal Summary](../06-executive-proposal-summary/SKILL.md)
- [Commercial Insurance Underwriter Submission Email](../07-underwriter-submission-email/SKILL.md)
- Statement of Values Analysis
- Workers' Compensation Exposure Analysis
- Fleet Exposure Analysis
- Loss Run Analysis
- Commercial Submission Preparation
- Property Concentration Analysis

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Prepare a Commercial Exposure Intelligence Summary.

Client:
[OPTIONAL]

Industry:
[OPTIONAL]

Data Period:
[OPTIONAL]

Data:
[PASTE SCHEDULE / EXPOSURES]

Prior-Year Data:
[OPTIONAL]

Known Concerns:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Data:
[PASTE SCHEDULE / EXPOSURES]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #8 include:

- Data-readiness framework
- Data Integrity Standard
- Data Normalization Standard
- Source hierarchy
- Evidence classification
- Calculation Integrity Standard
- Exposure-category framework
- Geographic concentration analysis
- Operational concentration analysis
- Revenue and customer concentration analysis
- Property and workforce concentration analysis
- Fleet concentration analysis
- Trend Analysis Standard
- Outlier detection
- Underwriting-sensitivity analysis
- Frequency/severity analysis
- Data-quality framework
- Confirmation-question framework
- Submission-ready narrative
- Quality-control standards
- Failure conditions
- Insurance-specific guardrails
- Example implementation

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Risk advisory
- Underwriting analysis
- Data interpretation
- Growth

while AI handles more of the repetitive work surrounding those responsibilities.

Apeironix is building an AI Operating Layer designed to work alongside the systems insurance agencies already use.

### Your people make the decisions. Your AI Teammates do the work.

**Keep your systems. Activate an AI Workforce.**

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
