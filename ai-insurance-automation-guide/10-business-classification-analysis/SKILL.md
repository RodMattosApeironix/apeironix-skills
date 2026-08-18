---
name: business-classification-analysis
title: Commercial Insurance Business Classification Analysis
collection: ai-insurance-automation-guide
prompt_number: 10
category: commercial-pc
capability: underwriting-intelligence
primary_role: commercial-insurance-underwriting-analyst
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

# Commercial Insurance Business Classification Analysis

## Purpose

Analyze a business description and determine how the operations would most likely be classified from a commercial insurance underwriting and rating perspective.

This Skill is designed to help the insurance professional:

- Understand what the business actually does
- Distinguish primary from incidental or secondary operations
- Identify likely insurance classifications
- Recognize when multiple classifications may apply
- Identify operational characteristics that materially affect classification
- Surface exposure categories associated with the operations
- Identify underwriting characteristics likely to influence appetite, pricing, or terms
- Identify coverage considerations created by the business model
- Highlight information needed before a final classification decision can be made
- Avoid relying solely on a company name, website category, NAICS description, or broad industry label

The objective is **not** to assign a code based on surface-level wording.

The objective is to develop a practical **Business Classification Analysis** that reflects how an experienced underwriter or rating professional would evaluate the actual operations.

---

# Core Outcome

A successful use of this Skill should help the insurance professional answer:

- What does this business actually do?
- Which operation generates the majority of revenue or payroll?
- What activity creates the primary insured exposure?
- What classification system is relevant?
- What is the most likely primary classification?
- Are secondary classifications required?
- Are any operations potentially separately rated?
- Are there classification ambiguities?
- What facts could materially change the classification?
- What underwriting concerns arise from the operating model?
- What coverage considerations should be evaluated?
- What information must be confirmed before relying on the classification?

The final output should support underwriting, rating, submission preparation, and client discovery.

---

# Best Used For

Use this Skill when analyzing:

- New commercial prospects
- New-business submissions
- Renewal exposure reviews
- Workers' compensation classification
- General liability classification
- Commercial package classification
- Businessowners policy eligibility
- Commercial auto operating classifications
- Property occupancy classification
- Contractor operations
- Manufacturing operations
- Distribution operations
- Professional services
- Retail operations
- Wholesale operations
- Service businesses
- Mixed operations
- Emerging business models
- Difficult-to-classify businesses
- Businesses with multiple revenue streams
- Businesses using subcontractors
- Businesses whose public description does not clearly reflect insured operations

This Skill is especially valuable before submitting an account to carriers or finalizing exposure data.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Carrier classification authority
- Rating bureau rules
- State-specific classification manuals
- NCCI rules
- Independent bureau rules
- WCIRB rules
- Carrier-specific underwriting manuals
- ISO classification manuals
- Regulatory interpretation
- Premium audit determinations
- Final carrier rating decisions
- Legal advice
- Tax classification
- NAICS assignment for government reporting
- SIC classification for regulatory purposes unless specifically requested

This is a **classification analysis and underwriting decision-support Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Underwriting Analysts
- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Placement Specialists
- Marketing Specialists
- Underwriting Specialists
- Premium Audit Teams
- Risk Advisors
- Agency Principals
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Business description**

Recommended format:

```text
Business Description:
[INSERT]
```

The description should ideally explain:

- What the company sells
- What services it performs
- Where work occurs
- Who performs the work
- Who the customers are
- Whether products are manufactured, distributed, installed, or repaired
- Whether subcontractors are used
- Whether employees work away from the premises
- Whether vehicles are used
- Whether professional advice or design is provided

If the business description is too broad to support a meaningful classification, identify the missing operational information.

---

# Recommended Inputs

The following inputs materially improve classification accuracy:

- Company name
- Website
- Primary state
- States of operation
- Annual revenue
- Revenue by operation
- Payroll
- Payroll by employee function
- Employee count
- Job descriptions
- Ownership responsibilities
- Customer types
- Products sold
- Services performed
- Manufacturing activity
- Installation activity
- Repair activity
- Wholesale activity
- Retail activity
- Distribution activity
- Construction activity
- Professional services
- Consulting
- Design
- Engineering
- Field work
- Office work
- Clerical payroll
- Sales payroll
- Delivery exposure
- Vehicle use
- Subcontractor costs
- Percentage subcontracted
- Work-at-height exposure
- Excavation
- Welding
- Hot work
- Hazardous materials
- Product end use
- Geographic scope
- International operations
- Prior classification codes
- Prior carrier classifications
- Current policies
- Premium audit results
- Current applications

