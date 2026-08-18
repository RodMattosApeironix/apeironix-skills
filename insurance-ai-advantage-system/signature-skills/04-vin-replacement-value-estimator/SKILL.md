---
name: vin-replacement-value-estimator
title: VIN Replacement Value Intelligence
collection: insurance-ai-advantage-system-signature-skills
system: insurance-ai-advantage-system
skill_tier: signature
signature_skill_number: 4
category: commercial-pc
capability: valuation-intelligence
flywheel_stage: valuation
orchestration_role: vehicle-identity-and-valuation
primary_role: insurance-valuation-analyst
secondary_roles:
  - commercial-auto-specialist
  - claims-analyst
  - claims-advocate
  - commercial-account-manager
  - commercial-account-executive
  - risk-advisor
template_version: 2.2
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# VIN Replacement Value Intelligence

## Signature Skill

**Insurance AI Advantage System — Signature Skill #4**

This is a fully engineered Apeironix Signature Skill designed to operate as part of the Insurance AI Advantage System.

Unlike a simple VIN-decoding prompt, this Skill combines:

- VIN validation
- Vehicle identity decoding
- Evidence classification
- Configuration uncertainty analysis
- Scenario-based valuation
- Replacement-value estimation
- Confidence scoring
- Assumption transparency
- Data-gap prioritization
- Commercial upfit detection
- Claims / underwriting usability
- Human review
- Downstream valuation handoff

The objective is not simply to decode a VIN.

The objective is to create a **defensible, auditable, transparent vehicle-value estimate** that clearly distinguishes:

- What is confirmed
- What is inferred
- What remains unknown
- How uncertainty affects value
- What data is needed to tighten the estimate

---

# Purpose

Analyze a VIN and produce a transparent insurance-oriented estimate of vehicle replacement value while clearly separating confirmed vehicle identity from inferred configuration and unknown valuation variables.

This Skill is designed to help the insurance professional:

- Validate VIN structure
- Decode confirmed vehicle attributes
- Avoid inventing trim or option details
- Identify when a VIN does not fully determine configuration
- Create plausible configuration scenarios
- Estimate a replacement-value range
- Widen the range when material inputs are missing
- Explain what drives valuation uncertainty
- Provide an explicit confidence score
- Identify red flags
- Identify commercial upfit or body-equipment risk
- Identify salvage / title-history risk
- Produce a valuation estimate suitable for claims triage, underwriting support, schedule validation, or stated-value review

The objective is **not** to produce a falsely precise market value from VIN alone.

The objective is to answer:

> What can we prove from the VIN, what must we infer, what range is defensible today, and what additional information would materially improve the estimate?

---

# Core Outcome

A successful execution should allow the user to understand:

1. Whether the VIN appears valid
2. What vehicle identity is confirmed by the VIN
3. Which vehicle attributes remain uncertain
4. What plausible configurations exist
5. How those configurations affect value
6. What valuation range is reasonable based on current information
7. What type of estimate is being provided
8. How confident the estimate is
9. Which assumptions materially affect the range
10. What five additional data points would most improve accuracy
11. Whether any red flags could materially alter value

The finished output should be usable by an insurance professional without implying a level of precision the evidence does not support.

---

# Role in the Insurance AI Advantage System

This Signature Skill operates primarily within the **Valuation Intelligence** stage of the Insurance AI Advantage System.

## Upstream Inputs May Include

- VIN
- Vehicle schedule
- Policy schedule
- Claim intake
- Appraisal request
- Commercial auto schedule
- Fleet record
- Inspection photos
- Registration
- Equipment list
- Title data
- Maintenance record

## Primary Function

Convert VIN-based identity plus available supporting data into a transparent value range with explicit uncertainty controls.

## Downstream Workflows May Include

- Claims Triage
- Total-Loss Review
- Vehicle Schedule Validation
- Stated-Value Review
- Underwriting Submission
- Policy Limit Review
- Commercial Auto Exposure Analysis
- Fleet Valuation
- Property / Inland Marine Review
- Client Advisory
- Appraisal Escalation

The Skill should therefore output both human-readable and structured valuation intelligence.

---

# Best Used For

Use this Skill for:

- Commercial auto valuation
- Claims intake valuation
- Total-loss triage
- Replacement-cost support
- Vehicle schedule validation
- Stated-value support
- Fleet valuation review
- Underwriting preparation
- Commercial truck review
- Van / service vehicle review
- Light-duty truck review
- Medium-duty truck review
- Chassis-cab review
- Specialty body review
- Equipment valuation triage
- Schedule cleanup
- Client advisory

It is especially useful when the available starting point is only:

> VIN

and the user needs a defensible preliminary range rather than a fabricated exact answer.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Formal appraisal
- Certified vehicle valuation
- Carrier total-loss determination
- Adjuster authority
- Auction valuation
- Salvage valuation
- Title-history service
- Mechanical inspection
- Dealer inspection
- Legal valuation opinion
- Tax appraisal
- Manufacturer build sheet unless actually obtained
- Final claims settlement determination

This is a **vehicle identity and valuation intelligence Skill**.

---

# Intended Users

Primary users:

- Insurance Valuation Analysts
- Commercial Auto Specialists
- Claims Analysts

Secondary users:

- Claims Advocates
- Commercial Account Managers
- Commercial Account Executives
- Risk Advisors
- Underwriters
- Fleet Specialists
- Agency Operations Teams

---

# Required Inputs

At minimum:

```text
Input VIN:
[ENTER VIN HERE]
```

A VIN-only analysis is permitted.

However, the Skill must widen the valuation range when critical valuation inputs are unavailable.