---

# Optional Intelligence Sources

When research is appropriate, useful sources may include:

- Official company website
- Product and service pages
- Careers page
- Job descriptions
- Public business registrations
- Public licensing information
- Contractor license records
- Industry association information
- Public product catalogs
- Public project information
- Public regulatory records
- Reliable business databases
- Current classification manuals where authorized and available
- Current carrier underwriting guidance

External research should be used to understand operations, not to silently override client-confirmed information.

---

# Classification Authority Standard

Insurance classification depends on:

- Line of business
- State or jurisdiction
- Governing rating organization
- Carrier rules
- Actual operations
- Payroll or revenue allocation
- Policy structure

A code should never be treated as universally correct without identifying the applicable classification system.

Potential systems may include:

- Workers' compensation bureau classifications
- NCCI classifications
- Independent state bureau classifications
- WCIRB classifications
- ISO general liability classifications
- Carrier proprietary classifications
- Commercial auto classifications
- Property occupancy classifications
- Program-specific classifications

When the governing system is unknown:

- Identify likely classifications descriptively
- Provide code candidates only when supportable
- Clearly label them as provisional
- State what jurisdiction or rating authority must be confirmed

---

# Jurisdiction Standard

Classification can vary materially by state.

Before providing a definitive code, determine when possible:

- Primary state
- States where employees work
- States where operations occur
- Policy line
- Applicable rating authority

Do not assume a code used in one jurisdiction applies in another.

Where multiple states are involved:

- Identify whether classifications may vary
- Separate state-specific considerations when meaningful
- Flag the need for carrier or bureau confirmation

---

# Source Hierarchy

When classification information is available from multiple sources, prioritize:

1. Current governing classification manual or rating authority
2. Current carrier underwriting or rating guidance
3. Current carrier-issued classifications
4. Current client-confirmed operational information
5. Current applications and exposure schedules
6. Current premium audit information
7. Agency-verified information
8. Prior policy classifications
9. Public company information
10. Industry norms and professional inference

Do not rely on prior policy codes simply because they were used previously.

Prior classification may itself be incorrect or outdated.

---

# Evidence Classification

Every material classification conclusion should be treated as one of the following.

## Verified Classification

Supported by the applicable current rating authority, carrier, or other authoritative source.

---

## Likely Primary Classification

Most consistent with the known operations but requiring carrier or bureau confirmation.

---

## Likely Secondary Classification

A separate operation that may warrant an additional classification if it meets applicable separation or rating rules.

---

## Alternative Classification

Another reasonable classification depending on an unresolved operational fact.

---

## Incidental Operation

An activity that may not require a separate classification depending on governing rules.

---

## Requires Classification Authority Review

The available information is insufficient to assign or distinguish the classification responsibly.

---

# Confidence Classification

Where useful, classify conclusions:

### High Confidence

Operations are clear and classification authority strongly supports the classification.

### Moderate Confidence

Classification is likely but one or more operational or jurisdictional details remain unresolved.

### Low Confidence

Multiple classifications remain plausible or the governing rating system is unknown.

Do not create false precision.

---

# Core Principle

## Classify the Work Actually Performed

Do not classify a business solely based on:

- Company name
- Marketing description
- NAICS category
- Website headline
- Corporate registration
- Customer industry
- Product name

The classification should reflect:

- What employees actually do
- Where work is performed
- What operations generate revenue
- What hazards are created
- Whether operations are separately identifiable

Ask:

> What work is actually being performed, and what exposure does that work create?

---

# Workflow

Follow the workflow in order unless circumstances clearly require another sequence.

---

## Step 1 — Define the Business Model

Identify:

- Primary products
- Primary services
- Revenue-producing operations
- Customer types
- Work locations
- Employee activities
- Use of equipment
- Vehicle activity
- Subcontracted work
- Professional services
- Installation or field operations