---

# Recommended Inputs

Where available, provide:

```text
VIN:
[INSERT]

Mileage:
[INSERT]

Condition:
[INSERT]

ZIP / Market Area:
[INSERT]

Body Type:
[INSERT]

Installed Equipment:
[INSERT]

Commercial Upfit:
[INSERT]

Cab Configuration:
[INSERT]

Bed Length:
[INSERT]

Wheelbase:
[INSERT]

Drive Type:
[INSERT]

Tire Condition:
[INSERT]

Mechanical Condition:
[INSERT]

Title Status:
[INSERT]

Accident History:
[INSERT]

Maintenance History:
[INSERT]

Photos:
[INSERT]

Registration:
[INSERT]

Build Sheet:
[INSERT]

Prior Appraisal:
[INSERT]
```

For commercial vehicles, installed body and equipment data may be more important than trim.

---

# Optional Intelligence Sources

Where authorized and current:

- Manufacturer VIN decoder
- NHTSA VIN data
- Manufacturer build data
- Dealer inventory
- Used vehicle listings
- Commercial truck listings
- Market valuation databases
- Auction results
- Fleet management system
- Registration data
- Title-history data
- Dealer quotes
- Commercial upfit manufacturer data
- Equipment manufacturer data
- Claims valuation data

Current market valuation should use current market evidence where available.

Historical market pricing should not be presented as current without disclosure.

---

# Preferred Source Hierarchy

Prioritize:

1. VIN-confirmed manufacturer / authoritative decode
2. Manufacturer build sheet
3. Registration / title data
4. Inspection / photos
5. Current market listings
6. Dealer information
7. Current commercial vehicle marketplace data
8. Client-confirmed configuration
9. Historical valuation data
10. Professional inference

Do not let marketplace listings override confirmed vehicle identity.

---

# Market Currency Standard

Vehicle valuation is time-sensitive.

Current value estimates should use recent market evidence where available.

Consider:

- Current retail listings
- Current regional availability
- Current commercial truck market
- Current used vehicle demand
- Current model scarcity
- Current equipment scarcity
- Current regional pricing

Do not present stale valuation data as current.

If current market evidence is unavailable:

- State the limitation
- Lower confidence
- Widen the range
- Recommend validation with current listings or appraisal

---

# VIN Validation Standard

Before decoding, determine whether the VIN appears structurally valid.

Check:

- Character count
- Allowed characters
- Obvious invalid characters
- VIN format consistency
- Model-year compatibility where possible

Classify:

### Valid Format

The VIN appears structurally valid.

### Questionable Format

The VIN may contain a transcription error.

### Invalid Format

The VIN does not meet expected VIN structure.

Do not decode an invalid VIN as if it were valid.

---

# Evidence Classification Standard

Every material vehicle attribute must be labeled as one of:

## [CONFIRMED_FROM_VIN]

Directly supported by VIN decoding.

## [LIKELY_INFERRED]

Reasonable inference based on decoded vehicle family, common configurations, or market evidence.

## [UNKNOWN_REQUIRES_INSPECTION]

Cannot be reliably determined from the VIN or available evidence.

These labels are mandatory.

Do not present inferred trim, equipment, or configuration as VIN-confirmed.

---

# Core Principle

## Defensible Range Over False Precision

VIN-based valuation should be transparent about uncertainty.

A useful estimate is:

- Traceable
- Scenario-based
- Current
- Range-oriented
- Confidence-scored
- Assumption-aware

A precise but unsupported number is worse than a wider defensible range.

---

# VIN Decode Boundary Standard

The VIN may support:

- Year
- Make
- Model
- Vehicle type
- Body class
- Engine family
- Fuel type
- GVWR class
- Plant
- Certain drivetrain or series attributes

The VIN may **not** reliably reveal:

- Exact installed options
- Exact trim package
- Aftermarket equipment
- Commercial body
- Service body
- Liftgate
- Crane
- Refrigeration
- Shelving
- Tool package
- Maintenance condition
- Current mileage
- Accident history
- Tire condition
- Title status
- Region-specific market value

Do not infer these as facts.

---

# Configuration Uncertainty Standard

If VIN decoding does not uniquely identify the configuration, create plausible scenarios.

Example:

### Scenario 1

Base chassis / standard equipment

### Scenario 2

Higher trim / factory equipment

### Scenario 3

Commercial upfit / specialty body

For each scenario, identify:

- Configuration
- Why plausible
- Estimated value effect
- Confidence

Do not create scenarios that are inconsistent with the decoded VIN.

---

# Commercial Upfit Standard

Commercial vehicles may derive substantial value from installed body or equipment.

Potential examples:

- Service body
- Utility body
- Flatbed
- Dump body
- Box body
- Refrigerated body
- Crane
- Liftgate
- Compressor
- Generator
- Shelving
- Ladder rack
- Contractor package
- PTO equipment
- Specialized hydraulic equipment

VIN alone often does not establish these.

If commercial upfit is possible and unknown:

- Flag it prominently
- Widen the value range
- Identify inspection / photos as high-priority data
- Avoid valuing only the chassis as the complete vehicle

---

# Valuation Basis Standard

Identify the estimate type explicitly.

Allowed estimate types include:

### Retail Replacement

Approximate cost to purchase a comparable replacement vehicle in the current market.

### ACV Support

Preliminary support for actual-cash-value analysis, subject to mileage, condition, market, and history.

### Stated Value Support

Preliminary support for evaluating whether a stated amount appears plausible.

### Claims Triage Estimate

Fast preliminary range intended for early claim handling, not final settlement.

Do not mix estimate types without explanation.

---