Do not classify until the actual operating model is understood.

---

## Step 2 — Identify the Primary Operation

Determine the activity that appears to represent the core business.

Consider:

- Revenue
- Payroll
- Employee activity
- Operational importance
- Hazard
- Customer contracts

The primary classification should generally correspond to the dominant insurable operation, subject to applicable classification rules.

---

## Step 3 — Identify Secondary Operations

Look for distinct operations such as:

- Installation
- Manufacturing
- Repair
- Delivery
- Warehousing
- Retail
- Wholesale
- Consulting
- Design
- Clerical
- Outside sales
- Field service
- Construction
- Subcontracted operations

Determine whether each operation is:

- Separately classifiable
- Incidental
- Included in another classification
- Dependent on governing rules

Do not automatically create separate codes for every employee function.

---

## Step 4 — Identify the Relevant Classification System

Determine which system is being analyzed.

Examples:

### Workers' Compensation

Often driven by:

- Employee duties
- Payroll
- State
- Bureau rules

### General Liability

Often driven by:

- Business operations
- Revenue
- Products
- Completed operations
- Location exposure
- Classification descriptions

### Property

Often driven by:

- Occupancy
- Construction
- Protection
- Use

### Commercial Auto

Often driven by:

- Vehicle type
- Use
- Radius
- Business use
- Garaging

Do not combine classification systems as though they are interchangeable.

---

## Step 5 — Identify Likely Classifications

For each relevant classification:

### Classification

[Description]

### Likely Code

[Code if supportable]

### Classification System

[NCCI / WCIRB / ISO / Carrier / Other]

### Why It Fits

[Operational reasoning]

### Exposure Basis

[Payroll / Sales / Units / Other]

### Confidence

High / Moderate / Low

### Verification Required

[Carrier / Bureau / State / Manual]

---

## Step 6 — Evaluate Mixed Operations

When multiple business activities exist, determine whether:

- One operation dominates
- Operations are truly separate
- Employees cross between activities
- Payroll can be separated
- Revenue can be separated
- Work occurs at different locations
- Operations create materially different hazards

Mixed operations may require more than one classification.

However, classification separation rules vary.

Do not assume payroll or revenue can automatically be split.

---

# Separation of Operations Standard

Do not recommend separate classifications solely because a company has multiple departments.

Before suggesting separate classifications, consider:

- Whether duties are operationally distinct
- Whether payroll records separately track employees
- Whether governing rules permit separation
- Whether employees interchange between operations
- Whether one classification includes the other operation

When separation requirements are unknown, state:

> Separate classification may be possible, subject to applicable bureau and carrier rules.

---

## Step 7 — Identify Governing Operational Details

Determine what facts are most likely to change classification.

Examples:

- Manufacturing vs. assembly
- Wholesale vs. retail
- Installation vs. delivery only
- Repair vs. fabrication
- Office-based consulting vs. field engineering
- General contracting vs. subcontracting only
- Residential vs. commercial construction
- Shop work vs. field work
- Product distribution vs. product manufacturing
- Janitorial vs. specialized industrial cleaning
- Landscape maintenance vs. tree work
- Warehousing vs. trucking
- Staffing office vs. employees placed at client locations

These distinctions often matter more than the broad industry name.

---

## Step 8 — Identify Employee Function Differences

Where workers' compensation is relevant, identify employee groups such as:

- Clerical
- Outside sales
- Drivers
- Shop employees
- Field technicians
- Installers
- Construction employees
- Supervisors
- Executives
- Warehouse employees
- Manufacturing employees

Do not assume clerical or sales classifications apply without confirming applicable rules and employee duties.

---

## Step 9 — Identify Payroll Allocation Concerns

Where workers' compensation classification is relevant, evaluate:

- Payroll by role
- Payroll by class
- Employee interchange
- Overtime treatment
- Executive payroll
- Owners
- Subcontractor payroll exposure
- Uninsured subcontractors
- Temporary labor

Flag when payroll allocation could materially affect premium.

---

## Step 10 — Identify Revenue / Sales Allocation Concerns

Where general liability or other sales-rated coverage is relevant, evaluate:

- Revenue by operation
- Product vs. service revenue
- Installation revenue
- Subcontracted work
- Domestic vs. international revenue
- Revenue from higher-hazard activities