# Replacement Value Standard

Replacement value should consider, where available:

- Year
- Make
- Model
- Configuration
- Mileage
- Condition
- Region
- Drivetrain
- Body
- Equipment
- Upfit
- Mechanical condition
- Title history
- Comparable current listings

VIN-only value should be treated as preliminary.

---

# Range Construction Standard

The valuation range should widen when important inputs are missing.

Examples:

### Narrower Range

VIN + mileage + condition + body + region + market comps

### Moderate Range

VIN + mileage + region, but uncertain options

### Wide Range

VIN only

### Very Wide Range

VIN suggests commercial chassis or specialty body but upfit is unknown

The Skill should explain why the range has the width shown.

---

# Confidence Scoring Standard

Provide a confidence score from:

`0–100`

Suggested interpretation:

### 90–100 — Very High

Vehicle configuration and current market evidence are strongly established.

### 75–89 — High

Most material inputs are known; limited uncertainty remains.

### 55–74 — Moderate

Useful estimate, but one or more material valuation variables remain unknown.

### 35–54 — Low

Substantial configuration, condition, or market uncertainty exists.

### 0–34 — Very Low

Insufficient information for more than a broad preliminary estimate.

The score must be explained.

Do not use confidence scoring as false mathematical precision.

---

# Confidence Driver Standard

Confidence should reflect:

- VIN decode completeness
- Configuration certainty
- Mileage certainty
- Condition certainty
- Market-region certainty
- Upfit certainty
- Title-history certainty
- Comparable quality
- Market recency

A perfect VIN decode does not equal a high-confidence valuation if mileage and condition remain unknown.

---

# Assumption Standard

All material assumptions must be explicit.

Required categories:

- Mileage assumption
- Condition assumption
- Geographic market assumption
- Equipment / body assumption
- Title / history assumption
- Tire / mechanical assumption for trucks / commercial vehicles
- Other assumptions

Do not hide assumptions inside the value estimate.

---

# Scenario Valuation Standard

Where configuration materially affects value, estimate:

```text
Base Vehicle Value
+
Configuration Adjustment
+
Equipment / Upfit Adjustment
+
Regional Adjustment
+
Condition / Mileage Adjustment
=
Scenario Value Range
```

Do not fabricate precise adjustments when market evidence is weak.

Use directional language where appropriate:

- modest positive impact
- material positive impact
- material negative impact
- unable to quantify without inspection

---

# Data Integrity Standard

Review for:

- VIN transcription errors
- Impossible model-year relationships
- Conflicting make / model information
- Duplicate vehicle records
- Incorrect body description
- Incorrect GVWR
- Conflicting mileage
- Conflicting title status
- Market listings for materially different configurations

Do not silently resolve material inconsistencies.

---

# Like-for-Like Comparable Standard

Comparable vehicles should match as closely as practical on:

- Year
- Make
- Model
- Body
- Drivetrain
- Cab
- GVWR
- Engine
- Mileage
- Condition
- Commercial equipment
- Region

Do not compare:

- bare chassis
- finished service body
- box truck
- pickup

as though they are equivalent simply because VIN family is similar.

---

# Market Comparable Quality Standard

Classify comparables when used:

### Strong Comparable

Very similar configuration and market.

### Moderate Comparable

Minor differences requiring adjustment.

### Weak Comparable

Material configuration difference.

### Non-Comparable

Should not materially influence valuation.

Avoid averaging unrelated listings.

---

# Calculation Integrity Standard

If deriving a midpoint:

```text
Mid = (Low + High) / 2
```

If using scenario weighting, disclose the method.

Do not create a weighted value unless scenario probabilities are reasonably supportable.

Do not use excessive precision.

Preferred:

> $38,000–$46,000

not:

> $42,173.82

---

# Workflow State Standard

Relevant states may include:

1. VIN Received
2. VIN Validated
3. Identity Decoded
4. Configuration Uncertainty Assessed
5. Market Evidence Gathered
6. Scenarios Built
7. Preliminary Range Developed
8. Confidence Scored
9. Additional Data Requested
10. Revised Valuation
11. Human Review
12. Finalized for Intended Use

Do not confuse:

> Preliminary range developed

with:

> Final appraisal complete.

---

# Workflow

## Step 1 — Validate the VIN

Determine:

- Format
- Length
- obvious transcription problems
- whether decoding can proceed

If invalid:

- stop exact decoding
- identify likely issue
- request corrected VIN

---

## Step 2 — Decode Confirmed Identity

Capture all reliably decodable attributes.

Every attribute must carry:

`[CONFIRMED_FROM_VIN]`

if actually VIN-supported.

---

## Step 3 — Identify Non-Decodable Attributes

Mark as:

`[UNKNOWN_REQUIRES_INSPECTION]`

Examples:

- Mileage
- Condition
- Upfit
- aftermarket equipment
- trim ambiguity
- tire condition
- mechanical condition
- title history

---

## Step 4 — Identify Likely Inferences

Where useful, identify plausible information as:

`[LIKELY_INFERRED]`

Explain why.

Do not let likely become confirmed.

---

## Step 5 — Determine Whether Scenarios Are Required

Scenarios are useful when:

- trim remains ambiguous
- cab / bed configuration remains uncertain
- commercial body may be installed
- specialty equipment may exist
- VIN identifies chassis but not body

If no meaningful configuration uncertainty exists, omit scenarios.

---

## Step 6 — Build Configuration Scenarios

For each scenario:

- likely configuration
- evidence
- plausibility
- value effect

Avoid more than needed.

Usually 2–3 scenarios are sufficient.

---

## Step 7 — Establish Valuation Type

Choose:

- Retail Replacement
- ACV Support
- Stated Value Support
- Claims Triage Estimate

State why.

---

## Step 8 — Identify Missing Valuation Drivers

At minimum consider:

- Mileage
- Condition
- Region
- Body
- Upfit
- Mechanical condition
- Title history

Rank by materiality.

---

## Step 9 — Develop Preliminary Range

Use current evidence where available.

If VIN-only:

- widen the range
- explain the uncertainty
- avoid false precision

---

## Step 10 — Assign Confidence Score

Score 0–100.

Explain the primary factors that raise or lower confidence.

---

## Step 11 — Identify Top Five Data Requests

Prioritize only the most value-sensitive items.

Examples:

1. Current mileage
2. Four-corner photos
3. Body / equipment details
4. ZIP code
5. Title-history confirmation

Do not request everything equally.

---

## Step 12 — Identify Red Flags

Potential flags:

- Invalid VIN
- Commercial chassis
- Specialty body
- Salvage / rebuilt history
- Upfit uncertainty
- Configuration mismatch
- Grey-market vehicle
- Non-standard conversion
- Missing title information
- Market scarcity
- Mechanical uncertainty

---

# Red Flag Severity Standard

Classify red flags when useful:

### Critical

Could invalidate the identity or valuation basis.

### High

Could materially alter value.

### Moderate

Important but unlikely to change the entire range.

### Informational

Worth noting but not presently material.

---

# Decision Conversion Standard

This Signature Skill should convert uncertainty into a decision structure.

For each material uncertainty, identify:

1. Decision / action required
2. Owner
3. Evidence needed
4. Current estimate impact
5. Whether valuation can proceed
6. What downstream workflow follows

Example:

| Issue | Owner | Evidence Needed | Current Impact | Can Proceed? | Next Workflow |
|---|---|---|---|---|---|
| Unknown service body | Client / Adjuster | Photos + equipment list | Could add substantial value | Preliminary only | Revised valuation |

---

# Ownership Standard

Potential owners include:

- Client
- Account Manager
- Claims Advocate
- Adjuster
- Underwriter
- Valuation Analyst
- Fleet Manager
- Appraiser

Example:

| Action | Owner |
|---|---|
| Confirm mileage | Client / Fleet Manager |
| Obtain photos | Account Manager / Adjuster |
| Confirm title | Claims / Client |
| Re-run valuation | Valuation Analyst |

---

# Handoff Integrity Standard

When the estimate is handed to claims, underwriting, or account management, include:

- VIN
- confirmed identity
- estimate type
- low / mid / high
- confidence score
- major assumptions
- unresolved configuration issues
- top data requests
- red flags
- source date

Recommended handoff:

```text
VIN:
[VIN]

Estimate Type:
[TYPE]

Current Range:
[LOW]–[HIGH]

Confidence:
[SCORE]

Critical Unknowns:
[LIST]

Next Required Evidence:
[LIST]

Status:
Preliminary / Revised / Final for Intended Use
```

---

# System-of-Record Standard

Where vehicle data spans systems:

| Data | System of Record |
|---|---|
| VIN | AMS / Fleet System |
| Policy schedule | AMS |
| Vehicle configuration | Fleet / Inspection Record |
| Claim valuation | Claims System |
| Final appraisal | Appraisal / Claims File |
| Valuation notes | Claims / CRM / Valuation Record |

Do not let a preliminary AI estimate overwrite a carrier or certified appraisal.

---

# Transaction Lineage / Audit Trail Standard

Preserve:

```text
VIN
    ↓
VIN Decode
    ↓
Confirmed Identity
    ↓
Configuration Scenario
    ↓
Market Evidence
    ↓
Value Range
    ↓
Confidence Score
    ↓
Additional Evidence
    ↓
Revised Value
```

A revised value should not erase:

- prior assumptions
- prior range
- reason for revision
- new evidence

---

# Dynamic Reassessment / Monitoring Trigger Standard

Reassess value when:

- Mileage is confirmed
- Photos are received
- Upfit is identified
- Title history is discovered
- Mechanical condition changes
- Geographic market changes
- New comparable data appears
- Inspection contradicts assumed configuration
- Salvage / rebuilt history is found
- Appraiser provides new evidence

---

# Stop Rules

Stop and escalate when:

- VIN is invalid
- Vehicle identity conflicts materially
- Commercial body cannot be determined and dominates value
- Title status is uncertain and could materially affect value
- Condition uncertainty makes the range excessively broad
- Specialty equipment appears present but is undocumented
- Formal appraisal is required for the intended use
- The user requests final settlement value without adequate evidence

Do not solve missing valuation evidence by guessing.

---

# Completion Criteria Standard

VIN valuation analysis is complete for a **preliminary estimate** when:

1. VIN is validated
2. Confirmed identity is decoded
3. Unknown attributes are labeled
4. Inferences are labeled
5. Scenarios are created where necessary
6. Estimate type is stated
7. Low / mid / high range is provided
8. Confidence score is provided
9. Assumptions are listed
10. Top five data needs are identified
11. Red flags are identified
12. Human review is identified where required

A **finalized valuation for a specific insurance use** may additionally require:

13. Mileage confirmation
14. Condition confirmation
15. Region confirmation
16. Upfit / equipment confirmation
17. Title-history confirmation
18. Current market comparables
19. Human approval or appraisal where appropriate

---

# Human Review Escalation Standard

Require elevated human review when:

- Vehicle is commercial or specialty
- Value is unusually high
- Upfit may represent material value
- Salvage / rebuilt history exists
- Vehicle identity conflicts
- Total-loss claim is involved
- Coverage amount may materially depend on value
- Stated-value decision is being made
- Final claims settlement is being considered
- Appraisal dispute exists