Do not assume total sales are the correct exposure basis for every classification.

---

## Step 11 — Evaluate Subcontractor Exposure

Determine:

- Whether subcontractors are used
- What work they perform
- Percentage of operations subcontracted
- Whether certificates are obtained
- Whether contractual risk transfer is used
- Whether subcontractors are insured
- Whether uninsured subcontractor costs may affect rating

Subcontractor usage may materially influence:

- Classification
- General liability
- Workers' compensation
- Underwriting appetite
- Pricing

---

## Step 12 — Identify Product Exposure

If products are involved, determine whether the insured:

- Manufactures
- Imports
- Distributes
- Wholesales
- Retails
- Private labels
- Installs
- Repairs
- Designs

Identify:

- Product end use
- Critical applications
- Product recall exposure
- Completed operations
- Contractual requirements

Product role can materially change underwriting classification.

---

## Step 13 — Identify Professional Services

Determine whether the company provides:

- Design
- Engineering
- Architecture
- Consulting
- Advice
- Specifications
- Project management
- Technical recommendations
- Technology services

Professional services may create exposure outside the primary commercial general liability classification.

---

## Step 14 — Identify Location and Premises Characteristics

Where relevant, identify:

- Retail premises
- Warehouse
- Manufacturing plant
- Office
- Jobsite work
- Customer premises
- Residential work
- Commercial work
- Industrial facilities

Location and worksite characteristics may materially influence underwriting.

---

## Step 15 — Identify Hazard Characteristics

Identify hazards such as:

- Heavy machinery
- Welding
- Hot work
- Heights
- Excavation
- Confined spaces
- Hazardous materials
- Driving
- Heavy lifting
- Food handling
- High-value property
- Flammable materials
- Product severity
- Professional errors
- Cyber exposure

These characteristics help explain why a classification fits and what underwriting concerns may follow.

---

## Step 16 — Identify Alternative Classifications

When multiple interpretations are plausible, provide alternatives.

For each alternative:

### Alternative Classification

[Description / Code candidate]

### Why It Could Apply

[Reason]

### What Fact Determines the Difference

[Key operational distinction]

Example:

> If the company only distributes pre-manufactured components, a wholesale classification may be appropriate. If employees fabricate or materially modify the components, a manufacturing classification may be more appropriate.

This is preferable to forcing a single unsupported answer.

---

## Step 17 — Identify Classification Red Flags

Potential red flags include:

- Business description does not match policy classification
- Significant operations are omitted
- Payroll appears concentrated in an unexpectedly low-hazard classification
- Revenue allocation appears inconsistent
- Employees perform multiple functions
- Subcontractor work is unclear
- Field work is not reflected
- Product manufacturing is described as distribution
- Installation is omitted
- Construction activity is understated
- Professional services are not disclosed
- Prior class codes appear inconsistent with current operations

Flag these for review.

---

# Classification Drift Standard

Businesses change over time.

A classification that was appropriate several years ago may no longer reflect current operations.

Review for:

- New products
- New services
- New locations
- New states
- New delivery activity
- New installation work
- Increased subcontracting
- New manufacturing
- New professional services
- Acquisition
- Expansion into higher-hazard work

When operations have changed materially, prior classifications should be revalidated.

---

## Step 18 — Develop the Underwriting Exposure Map

Translate classification into underwriting exposure categories.

Potential categories:

- Premises
- Operations
- Products
- Completed operations
- Auto
- Workers' compensation
- Property
- Professional liability
- Cyber
- Pollution
- Inland marine
- Contractual liability
- Employment practices

Only include relevant categories.

---

## Step 19 — Identify Core Risk Characteristics

Determine what characteristics will influence underwriting decisions.

Examples:

- Hazard level
- Severity potential
- Frequency potential
- Employee duties
- Customer type
- Contract structure
- Geographic scope
- Fleet use
- Product end use
- Subcontractor usage
- Property characteristics
- Safety controls
- Claims experience
- Management experience

Rank material characteristics.

---

## Step 20 — Identify Coverage Considerations

Based on classification and operations, identify coverage areas that should be evaluated.

Potential considerations:

- General Liability
- Products / Completed Operations
- Professional Liability
- Commercial Auto
- Hired / Non-Owned Auto
- Workers' Compensation
- Umbrella / Excess
- Property
- Inland Marine
- Equipment Breakdown
- Cyber
- Pollution
- Contractors Pollution
- Product Recall
- Employment Practices
- Crime

Do not imply a coverage gap solely from classification.

Use:

> Should be evaluated

rather than:

> Is missing

unless actual policy information supports the conclusion.

---

## Step 21 — Identify Questions Required for Final Classification

Develop only the questions capable of materially affecting classification.

Examples:

- What percentage of revenue comes from installation?
- Do employees fabricate the product or only distribute it?
- Are any employees performing work at customer locations?
- Are subcontractors used for core operations?
- Is payroll separately tracked by employee duty?
- Do drivers deliver company products?
- Does the company perform any design or engineering?
- Are residential projects performed?
- Does the company import products directly?

Avoid generic questionnaires.

---

## Step 22 — Determine Classification Readiness

Classify the available information.

### Classification Ready

Core operational facts and applicable rating system are sufficiently clear.

### Conditionally Ready

Likely classifications can be identified, but one or more facts require confirmation.

### Not Ready

The business description is too ambiguous or the governing classification system is unknown.

Do not force a definitive code when the information does not support one.

---

# Materiality / Prioritization Framework

Prioritize classification issues using:

| Factor | Question |
|---|---|
| Premium Impact | Could the classification materially change premium? |
| Exposure Severity | Does the operation create materially different loss potential? |
| Employee Activity | Do duties differ meaningfully? |
| Revenue Allocation | Are materially different operations being combined? |
| Jurisdiction | Could state rules change the classification? |
| Underwriting Impact | Could the classification change appetite or terms? |
| Coverage Impact | Does the operation create additional coverage considerations? |
| Audit Risk | Could incorrect classification create material premium audit exposure? |
| Evidence | How well supported is the classification? |

Use professional judgment.

---

# Decision Rules

## Operations Before Labels

Do not classify based solely on what the company calls itself.

---

## Primary vs. Secondary Must Be Operationally Supported

Do not create unnecessary secondary classifications.

---

## Never Assume Classification Separation

Separate payroll or revenue classifications require applicable rules and operational support.

---

## Jurisdiction Matters

Do not state that a code is universally applicable across states.

---

## Classification System Matters

Do not treat:

- NCCI
- WCIRB
- ISO
- Carrier-specific classifications

as interchangeable systems.

---

## Prior Classification Is Evidence, Not Proof

Prior policy codes can be useful but should not override current operations.

---

## Alternative Interpretations Should Be Disclosed

If more than one classification is reasonable, explain why.

---

## Classification Does Not Establish Coverage

A correct class code does not prove the insurance program adequately covers the operation.

---

## Do Not Chase the Lowest Rate

Classification should reflect actual operations.

Never recommend a lower-rated classification solely because it reduces premium.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Commercial Business Classification Analysis

## Business Snapshot

**Business:** [If known]  
**Primary State:** [If known]  
**Industry:** [If known]  
**Classification System:** [If known]

---

# 1. Executive Classification Perspective

Provide a concise summary answering:

- What does the business primarily do?
- What is the likely primary classification?
- Are secondary classifications likely?
- What is the main classification uncertainty?
- What should be confirmed first?

---

# 2. Classification Readiness

**Status:** Classification Ready / Conditionally Ready / Not Ready

### Information Reviewed

[List]

### Material Information Gaps

[List]

---

# 3. Likely Classifications

| Priority | Classification | Likely Code | System / Authority | Why It Fits | Confidence |
|---|---|---|---|---|---|
| Primary | [Classification] | [Code if supportable] | [System] | [Reason] | High / Moderate / Low |
| Secondary | [Classification] | [Code] | [System] | [Reason] | [Confidence] |

If the exact code cannot be responsibly determined, use:

`Requires current classification authority review`

rather than inventing a code.

---

# 4. Alternative Classifications

| Alternative | When It May Apply | Key Distinguishing Fact | Verification Needed |
|---|---|---|---|
| [Classification] | [Condition] | [Fact] | [Action] |

Omit if no meaningful alternative exists.

---