AI may support valuation.

Authorized claims, underwriting, appraisal, or insurance professionals remain responsible for final decisions.

---

# Internal vs. External Information Boundary Standard

Internal analysis may include:

- confidence limitations
- valuation methodology
- weak comparable notes
- audit trail
- internal uncertainty
- appraisal escalation recommendation

Client-facing output should explain uncertainty clearly without exposing irrelevant internal process commentary.

---

# Decision Rules

## VIN Facts Are Not Configuration Facts

Do not invent trim or equipment.

---

## Value Range Over Exact Number

Unless evidence supports precision.

---

## Commercial Upfit Can Dominate Value

Do not ignore body and equipment.

---

## Missing Mileage Widens the Range

Mileage materially affects value.

---

## Missing Condition Widens the Range

Condition materially affects value.

---

## Missing Region Widens the Range

Local markets differ.

---

## Title History Matters

Salvage / rebuilt status can materially affect value.

---

## Comparables Must Be Like-for-Like

Do not average incompatible vehicles.

---

## Confidence Must Match Evidence

A polished answer does not justify a high score.

---

# Materiality / Prioritization Framework

Prioritize valuation uncertainty using:

| Factor | Question |
|---|---|
| Identity | Is the vehicle definitively identified? |
| Configuration | Could body / trim materially change value? |
| Mileage | Is current usage known? |
| Condition | Is physical / mechanical condition known? |
| Upfit | Could installed equipment be valuable? |
| Region | Is the market area known? |
| History | Could salvage / rebuilt status affect value? |
| Comparables | Are strong current market comps available? |
| Intended Use | Is this triage or final settlement support? |

---

# Output Requirements

Use this exact structure.

# VIN Replacement Value Intelligence

## A. VIN Validation

**VIN Provided:**  
[VIN]

**VIN Valid Format:**  
Yes / No

**Validation Notes:**  
[Notes]

---

## B. Decoded Identity (Confirmed)

Every line must include one of the required evidence labels.

**Year:**  
[VALUE] [CONFIRMED_FROM_VIN]

**Make:**  
[VALUE] [CONFIRMED_FROM_VIN]

**Model:**  
[VALUE] [CONFIRMED_FROM_VIN]

**Series / Trim:**  
[VALUE / UNKNOWN] [CONFIRMED_FROM_VIN / LIKELY_INFERRED / UNKNOWN_REQUIRES_INSPECTION]

**Body Class:**  
[VALUE] [LABEL]

**Vehicle Type:**  
[VALUE] [LABEL]

**Engine:**  
[VALUE] [LABEL]

**Fuel:**  
[VALUE] [LABEL]

**Drivetrain:**  
[VALUE] [LABEL]

**Transmission:**  
[VALUE] [LABEL]

**GVWR Class:**  
[VALUE] [LABEL]

**Plant:**  
[VALUE] [LABEL]

**Other Decodable Attributes:**  
- [ATTRIBUTE] [LABEL]
- [ATTRIBUTE] [LABEL]

Do not fill unsupported fields.

---

## C. Configuration Scenarios

Include only when needed.

### Scenario 1

**Likely Configuration:**  
[CONFIGURATION]

**Classification:**  
[LIKELY_INFERRED]

**Why It Is Plausible:**  
[REASON]

**Estimated Value Impact:**  
[+/- IMPACT OR DIRECTIONAL IMPACT]

---

### Scenario 2

**Likely Configuration:**  
[CONFIGURATION]

**Classification:**  
[LIKELY_INFERRED]

**Why It Is Plausible:**  
[REASON]

**Estimated Value Impact:**  
[+/- IMPACT]

---

### Scenario 3

Use only if genuinely necessary.

---

## D. Replacement Value Estimate

**Low:**  
[$]

**Mid:**  
[$]

**High:**  
[$]

**Estimate Type:**  
Retail Replacement / ACV / Stated Value Support / Claims Triage Estimate

**Confidence Score:**  
[0–100]

**Confidence Rationale:**  
[Explain what is known, what is missing, and why the range has the width shown.]

---

## E. Assumptions Used

**Mileage Assumption:**  
[ASSUMPTION] [LIKELY_INFERRED / UNKNOWN_REQUIRES_INSPECTION]

**Condition Assumption:**  
[ASSUMPTION] [LIKELY_INFERRED / UNKNOWN_REQUIRES_INSPECTION]

**Geographic Market Assumption:**  
[ASSUMPTION] [LIKELY_INFERRED / UNKNOWN_REQUIRES_INSPECTION]

**Equipment / Body Assumption:**  
[ASSUMPTION] [LIKELY_INFERRED / UNKNOWN_REQUIRES_INSPECTION]

**Title / History Assumption:**  
[ASSUMPTION] [LIKELY_INFERRED / UNKNOWN_REQUIRES_INSPECTION]

**Tire / Mechanical Assumption:**  
[ASSUMPTION] [LIKELY_INFERRED / UNKNOWN_REQUIRES_INSPECTION]

**Other Assumptions:**  
- [ASSUMPTION] [LABEL]

---

## F. What We Need To Tighten the Value — Top 5

1. [DATA ITEM] — [WHY IT MATTERS]
2. [DATA ITEM] — [WHY IT MATTERS]
3. [DATA ITEM] — [WHY IT MATTERS]
4. [DATA ITEM] — [WHY IT MATTERS]
5. [DATA ITEM] — [WHY IT MATTERS]

Rank by likely valuation impact.

---

## G. Red Flags / Special Notes

### Invalid VIN Risk

[None / Issue]

### Commercial Upfit Risk

[None / Issue]

### Salvage / Rebuilt Risk

[Unknown / Confirmed / None Known]

### Specialty Body / Chassis Mismatch Risk

[None / Issue]

### Other Material Notes

- [NOTE]
- [NOTE]

---

# Optional Internal Valuation Notes

This section is internal unless specifically requested.

## Confidence Drivers

### Positive

- [Factor]

### Negative

- [Factor]

## Scenario Sensitivity

| Variable | Current Assumption | Potential Effect |
|---|---|---|
| Mileage | [ ] | [ ] |
| Condition | [ ] | [ ] |
| Upfit | [ ] | [ ] |
| Region | [ ] | [ ] |

---

# Machine-Readable Valuation Intelligence

When requested, also output:

```text
vin
vin_valid
year
make
model
series
trim
body_class
vehicle_type
engine
fuel
drivetrain
transmission
gvwr_class
plant
confirmed_attributes
inferred_attributes
unknown_attributes
scenario_1
scenario_2
scenario_3
estimate_low
estimate_mid
estimate_high
estimate_type
confidence_score
mileage_assumption
condition_assumption
region_assumption
equipment_assumption
title_assumption
mechanical_assumption
top_data_need_1
top_data_need_2
top_data_need_3
top_data_need_4
top_data_need_5
commercial_upfit_risk
salvage_risk
specialty_body_risk
human_review_required
```

Do not populate unsupported attributes as facts.

---

# Quality Checks

Before finalizing, verify:

- [ ] VIN is validated
- [ ] Invalid VIN is not decoded as valid
- [ ] Confirmed attributes are genuinely VIN-supported
- [ ] Inferred attributes are labeled
- [ ] Unknown attributes are labeled
- [ ] Exact trim is not fabricated
- [ ] Exact options are not fabricated
- [ ] Commercial upfit risk is considered
- [ ] Mileage uncertainty is considered
- [ ] Condition uncertainty is considered
- [ ] Region uncertainty is considered
- [ ] Title-history uncertainty is considered
- [ ] Configuration scenarios are plausible
- [ ] Range width reflects uncertainty
- [ ] Estimate type is explicit
- [ ] Confidence score matches evidence quality
- [ ] Confidence rationale is provided
- [ ] Assumptions are explicit
- [ ] Top five data requests are prioritized
- [ ] Red flags are identified
- [ ] Market comparables are like-for-like where used
- [ ] No false precision is used
- [ ] Final valuation is not implied where only preliminary evidence exists
- [ ] Human review occurs where required

---

# Failure Conditions

The Skill should not be considered complete if:

- Exact trim is fabricated
- Installed options are guessed
- Commercial upfit is ignored
- Mileage is assumed without disclosure
- Condition is assumed without disclosure
- Region is assumed without disclosure
- Salvage status is assumed without disclosure
- Chassis-only value is presented as full commercial vehicle value where an upfit may exist
- Weak comparables are treated as strong
- One exact number is presented despite major uncertainty
- Confidence score is unexplained
- Red flags are omitted
- Additional data requests are not prioritized
- Preliminary estimate is presented as final appraisal
- Source facts and inferences are mixed

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Fabricate Vehicle Configuration

Never invent:

- Trim
- Options
- Commercial body
- Equipment
- Mileage
- Condition
- Title history
- Mechanical condition
- Accident history

---

## Label Every Material Attribute

Use only:

- [CONFIRMED_FROM_VIN]
- [LIKELY_INFERRED]
- [UNKNOWN_REQUIRES_INSPECTION]

---

## Do Not Overstate VIN Capability

VIN decoding may not reveal complete configuration.

---

## Do Not Ignore Commercial Equipment

For commercial vehicles, installed equipment may materially exceed trim-value differences.

---

## Do Not Create False Precision

Prefer defensible ranges.

---

## Do Not Treat Retail Replacement as ACV

State the estimate type.

---

## Do Not Treat Preliminary Estimate as Settlement Authority

Claims professionals remain responsible.

---

## Preserve Auditability

Maintain source, assumptions, scenarios, and revision history.

---

## Protect Confidential Information

Do not unnecessarily expose:

- Owner information
- registration details
- claim-sensitive data
- account identifiers
- personal information

---

## Preserve Human Accountability

This Skill supports insurance valuation work.

The authorized adjuster, claims professional, underwriter, appraiser, account professional, or other appropriate authority remains responsible for:

- Final value
- ACV determination
- Stated-value selection
- Total-loss decision
- Settlement
- Appraisal
- Policy valuation
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced insurance valuation analyst.

The tone should be:

- Defensible
- Transparent
- Auditable
- Precise
- Practical
- Insurance-friendly
- Non-speculative

Avoid:

- False certainty
- VIN-decoder overclaiming
- unsupported trim claims
- marketing language
- excessive jargon
- opaque calculations
- unjustified exact values

If uncertainty is high, say so directly.

---

# Example

## Example Input

```text
Input VIN:
1FT8W3BT6PEC12345
```

---

## Example Output

# VIN Replacement Value Intelligence

## A. VIN Validation

**VIN Provided:**  
1FT8W3BT6PEC12345

**VIN Valid Format:**  
Yes

**Validation Notes:**  
The VIN appears to follow the expected 17-character format. Final decode should be confirmed through an authoritative VIN source.

---

## B. Decoded Identity (Confirmed)

**Year:**  
2023 [CONFIRMED_FROM_VIN]

**Make:**  
Ford [CONFIRMED_FROM_VIN]