# 5. Key Exposure Categories

| Exposure | Relevance | Operational Basis | Underwriting Impact |
|---|---|---|---|
| [Exposure] | High / Medium / Low | [Reason] | [Impact] |

---

# 6. Core Risk Characteristics

Rank the most important characteristics.

| Priority | Risk Characteristic | Why It Matters |
|---|---|---|
| High | [Characteristic] | [Reason] |

---

# 7. Classification Red Flags

Identify:

- Existing code mismatch
- Undisclosed operation
- Payroll allocation concern
- Revenue allocation concern
- Mixed duties
- Field activity
- Installation
- Manufacturing
- Subcontractor issue
- Professional services

Omit if no meaningful red flags are identified.

---

# 8. Coverage Considerations

For each relevant coverage:

## [Coverage]

**Operational reason:**  
[Why it should be evaluated]

**Primary exposure:**  
[Exposure]

**What to confirm:**  
[Question]

Do not imply the coverage is currently missing without policy information.

---

# 9. Questions Required for Final Classification

Provide the highest-value questions.

1. [Question]
2. [Question]
3. [Question]

Limit questions to those capable of changing the classification or underwriting analysis.

---

# 10. Recommended Classification Action

### Primary Classification Approach

[Recommendation]

### Secondary Classification Approach

[If applicable]

### Authority to Confirm

[Carrier / NCCI / WCIRB / State Bureau / ISO / Other]

### Immediate Next Step

[Action]

---

# Assumptions & Items Requiring Confirmation

Use whenever inference is involved.

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Actual business operations were analyzed
- [ ] Company name alone was not used to determine classification
- [ ] Primary operation is identified
- [ ] Secondary operations were considered
- [ ] Relevant classification system is identified where possible
- [ ] Jurisdiction is considered
- [ ] Carrier or bureau authority is distinguished from inference
- [ ] Class codes are not invented
- [ ] Alternative classifications are disclosed when appropriate
- [ ] Employee duties are considered
- [ ] Payroll allocation is considered where relevant
- [ ] Revenue allocation is considered where relevant
- [ ] Subcontractor exposure is considered
- [ ] Product exposure is considered
- [ ] Professional services are considered
- [ ] Field operations are considered
- [ ] Mixed operations are evaluated
- [ ] Separation rules are not assumed
- [ ] Classification drift is considered
- [ ] Prior codes are not treated as definitive proof
- [ ] Coverage considerations are exposure-driven
- [ ] Classification does not imply coverage
- [ ] Questions requiring confirmation are specific
- [ ] Classification readiness is stated
- [ ] Final recommendations prioritize accuracy over premium reduction

---

# Failure Conditions

The Skill should not be considered complete if:

- The classification is based only on the company name
- A generic industry label is treated as sufficient
- Exact codes are invented
- Jurisdiction is ignored where it matters
- Different classification systems are conflated
- Secondary operations are ignored
- Every business activity is unnecessarily assigned a separate code
- Payroll separation is assumed without support
- Revenue allocation is ignored where relevant
- Mixed employee duties are ignored
- Product or installation exposure is overlooked
- Alternative classifications are not disclosed when materially plausible
- Prior classifications are accepted without evaluating current operations
- Classification is optimized solely to reduce premium
- Coverage conclusions are made solely from classification
- Material information gaps are not disclosed

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Class Codes

Never invent:

- NCCI codes
- WCIRB codes
- ISO classifications
- Carrier classifications
- Exposure bases
- Rating rules

If the correct code cannot be supported, state that authoritative confirmation is required.

---

## Do Not Optimize Classification for Premium

Classification must reflect actual operations.

Never recommend a classification because:

- It has a lower rate
- It produces lower premium
- It avoids an audit issue

unless it is also the correct classification under applicable rules.

---

## Do Not Treat Prior Codes as Automatically Correct

Existing classifications may be:

- Outdated
- Incorrect
- Incomplete
- Based on prior operations

Revalidate when operations have changed.

---

## Do Not Assume Payroll Separation

Whether payroll may be separated among classifications depends on applicable rules and actual employee duties.

---

## Do Not Assume Revenue Separation

Revenue allocation should follow applicable rating rules and actual operations.

---