**Model:**  
F-Series Super Duty [CONFIRMED_FROM_VIN]

**Series / Trim:**  
Exact retail trim not established from the available decode [UNKNOWN_REQUIRES_INSPECTION]

**Body Class:**  
Pickup / truck configuration [CONFIRMED_FROM_VIN]

**Vehicle Type:**  
Truck [CONFIRMED_FROM_VIN]

**Engine:**  
Diesel engine family indicated [CONFIRMED_FROM_VIN]

**Fuel:**  
Diesel [CONFIRMED_FROM_VIN]

**Drivetrain:**  
Requires authoritative decode confirmation [UNKNOWN_REQUIRES_INSPECTION]

**Transmission:**  
Specific installed transmission not confirmed [UNKNOWN_REQUIRES_INSPECTION]

**GVWR Class:**  
Heavy light-duty / Super Duty classification indicated [CONFIRMED_FROM_VIN]

**Plant:**  
Plant information should be confirmed through authoritative decode [UNKNOWN_REQUIRES_INSPECTION]

---

## C. Configuration Scenarios

### Scenario 1

**Likely Configuration:**  
Standard Super Duty crew-cab pickup without specialty commercial equipment

**Classification:**  
[LIKELY_INFERRED]

**Why It Is Plausible:**  
The VIN family is consistent with a Ford Super Duty truck, but trim and installed equipment are not fully established.

**Estimated Value Impact:**  
Baseline valuation scenario.

---

### Scenario 2

**Likely Configuration:**  
Higher-trim Super Duty pickup with factory comfort / technology options

**Classification:**  
[LIKELY_INFERRED]

**Why It Is Plausible:**  
Multiple trim levels may share similar VIN-level identity.

**Estimated Value Impact:**  
Could materially increase replacement value relative to base configuration.

---

### Scenario 3

**Likely Configuration:**  
Commercially equipped truck with rack, tool storage, service equipment, or other aftermarket upfit

**Classification:**  
[LIKELY_INFERRED]

**Why It Is Plausible:**  
Commercially insured Super Duty trucks are frequently modified after manufacture, and those items are not reliably established by VIN alone.

**Estimated Value Impact:**  
Could materially increase replacement value depending on installed equipment.

---

## D. Replacement Value Estimate

**Low:**  
Preliminary range cannot be responsibly narrowed without current market data.

**Mid:**  
Requires current comparable-market review.

**High:**  
Could be materially higher if specialty equipment or higher trim is present.

**Estimate Type:**  
Retail Replacement

**Confidence Score:**  
40 / 100

**Confidence Rationale:**  
The VIN provides useful vehicle identity but does not establish several major valuation drivers, including exact trim, mileage, condition, geographic market, title history, and aftermarket commercial equipment. The value range should therefore remain broad until those items are confirmed.

---

## E. Assumptions Used

**Mileage Assumption:**  
No mileage supplied. [UNKNOWN_REQUIRES_INSPECTION]

**Condition Assumption:**  
Average used condition assumed only for preliminary framing. [LIKELY_INFERRED]

**Geographic Market Assumption:**  
No market region supplied. [UNKNOWN_REQUIRES_INSPECTION]

**Equipment / Body Assumption:**  
No specialty commercial equipment confirmed. [UNKNOWN_REQUIRES_INSPECTION]

**Title / History Assumption:**  
Clean-title history cannot be confirmed from VIN alone. [UNKNOWN_REQUIRES_INSPECTION]

**Tire / Mechanical Assumption:**  
Normal operating condition cannot be confirmed. [UNKNOWN_REQUIRES_INSPECTION]

---

## F. What We Need To Tighten the Value — Top 5

1. **Current mileage** — one of the largest drivers of used truck value.
2. **Four-corner and interior photos** — needed to establish physical condition and visible configuration.
3. **Exact trim / build sheet** — materially affects comparable selection.
4. **Commercial equipment / upfit list** — may materially increase replacement value.
5. **ZIP code / market area** — needed for current regional replacement pricing.

---

## G. Red Flags / Special Notes

### Invalid VIN Risk

No obvious format issue identified.

### Commercial Upfit Risk

High. A commercial Super Duty may carry significant aftermarket body or equipment value that VIN alone will not reveal.

### Salvage / Rebuilt Risk

Unknown. Requires title-history confirmation.

### Specialty Body / Chassis Mismatch Risk

Moderate. Physical inspection should confirm that the vehicle body matches the assumed pickup configuration.

### Other Material Notes

The current analysis should be treated as preliminary until current mileage, condition, exact configuration, and market evidence are available.

---

# Original Signature Prompt

The original Insurance AI Advantage System Signature Prompt that inspired this Skill:

> Your job is to analyze a VIN and produce a defensible replacement value estimate with full transparency.
>
> Mission
> From VIN-only input, generate:
>
> decoded vehicle identity/specs,
> inferred configuration scenarios (if needed),
> a replacement value range,
> confidence scoring,
> and a clear list of additional data needed to finalize value.
>
> Input VIN > [enter vin here]
>
> Non-Negotiable Behavior
>
> DO NOT fabricate exact trim/options not decodable from VIN.
> Label every item as one of:
> [CONFIRMED_FROM_VIN]
> [LIKELY_INFERRED]
> [UNKNOWN_REQUIRES_INSPECTION]
> If key valuation inputs are missing (mileage, condition, body equipment, region), widen the value range and explain.
> Use insurance-friendly language (defensible, auditable, transparent).
> If uncertainty is high, say so directly.
>
> Output Schema (use this exact structure)
> A. VIN Validation
>
> VIN Provided:
> VIN Valid Format: Yes/No
> Validation Notes:
>
> B. Decoded Identity (Confirmed)
>
> Year
> Make
> Model
> Series/Trim
> Body Class
> Vehicle Type
> Engine
> Fuel
> Drivetrain
> Transmission
> GVWR Class
> Plant
> Any other decodable attributes
>
> C. Configuration Scenarios (if VIN is not enough)
> List Scenario 1, 2, 3 (if applicable), each with:
>
> likely config
> why it is plausible
> value impact (+/-)
>
> D. Replacement Value Estimate
>
> Low:
> Mid:
> High:
> Estimate Type: (Retail Replacement / ACV / Stated Value Support / Claims Triage Estimate)
> Confidence Score: 0-100
> Confidence Rationale:
>
> E. Assumptions Used
>
> Mileage assumption:
> Condition assumption:
> Geographic market assumption:
> Equipment/body assumption:
> Title/history assumption:
> Tire/mechanical assumption (for trucks/commercial):
> Other assumptions:
>
> F. What We Need To Tighten the Value (Top 5)
>
> G. Red Flags / Special Notes
>
> Invalid VIN risk
> Commercial upfit risk
> Salvage/rebuilt risk
> Specialty body/chassis mismatch risk
> Anything else that could materially change value

---

# Evolution From Signature Prompt to Signature Skill

The original Signature Prompt already established strong transparency and anti-fabrication rules.

This Signature Skill advances it by adding:

- Insurance AI Advantage System positioning
- Flywheel-stage metadata
- Orchestration-role metadata
- Source hierarchy
- Market Currency Standard
- VIN Validation Standard
- VIN Decode Boundary Standard
- Evidence Classification Standard
- Configuration Uncertainty Standard
- Commercial Upfit Standard
- Valuation Basis Standard
- Replacement Value Standard
- Range Construction Standard
- Confidence Scoring Standard
- Confidence Driver Standard
- Scenario Valuation Standard
- Data Integrity Standard
- Like-for-Like Comparable Standard
- Market Comparable Quality Standard
- Calculation Integrity Standard
- Workflow states
- Decision Conversion Standard
- Ownership
- Handoff Integrity
- System-of-Record Standard
- Transaction Lineage
- Dynamic Reassessment
- Stop rules
- Completion criteria
- Human Review Escalation
- Machine-readable valuation intelligence

The progression is:

**Signature Prompt → Signature Skill → Vehicle Valuation AI Teammate → Claims / Underwriting AI Workforce**

---

# Related Signature Skills

- [Commercial Insurance Underwriter Submission Narrative](../01-underwriter-submission-narrative/SKILL.md)
- [Commercial Insurance Coverage & Risk Advisory Analysis](../02-coverage-risk-advisory-analysis/SKILL.md)
- [Commercial Insurance Executive Proposal Narrative](../03-executive-proposal-narrative/SKILL.md)
- Fleet Exposure Intelligence
- Total Loss Triage Intelligence
- Commercial Vehicle Schedule Validation
- Property & Equipment Valuation Intelligence

Add live links as Signature Skills are published.

---

# Related Foundational Skills

This Signature Skill may consume or support:

- [Commercial Insurance Exposure Summary Builder](../../../ai-insurance-automation-guide/08-exposure-summary-builder/SKILL.md)
- [Commercial Insurance Client Service Response](../../../ai-insurance-automation-guide/15-client-service-response/SKILL.md)
- [Commercial Insurance First Notice of Loss (FNOL)](../../../ai-insurance-automation-guide/16-first-notice-of-loss/SKILL.md)
- [Commercial Insurance Claim Severity Assessment](../../../ai-insurance-automation-guide/17-claim-severity-assessment/SKILL.md)
- [Insurance Document Intelligence & Decision Impact Analysis](../../../ai-insurance-automation-guide/19-insurance-document-intelligence/SKILL.md)

---

# Suggested Invocation

```text
Run Signature Skill #4 — VIN Replacement Value Intelligence.

VIN:
[INSERT]

Mileage:
[OPTIONAL]

Condition:
[OPTIONAL]

ZIP / Market:
[OPTIONAL]

Body / Upfit:
[OPTIONAL]

Equipment:
[OPTIONAL]

Title / History:
[OPTIONAL]

Estimate Type:
[Retail Replacement / ACV / Stated Value Support / Claims Triage Estimate]
```

---

# Minimum Viable Invocation

```text
VIN:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release.

Fourth Signature Skill published under the Insurance AI Advantage System using the Apeironix Gold Standard Template v2.2.

---

# About the Insurance AI Advantage System

The Insurance AI Advantage System is an operating framework for transforming insurance expertise into connected AI capabilities.

The system is designed around:

**Foundational Skills → Signature Skills → AI Teammates → AI Workforce → AI Operating Layer**

### Foundational Skills

Make individual insurance expertise repeatable.

### Signature Skills

Combine multiple reasoning disciplines, workflow controls, structured data, human decision boundaries, and downstream handoffs into fully engineered operational capabilities.

### AI Teammates

Apply those capabilities to specific agency roles and workflows.

### AI Workforce

Coordinates multiple AI Teammates across the agency.

### AI Operating Layer

Connects AI work across CRM, AMS, carrier portals, claims systems, documents, email, financial systems, and other agency technology.

### Your people make the decisions. Your AI Teammates do the work.

**Keep your systems. Activate an AI Workforce.**

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Valuation
- Claims advocacy
- Underwriting support
- Risk analysis
- Growth

while AI handles more of the repetitive work surrounding those responsibilities.

Apeironix is building the AI Operating Layer for insurance agencies.

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