## Do Not Treat Classification as Coverage

A classification does not establish:

- Coverage exists
- Coverage is adequate
- A claim is covered
- A policy responds
- A carrier accepts the operation

---

## No Legal or Regulatory Conclusions

State-specific classification and rating rules may involve regulatory requirements.

Defer final classification decisions to authorized carrier, bureau, audit, or regulatory authorities where appropriate.

---

## Protect Confidential Information

Use only information needed for classification.

Do not unnecessarily expose:

- Personally identifiable employee information
- Payroll details at an individual level
- Confidential customer information
- Proprietary company information
- Financial account information

Use aggregated data where sufficient.

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized insurance professional, carrier, rating bureau, premium auditor, or other governing authority remains responsible for:

- Final classification
- Rating
- Payroll allocation
- Revenue allocation
- Carrier submission
- Compliance
- Premium audit decisions
- Coverage recommendations
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced commercial underwriting analyst.

The tone should be:

- Practical
- Analytical
- Precise
- Operationally focused
- Underwriter-aware
- Concise
- Transparent about uncertainty
- Non-alarmist

Avoid:

- Guessing exact codes
- Overconfidence
- Generic industry descriptions
- Rate-shopping logic
- Excessive jargon
- Unsupported regulatory conclusions
- Long unprioritized lists

The objective is classification accuracy and underwriting clarity.

---

# Example

## Example Request

```text
Business Description:

A Nevada company sells and installs commercial security systems for warehouses, offices, and industrial facilities.

Approximately 60% of revenue comes from system installation, 25% from equipment sales, and 15% from monitoring and service agreements.

The company has 18 field technicians, 4 salespeople, and 6 office employees.

Field technicians install cameras, access-control systems, wiring, and alarm equipment at customer locations. Some work requires ladders, but no major structural construction is performed.

The company operates 12 service vans.

Primary state is Nevada.
```

---

## Example Output Excerpt

### Executive Classification Perspective

The business should not be classified simply as an electronics retailer or alarm-monitoring company.

The dominant exposure is field installation of commercial security and access-control systems, representing approximately 60% of revenue and the majority of operational employee activity.

A contractor or low-voltage electrical/security-system installation classification is therefore likely to represent the primary exposure, subject to the applicable Nevada workers' compensation and carrier classification rules.

Separate clerical and outside-sales classifications may be possible where applicable rules and employee duties support separation.

Equipment sales and monitoring operations should also be evaluated to determine whether they are included within the primary classification or warrant separate treatment.

---

### Likely Classifications

| Priority | Classification | Likely Code | System / Authority | Why It Fits | Confidence |
|---|---|---|---|---|---|
| Primary | Security / low-voltage system installation | Requires current classification authority review | Applicable Nevada WC / carrier rules | Installation represents the dominant operation and field payroll exposure | Moderate |
| Secondary | Clerical office employees | Requires authority confirmation | Applicable WC authority | Employees appear to perform office-only functions | Moderate |
| Secondary | Outside sales | Requires authority confirmation | Applicable WC authority | Dedicated sales employees may qualify if duties meet applicable rules | Moderate |

---

### Alternative Classification

If technicians perform significant electrical work beyond low-voltage security-system installation, an electrical contractor classification may be more appropriate.

The key distinguishing fact is the scope of electrical work performed and whether technicians work on energized or higher-voltage systems.

---

### Core Risk Characteristics

| Priority | Risk Characteristic | Why It Matters |
|---|---|---|
| High | Field installation | Employees work at customer locations and create completed-operations exposure |
| High | Ladder work | Creates workers' compensation severity potential |
| High | 12 service vans | Commercial auto exposure is material |
| Medium | Installed security systems | Failure of installed systems may create professional or technology-related liability questions |
| Medium | Recurring monitoring/service agreements | Creates ongoing service and technology dependency |

---

### Coverage Considerations

## Commercial General Liability

**Operational reason:**  
Installation activity creates premises/operations and completed-operations exposure.

**What to confirm:**  
Current classifications, subcontractor usage, contractual requirements, and completed-operations treatment.

## Commercial Auto

**Operational reason:**  
The company operates 12 service vans used by field technicians.

**What to confirm:**  
Vehicle schedule, driver controls, radius, and hired/non-owned exposure.

## Professional / Technology Liability

**Operational reason:**  
If the company designs system layouts, specifies equipment, programs access controls, or provides monitoring services, errors may create economic or security-related losses not addressed solely by general liability.

**What to confirm:**  
Scope of design, programming, monitoring, and contractual responsibilities.

---

### Questions Required for Final Classification

1. Do technicians perform only low-voltage wiring, or do they perform higher-voltage electrical work?
2. Is payroll separately tracked for office, sales, and field employees?
3. Does the company design security systems or only install customer/specification-based systems?
4. Are any installation activities subcontracted?
5. Does the company provide continuous alarm monitoring directly or through a third party?

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a commercial insurance underwriting analyst responsible for accurately classifying business operations and identifying key exposure characteristics.
>
> Review the business description below and determine how it would most likely be classified from an underwriting and rating perspective.
>
> Business Description:
> [INSERT]
>
> Think beyond surface-level descriptions. Consider how the business actually operates, where risk is created, and how underwriters would evaluate it.
>
> Provide a structured analysis that includes:
>
> - Likely class codes (where applicable), including primary and any secondary classifications
> - Key exposure categories based on operations
> - Core risk characteristics that would influence underwriting decisions
> - Coverage considerations that should be addressed based on this classification
>
> Where there is uncertainty or multiple possible interpretations, clearly explain the reasoning and note alternative classifications.
>
> Keep the output practical, accurate, and aligned with real-world underwriting thinking.

---

# Evolution From Prompt to Skill

The original prompt established the goal of accurately classifying business operations while considering underwriting exposure.

This Skill expands that prompt into a reusable Underwriting Intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Optional intelligence sources
- Classification Authority Standard
- Jurisdiction Standard
- Source hierarchy
- Evidence classification
- Confidence classification
- Primary-operation analysis
- Secondary-operation analysis
- Classification-system identification
- Mixed-operations analysis
- Separation of Operations Standard
- Employee-function analysis
- Payroll-allocation review
- Revenue-allocation review
- Subcontractor analysis
- Product-role analysis
- Professional-services analysis
- Location and premises analysis
- Hazard-characteristic analysis
- Alternative-classification framework
- Classification-red-flag review
- Classification Drift Standard
- Underwriting exposure mapping
- Coverage-consideration framework
- Classification-readiness framework
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a classification prompt into a reusable **Business Classification Intelligence Skill**.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Prospect Intelligence Brief](../01-prospect-intelligence-brief/SKILL.md)
- [Commercial Insurance Meeting Strategy Builder](../02-meeting-strategy-builder/SKILL.md)
- [Commercial Insurance Coverage Gap Analysis](../03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Renewal Strategy Builder](../04-renewal-strategy-builder/SKILL.md)
- [Commercial Insurance Underwriter Submission Email](../07-underwriter-submission-email/SKILL.md)
- [Commercial Insurance Exposure Summary Builder](../08-exposure-summary-builder/SKILL.md)
- [Commercial Insurance Carrier Placement Strategy](../09-carrier-placement-strategy/SKILL.md)
- Workers' Compensation Classification Review
- General Liability Classification Review
- Premium Audit Analysis
- Exposure Verification
- Commercial Submission Preparation

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Perform a Commercial Insurance Business Classification Analysis.

Business:
[OPTIONAL]

Primary State:
[OPTIONAL]

Classification Type:
[Workers' Compensation / General Liability / Multi-Line / OPTIONAL]

Business Description:
[INSERT]

Revenue by Operation:
[OPTIONAL]

Payroll by Employee Function:
[OPTIONAL]

Current Classifications:
[OPTIONAL]

Additional Context:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Business Description:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #10 include:

- Classification Authority Standard
- Jurisdiction Standard
- Classification-system separation
- Primary and secondary classification framework
- Mixed-operations analysis
- Separation of Operations Standard
- Payroll-allocation review
- Revenue-allocation review
- Employee-duty analysis
- Subcontractor analysis
- Product-role analysis
- Professional-services analysis
- Alternative-classification framework
- Classification-red-flag detection
- Classification Drift Standard
- Classification-readiness assessment
- Exposure and coverage mapping
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
- Classification accuracy
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
