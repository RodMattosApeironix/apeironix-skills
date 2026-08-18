---
name: prospect-intelligence-brief
title: Commercial Prospect Intelligence Brief
collection: ai-insurance-automation-guide
prompt_number: 1
category: commercial-pc
capability: client-intelligence
primary_role: commercial-insurance-producer
secondary_roles:
  - commercial-account-executive
  - commercial-account-manager
  - risk-advisor
  - sales-leader
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---
---

# Commercial Prospect Intelligence Brief

## Purpose

Prepare a commercial insurance producer, advisor, or account executive for a first meeting with a prospective client by developing a structured, insurance-specific understanding of the business before the conversation begins.

This Skill is designed to help the insurance professional quickly understand:

- How the prospect likely operates
- Where material risk exists
- What the likely insurance program should include
- Where coverage commonly falls short
- Which operational exposures deserve deeper discovery
- Which questions are most likely to uncover meaningful risk
- Where the producer may be able to introduce advisory value early
- How to enter the first meeting with a point of view rather than a generic questionnaire

The objective is **not** to create a generic company profile.

The objective is to create a practical, underwriter-level **Prospect Intelligence Brief** that enables an experienced commercial insurance professional to lead a higher-value first conversation.

The output should help the producer understand the prospect well enough to begin thinking like both:

1. The client’s risk advisor, and
2. The underwriter who may eventually evaluate the account.

---

# Core Outcome

A successful use of this Skill should allow the producer to walk into the first meeting able to answer:

- What does this company actually do?
- How does it make money?
- What could materially interrupt that business?
- What types of losses are most likely?
- What types of losses could be most severe?
- What would an underwriter want to know?
- What insurance program would normally support a company like this?
- Where do similar companies often have coverage gaps?
- Which risks should be explored first?
- What should I ask that demonstrates expertise?
- What is the best initial advisory wedge?

The producer should finish the brief with a clear meeting strategy, not merely more information.

---

# Best Used For

Use this Skill when preparing for:

- A first commercial insurance prospect meeting
- A producer discovery call
- A mid-market commercial P&C introduction
- A broker-of-record opportunity
- A pre-renewal prospect conversation
- An account qualification meeting
- A targeted industry prospecting campaign
- A producer cold-to-warm introduction
- A referral meeting
- A cross-sell opportunity involving an existing relationship
- A commercial account strategy session
- A new market or industry vertical initiative

This Skill is particularly valuable when only limited information is available initially.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A formal policy review
- A coverage comparison
- A complete underwriting submission
- A carrier appetite determination
- A loss-control inspection
- A legal review
- A contract review by counsel
- A regulatory opinion
- A binding recommendation
- A policy interpretation
- A coverage determination
- A claim-coverage determination
- Verified client discovery
- Final account placement strategy

This is a **pre-meeting intelligence and discovery Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Risk Advisors
- Agency Principals
- Sales Leaders
- Practice Leaders
- Business Development Professionals
- Commercial Insurance Consultants
- Other authorized insurance professionals

---

# Required Inputs

At minimum, obtain:

1. **Company Name**
2. **Industry**
3. **Primary Location**

Recommended input format:

```text
Company Name: [INSERT]
Industry: [INSERT]
Location: [INSERT]
```

If any required input is missing, identify the missing information before completing the full brief.

---

# Recommended Inputs

The following inputs materially improve the analysis:

- Company website
- Estimated annual revenue
- Employee count
- Number of locations
- States of operation
- Years in business
- Ownership structure
- Product or service description
- Customer types
- Major contracts
- Vehicle/fleet information
- Property ownership or leasing details
- Equipment values
- Payroll estimate
- Use of subcontractors
- International operations
- Import/export activity
- Manufacturing operations
- Distribution operations
- Professional services
- Construction activities
- Technology dependency
- Current carrier
- Current insurance program
- Current premium
- Loss history
- Known renewal date
- Existing broker
- Known pain points
- Publicly available company information

---

# Optional Intelligence Sources

When appropriate and available, useful research sources may include:

- Official company website
- Company About page
- Locations page
- Products/services pages
- Careers page
- Press releases
- Public corporate filings
- Secretary of State records
- OSHA or regulatory information
- Industry association information
- Company social media
- Public job postings
- Public fleet or transportation information
- News coverage
- Trade publications
- Reliable business databases
- Public contract awards
- Public permit information
- Public litigation or regulatory records when relevant and appropriate
- Other credible public sources

Do not rely on a single source when material information can reasonably be corroborated.

---

# Research Standard

When research capabilities are available, perform enough research to understand the operating model of the company.

Do not stop after locating a company description.

Look for indicators of:

- What the company sells
- Who buys from them
- Where they operate
- How work is performed
- What assets they rely on
- What could cause a severe loss
- What contracts they may enter into
- What employees do
- Whether vehicles are used
- Whether subcontractors are used
- Whether products are manufactured or distributed
- Whether professional services are provided
- Whether data or technology is mission-critical
- Whether the business depends on a small number of facilities, vendors, or customers
- Whether geographic catastrophe exposure is meaningful

The purpose of research is to understand the **risk architecture of the business**.

---

# Source Hierarchy

When information is available from multiple sources, prioritize:

1. Information directly supplied by the prospect or user
2. Official company website
3. Official filings or public records
4. Carrier-issued or agency-verified information
5. Authoritative industry sources
6. Reliable business databases
7. Reputable trade or news sources
8. Industry norms and professional inference

When sources conflict:

- Identify the discrepancy
- Do not silently choose one value
- State which source appears more authoritative
- Flag the issue for confirmation during discovery

---

# Evidence Classification

Every meaningful company-specific observation should fall into one of these categories.

## Verified Fact

Information directly supported by a credible source.

Example:

> The company operates three facilities in Nevada and Arizona.

Use when the information is supported.

---

## Reasonable Industry Inference

A likely exposure, operational characteristic, or program feature based on the company’s industry, size, geography, or business model.

Example:

> A distributor of this type would commonly have hired/non-owned auto exposure if employees use personal vehicles for business purposes.

Use when the inference is reasonable but not verified.

---

## Discovery Hypothesis

A possible risk or weakness that should be explored but cannot be assumed.

Example:

> Determine whether customer contracts require broad additional insured status, primary/noncontributory wording, or waiver of subrogation.

Use when the issue is worth investigating.

---

# Confidence Classification

Where useful, classify material conclusions:

### High Confidence

Supported by direct or authoritative information.

### Moderate Confidence

Strongly supported by industry norms or multiple indicators.

### Low Confidence

Possible but requires meaningful confirmation.

Do not give false precision.

---

# Core Principle

## Never Convert an Inference Into a Fact

This Skill intentionally permits reasonable insurance-specific inference because prospect preparation often begins with incomplete information.

However:

- Inference must be labeled
- Assumptions must be disclosed
- Unknown information must remain unknown
- The producer must know what still needs to be confirmed

Use language such as:

- “Likely”
- “Typical for companies of this type”
- “Common industry exposure”
- “Worth confirming”
- “Potential exposure”
- “If the company performs X...”
- “Based on industry norms...”

Avoid language that implies certainty without evidence.

---

# Workflow

Follow the workflow in order unless the circumstances clearly justify a different sequence.

---

## Step 1 — Establish the Business Profile

Develop a concise working understanding of the company.

Identify when available:

- Primary business activity
- Revenue model
- Products
- Services
- Customer types
- Industry segment
- Geographic footprint
- Number and type of locations
- Property footprint
- Equipment dependency
- Employee roles
- Vehicle/fleet exposure
- Contractual relationships
- Vendor dependency
- Subcontractor usage
- Manufacturing activity
- Distribution activity
- Professional services
- Technology dependency
- International exposure
- Product responsibility
- Completed operations
- Business continuity dependencies

Do not merely repeat marketing copy from the company website.

Translate what the company does into **insurance-relevant operational characteristics**.

---

## Step 2 — Understand How the Business Makes Money

Identify:

- Primary revenue-producing activity
- Core products or services
- Critical facilities
- Critical equipment
- Key employees or specialized labor
- Major customers
- Important vendors
- Important suppliers
- Distribution channels
- Contractual dependencies
- Geographic dependencies
- Technology dependencies

Ask:

> What would have to fail for this company to stop generating revenue?

This question should influence the risk analysis.

---

## Step 3 — Map the Exposure Architecture

Evaluate the company across the following risk categories.

Do not force every category into the final output.

Use only those materially relevant to the company.

### Property Risk

Evaluate potential exposure involving:

- Buildings
- Tenant improvements
- Business personal property
- Machinery
- Equipment
- Inventory
- Stock
- Tools
- Mobile equipment
- Property of others
- Property off premises
- Property in transit
- Outdoor property
- Catastrophe exposure
- Fire protection
- Sprinkler systems
- Water damage
- Equipment breakdown
- Ordinance or law
- Replacement-cost adequacy

### Business Income / Continuity Risk

Evaluate:

- Revenue dependency on physical locations
- Restoration timelines
- Specialized equipment lead times
- Supply-chain dependencies
- Utility interruption
- Key suppliers
- Key customers
- Contingent business interruption
- Extra expense
- Civil authority
- Ingress/egress
- Extended period of indemnity
- Disaster recovery
- Business continuity planning

### General Liability Risk

Evaluate:

- Premises exposure
- Operations exposure
- Products exposure
- Completed operations
- Contractual liability
- Additional insured requirements
- Customer indemnification requirements
- Vendors
- Subcontractors
- Third-party bodily injury
- Third-party property damage

### Commercial Auto Risk

Evaluate:

- Owned vehicles
- Employee drivers
- Hired vehicles
- Non-owned vehicles
- Personal vehicles used for business
- Delivery activity
- Radius of operation
- Vehicle type
- Driver qualification
- MVR practices
- Telematics
- Distracted-driving controls
- Large vehicle exposure
- Catastrophic auto severity

### Workers’ Compensation Risk

Evaluate:

- Employee roles
- Payroll concentration
- Hazardous work
- Lifting
- Repetitive motion
- Driving
- Machinery
- Construction
- Working at height
- Heat exposure
- Remote operations
- Employee training
- Return-to-work practices
- Experience modification
- Claims frequency
- Claims severity

### Professional Liability Risk

Evaluate whether the company provides:

- Advice
- Design
- Engineering
- Consulting
- Specifications
- Professional services
- Technology services
- Recommendations
- Project management

Determine whether professional liability could exist independently from general liability.

### Cyber / Technology Risk

Evaluate:

- Customer data
- Employee data
- Payment systems
- Wire transfers
- Cloud dependency
- Cybersecurity practices
- Business-email compromise
- Ransomware
- Privacy obligations
- Technology outages
- System dependency
- Third-party technology vendors
- Funds-transfer exposure

### Employment Practices Risk

Evaluate:

- Employee count
- Multi-state workforce
- Hiring practices
- Termination practices
- Wage/hour exposure
- Harassment/discrimination allegations
- Employee handbook practices
- HR sophistication
- Remote workforce
- Management structure

### Management Liability Risk

Where applicable, evaluate:

- Ownership structure
- Board structure
- Investors
- Private equity
- Outside directors
- Fiduciary obligations
- M&A activity
- Employment-related claims
- Regulatory exposure

### Crime / Financial Risk

Evaluate:

- Employee theft
- Funds transfer
- Social engineering
- Check fraud
- Client funds
- Employee dishonesty
- Vendor fraud
- Cyber-enabled theft

### Environmental Risk

Evaluate:

- Fuel
- Chemicals
- Waste
- Hazardous materials
- Transportation
- Storage tanks
- Jobsite pollution
- Products
- Contractors pollution
- Mold
- Water intrusion

### Product Risk

Evaluate:

- Manufacturing
- Distribution
- Importing
- Private labeling
- Component products
- Critical end use
- Product recall
- Product contamination
- Completed operations
- Contractual indemnity

### Contractual Risk

Evaluate:

- Customer contracts
- Vendor contracts
- Lease agreements
- Construction contracts
- Master service agreements
- Indemnification
- Hold harmless
- Additional insured requirements
- Primary/noncontributory requirements
- Waivers of subrogation
- Insurance limit requirements
- Limitation-of-liability provisions

---

## Step 4 — Identify Frequency and Severity Drivers

Separate:

### Frequency Risks

Losses that may occur often but may be individually smaller.

Examples:

- Minor auto accidents
- Employee strains
- Slip-and-fall claims
- Small property losses
- Routine theft

### Severity Risks

Events that could materially threaten the company.

Examples:

- Catastrophic auto loss
- Large fire
- Severe product liability claim
- Cyber extortion
- Long-term business interruption
- Serious workplace injury
- Pollution event
- Professional liability claim
- Large contractual liability event

The meeting should focus disproportionately on **severity risks**, because those are often where advisory value is greatest.

---

## Step 5 — Identify Industry Trends With Insurance Impact

Identify only trends that materially influence:

- Loss frequency
- Loss severity
- Carrier appetite
- Pricing
- Limits
- Deductibles
- Coverage availability
- Underwriting requirements
- Risk-control expectations
- Business continuity

Examples may include:

- Nuclear verdicts
- Medical inflation
- Catastrophe losses
- Replacement-cost inflation
- Social inflation
- Cyber loss trends
- Auto severity
- Construction defect trends
- Labor shortages
- Supply-chain delays
- Regulatory change
- Litigation trends

Do not include generic economic commentary unless it has a clear insurance implication.

---

## Step 6 — Estimate the Likely Insurance Program

Based on company type, size indicators, operations, and industry norms, determine the likely program structure.

Potential coverages may include:

- Commercial Property
- General Liability
- Commercial Auto
- Workers’ Compensation
- Umbrella Liability
- Excess Liability
- Cyber Liability
- Employment Practices Liability
- Directors & Officers Liability
- Errors & Omissions
- Professional Liability
- Crime
- Fiduciary Liability
- Inland Marine
- Equipment Breakdown
- Builders Risk
- Pollution Liability
- Contractors Pollution
- Product Recall
- Product Contamination
- Cargo / Transit
- Ocean Marine
- International Coverage
- Surety
- Specialty programs

Do not include every possible coverage.

For each material line:

1. Explain why it is relevant
2. Identify the primary exposure
3. Identify what must be confirmed

Separate:

### Core Program

Coverage likely fundamental to the account.

### Exposure-Dependent Coverage

Coverage that becomes relevant only if certain facts are confirmed.

---

## Step 7 — Think Like an Underwriter

Before recommending discovery questions, identify what an underwriter would likely want to understand.

Examples:

- Revenue
- Payroll
- Locations
- Building construction
- Property values
- Occupancy
- Protection class
- Sprinklers
- Driver count
- Vehicle count
- Radius
- Loss history
- Experience modification
- Safety programs
- Contracts
- Subcontractor controls
- Products
- End use
- Cyber controls
- Business continuity
- Years in business
- Management experience

Ask:

> What information could materially change carrier appetite, pricing, limits, or terms?

Prioritize those items.

---

## Step 8 — Identify Common Coverage Gaps

Identify coverage weaknesses commonly seen in this industry.

Potential issues may include:

- Underinsured property
- Inadequate business-income limits
- Inadequate restoration periods
- Missing ordinance or law
- Equipment breakdown gaps
- Utility-services gaps
- Missing contingent business interruption
- Inadequate umbrella limits
- Hired/non-owned auto gaps
- Employee personal vehicle exposure
- Contractual liability issues
- Additional insured limitations
- Professional services exclusions
- Pollution exclusions
- Product liability gaps
- Product recall gaps
- Cyber exclusions
- Social engineering limitations
- Funds-transfer fraud gaps
- EPLI gaps
- Wage-and-hour limitations
- Unscheduled equipment
- Transit gaps
- Property of others
- Foreign exposures
- Crime/fidelity limitations
- Subcontractor risk-transfer weaknesses
- Catastrophe limit inadequacy

Only include issues reasonably relevant to the business.

For each gap, explain:

### Why It Commonly Occurs

What causes the issue.

### Potential Consequence

Why it matters.

### What to Confirm

What the producer should investigate.

---

## Step 9 — Identify Operational Risks

Think beyond policy terms.

Identify operational practices that may materially influence:

- Loss frequency
- Loss severity
- Carrier appetite
- Pricing
- Insurability
- Risk-transfer effectiveness
- Coverage structure

Potential areas:

- Driver screening
- Driver training
- Fleet safety
- Telematics
- Employee safety
- Return-to-work
- Contract review
- Subcontractor controls
- Certificates
- Vendor management
- Cybersecurity
- MFA
- Backups
- Disaster recovery
- Business continuity
- Fire protection
- Equipment maintenance
- Quality control
- Product recall
- Supply-chain concentration
- Customer concentration
- Claims reporting
- Incident investigation
- HR practices

---

## Step 10 — Identify Concentration Risk

Look specifically for dependencies involving:

- One facility
- One major customer
- One supplier
- One specialized machine
- One executive
- One geographic area
- One technology provider
- One logistics provider
- One distribution center
- One revenue stream

Concentration risk is often overlooked but can materially influence business interruption and enterprise risk.

---

## Step 11 — Develop Discovery Questions

Create **no more than 10 discovery questions**.

Every question should have a purpose.

Avoid application-style questions unless they unlock meaningful insight.

Each question should help uncover at least one of:

- Material exposure
- Coverage weakness
- Operational vulnerability
- Underwriting concern
- Contractual obligation
- Risk-control weakness
- Insurance-program deficiency
- Client dissatisfaction
- Risk-financing opportunity
- Advisory opportunity

---

# Discovery Question Standard

Do not ask:

> Are you happy with your current broker?

Prefer:

> What do you wish your current insurance program or broker did better for you today?

Do not ask:

> Do you have contracts?

Prefer:

> When you enter customer or vendor agreements, who reviews the insurance and indemnification requirements before the contract is signed?

Do not ask:

> Do you have business income coverage?

Prefer:

> If your most important location were unusable tomorrow, how long would it realistically take to restore operations, replace critical equipment, and return revenue to normal?

Discovery questions should demonstrate advisory thinking.

---

## Step 12 — Sequence the Questions

Rank questions in a logical meeting order.

Recommended progression:

1. Business model
2. Major operational dependencies
3. Largest risk concern
4. Prior loss experience
5. Contractual exposure
6. Operational controls
7. Coverage/program structure
8. Broker/service experience
9. Growth/change
10. Advisory opportunity

Do not make the meeting feel like an application interview.

---

## Step 13 — Identify Wedge Opportunities

A wedge opportunity is a specific issue or service that creates value before asking the prospect to move the entire account.

Potential wedges include:

- Contractual risk-transfer review
- Business-income analysis
- Property valuation review
- Workers’ compensation benchmarking
- Experience-mod analysis
- Fleet safety assessment
- Cyber coverage review
- Cyber control assessment
- Loss-run analysis
- Claims trend analysis
- Coverage-gap review
- Umbrella adequacy review
- Loss-control review
- Certificate-management review
- Executive-risk review
- Alternative-risk-financing analysis
- Renewal timeline review
- Benchmarking
- Risk-control assessment
- P&C / Benefits cross-sell opportunity

Select **2–5 meaningful wedges**.

Do not create wedges merely to sell products.

The wedge should solve a real problem or reveal meaningful insight.

---

## Step 14 — Score Wedge Opportunities

When multiple wedges exist, prioritize each based on:

| Factor | Question |
|---|---|
| Materiality | Could this materially affect the client? |
| Urgency | Is action needed soon? |
| Evidence | Is there a reason to believe the issue exists? |
| Differentiation | Can the advisor demonstrate meaningful expertise? |
| Accessibility | Can the issue be evaluated without replacing the broker? |
| Client Value | Would solving it create obvious value? |

Use:

- High
- Medium
- Low

Avoid false numerical precision unless requested.

---

## Step 15 — Determine the Best Initial Wedge

Select one primary wedge.

Explain:

- Why this issue is likely relevant
- Why it matters to the prospect
- What information is needed
- What the producer can offer next
- Why it creates a natural second conversation

The best wedge should move the relationship forward without requiring an immediate BOR request.

---

## Step 16 — Develop the Meeting Strategy

Finish with a concise producer strategy.

Provide:

### Top 3 Risks to Explore

The three most material areas.

### Top 3 Questions to Ask First

The three highest-value questions.

### Best Initial Wedge

The strongest advisory opening.

### Potential Red Flag

The issue most likely to materially affect appetite, pricing, or coverage.

### Potential Relationship Opportunity

Something the producer can do that demonstrates value beyond price.

---

# Decision Rules

## Insurance Insight Over Generic Commentary

Do not write:

> The company faces increasing competition.

Instead write:

> If competitive pressure has increased the company's reliance on contractual guarantees or tighter delivery timelines, contractual liability and business-interruption dependencies may deserve greater attention.

Connect business conditions to risk.

---

## Severity Before Trivia

Prioritize issues that could materially impact:

- Balance sheet
- Operations
- Revenue
- Reputation
- Insurability
- Coverage
- Claims
- Client relationships

Do not overwhelm the producer with low-impact observations.

---

## Industry-Specific Over Universal

Do not fill the report with risks relevant to every company.

Prioritize what is distinctive about:

- Industry
- Operations
- Geography
- Size
- Customer base
- Contracts
- Workforce
- Products
- Technology

---

## Do Not Create Artificial Precision

Do not invent:

- Premium estimates
- Coverage limits
- Payroll
- Vehicle counts
- Employee counts
- Revenue
- Property values

unless supported.

Use ranges only when they are clearly described as industry benchmarks or scenarios.

---

## Materiality Over Volume

The producer needs the most important insights, not the longest report.

If 6 material issues exist, do not create 20 simply to fill space.

---

## Separate Facts From Judgment

Use:

### Verified

Supported by evidence.

### Inferred

Based on industry norms.

### Needs Confirmation

Requires client discovery.

---

# Output Requirements

Use the following structure unless the user asks for another format.

---

# Prospect Intelligence Brief

## Company Snapshot

**Company:** [Company Name]  
**Industry:** [Industry]  
**Primary Location:** [Location]  
**Prepared For:** First Prospect Meeting

### Business Summary

Provide a concise description of:

- What the business appears to do
- How it likely generates revenue
- Primary operating characteristics
- Geographic footprint
- Key risk characteristics

Clearly distinguish fact from inference.

---

# 1. Executive Risk Perspective

Provide a concise senior-advisor perspective answering:

- What makes this account interesting?
- What could create the largest loss?
- What could disrupt revenue?
- What should the producer understand before the meeting?
- What appears most worthy of discovery?

Limit this section to the highest-value observations.

---

# 2. Industry & Risk Overview

Cover:

- Major loss drivers
- Severity risks
- Frequency risks
- Emerging risks
- Current underwriting concerns
- Operational characteristics affecting insurance
- Relevant industry trends with insurance implications

Avoid generic commentary.

---

# 3. Exposure Map

Use a table.

| Exposure | Relevance | Why It Matters | Confidence | Confirm During Discovery |
|---|---|---|---|---|
| Property | High / Medium / Low | [Explanation] | High / Moderate / Low | [What to confirm] |
| Business Income | High / Medium / Low | [Explanation] | High / Moderate / Low | [What to confirm] |
| General Liability | High / Medium / Low | [Explanation] | High / Moderate / Low | [What to confirm] |

Include only relevant categories.

---

# 4. Likely Insurance Program Structure

Separate:

## Core Program

| Coverage | Likely Relevance | Primary Exposure | What to Confirm |
|---|---|---|---|
| [Coverage] | High / Medium | [Exposure] | [Discovery item] |

## Exposure-Dependent Coverage

| Coverage | Trigger | Why It May Matter | Confirmation Needed |
|---|---|---|---|

Do not imply that these coverages are currently purchased.

---

# 5. Common Coverage Gaps

For each material issue:

## [Potential Coverage Gap]

**Why it commonly occurs:**  
[Explanation]

**Potential consequence:**  
[Explanation]

**What to confirm:**  
[Discovery item]

**Confidence:**  
High / Moderate / Low

---

# 6. Operational Risks to Explore

Use a table where useful.

| Operational Risk | Insurance Impact | What to Explore |
|---|---|---|
| [Risk] | [Impact] | [Discovery] |

Focus on operational issues capable of affecting claims, pricing, or coverage.

---

# 7. Underwriter's Likely Questions

Provide up to 8 questions an experienced underwriter would likely want answered.

This section helps the producer anticipate future submission requirements.

---

# 8. Discovery Questions for the Prospect

Provide **no more than 10** high-value questions.

Rank in recommended meeting order.

For each question, optionally identify the reason:

| # | Discovery Question | What It May Reveal |
|---|---|---|

Questions should create conversation, not interrogate the prospect.

---

# 9. Potential Wedge Opportunities

Identify 2–5.

For each:

## [Wedge Opportunity]

**Potential issue:**  
[Explanation]

**Why it matters:**  
[Explanation]

**Why this is a good wedge:**  
[Explanation]

**Suggested next step:**  
[Action]

**Priority:**  
High / Medium / Low

---

# 10. Meeting Strategy

## Top 3 Risks to Explore

1. [Risk]
2. [Risk]
3. [Risk]

## Top 3 Questions to Ask First

1. [Question]
2. [Question]
3. [Question]

## Best Initial Wedge

**[Wedge]**

Explain why.

## Potential Underwriting Red Flag

**[Issue]**

Explain what should be clarified.

## Potential Relationship Opportunity

**[Opportunity]**

Explain how the producer can demonstrate advisory value.

---

# 11. Assumptions & Items Requiring Confirmation

This section is mandatory whenever the brief contains inference.

List:

- Assumption
- Why it was made
- Confidence level
- What would confirm it

Example:

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| Employees may use personal vehicles | Common in this industry | Moderate | Ask about employee driving |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Company name is correct
- [ ] Industry is correct
- [ ] Location is correct
- [ ] Company-specific facts are supported
- [ ] Inferences are clearly labeled
- [ ] No fabricated company facts are included
- [ ] Industry commentary is insurance-specific
- [ ] Major severity risks are prioritized
- [ ] Frequency and severity are distinguished where useful
- [ ] Likely program structure fits the business
- [ ] Coverage gaps are relevant to the industry
- [ ] Operational risks connect to insurance outcomes
- [ ] Underwriter questions are practical
- [ ] Discovery questions create advisory value
- [ ] No more than 10 prospect discovery questions are included
- [ ] Wedge opportunities are actionable
- [ ] Wedges solve real problems rather than simply sell products
- [ ] Meeting priorities are clearly identified
- [ ] The best initial wedge is selected
- [ ] Material assumptions are disclosed
- [ ] Unknown information remains unknown
- [ ] No binding or coverage guarantees are made
- [ ] The final output prioritizes insight over volume

---

# Failure Conditions

The Skill should not be considered complete if:

- The company cannot be reasonably identified
- Required inputs are missing
- The output relies primarily on generic industry commentary
- Inferred information is presented as verified
- Discovery questions are generic or application-driven
- Wedge opportunities are merely product sales opportunities
- Major severity exposures are ignored
- Material assumptions are not disclosed
- The analysis provides unsupported coverage conclusions

If any failure condition exists, correct it before finalizing.

---

# Guardrails

## Do Not Fabricate Company Facts

Never invent:

- Revenue
- Employee count
- Payroll
- Locations
- Vehicle count
- Property values
- Loss history
- Current insurance carrier
- Premium
- Limits
- Claims
- Ownership structure
- Contracts
- Safety history
- Cyber controls

unless supported by credible information.

---

## Industry Inference Is Allowed

Industry-based professional inference is permitted.

However, always distinguish it from verified facts.

Appropriate language includes:

- “Companies of this type commonly...”
- “A likely exposure is...”
- “This may be relevant if...”
- “Worth confirming during discovery...”
- “Based on industry norms...”

---

## Do Not Provide Coverage Guarantees

Never state that:

- A claim is covered
- A claim is excluded
- A policy definitely provides coverage
- A carrier will accept the account
- A particular limit is adequate
- A coverage form will respond

without reviewing the relevant policy, underwriting information, and applicable terms.

---

## Do Not Bind Coverage

This Skill cannot:

- Bind insurance
- Alter coverage
- Issue policies
- Confirm carrier acceptance
- Change limits
- Confirm underwriting approval
- Authorize coverage

---

## No Legal Advice

Legal or contractual issues may be identified.

Do not provide legal conclusions.

When appropriate, recommend review by qualified legal counsel.

---

## Regulatory Awareness

If a state, industry, or business activity appears highly regulated:

- Identify regulation as a discovery consideration
- Do not make unsupported regulatory conclusions
- Recommend appropriate compliance review

---

## Protect Confidential Information

Use only information necessary for the requested analysis.

Do not unnecessarily expose:

- Personally identifiable information
- Credentials
- Financial account information
- Confidential client records
- Health information
- Proprietary agency information
- Sensitive company information

---

## Preserve Human Accountability

The AI supports the insurance professional.

The producer, advisor, account executive, carrier, client, or other authorized professional remains responsible for:

- Final judgment
- Coverage recommendations
- Client communication
- Carrier strategy
- Submission accuracy
- Compliance
- Binding decisions

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced commercial insurance advisor.

The tone should be:

- Practical
- Commercially aware
- Insurance-specific
- Concise
- Curious
- Analytical
- Client-centered
- Non-alarmist

Avoid:

- Generic risk-management clichés
- Excessive jargon
- Fear-based selling
- Product dumping
- Unsupported certainty
- Long lists without prioritization

---

# Example

## Example Request

```text
Company Name: Summit Precision Fabrication
Industry: Metal Fabrication
Location: Reno, Nevada
```

---

## Example Output Excerpt

### Executive Risk Perspective

Summit Precision Fabrication likely presents a combination of property, workers’ compensation, products/completed operations, equipment, contractual, and business-interruption exposures.

The most important first-meeting issue may not be routine general liability. If the company manufactures components used in mission-critical or high-severity applications, product failure could create significant downstream property damage, bodily injury, or customer production losses.

Critical equipment dependency and replacement lead times may also create a meaningful business-income exposure if operations rely on specialized machinery.

Both issues should be confirmed early.

---

### Exposure Map

| Exposure | Relevance | Why It Matters | Confidence | Confirm During Discovery |
|---|---|---|---|---|
| Property | High | Specialized machinery and fabrication equipment may create substantial replacement exposure | Moderate | Equipment values, building ownership, fire protection |
| Business Income | High | Long equipment replacement lead times could extend restoration | Moderate | Critical machines, lead times, alternate facilities |
| Workers' Compensation | High | Welding, fabrication, lifting, machinery, and material handling can create frequency and severity | High | Payroll, class codes, safety program, loss history |
| Products Liability | High | Severity depends heavily on end use of fabricated components | Moderate | Product end use, customer contracts, quality control |

---

### Discovery Question

> What are the most critical end uses for the components you manufacture, and are any used in applications where a component failure could cause significant bodily injury, property damage, or production interruption?

**What it may reveal:**  
Potential products/completed-operations severity, contractual obligations, quality-control requirements, umbrella/excess needs, and whether specialized product liability treatment may be warranted.

---

### Potential Wedge

## Contractual Risk Transfer Review

**Potential issue:**  
Manufacturers and fabricators frequently sign customer agreements containing indemnification and insurance requirements that may create obligations broader than assumed.

**Why it matters:**  
Additional insured wording, waiver-of-subrogation requirements, contractual liability, product responsibility, and required limits can materially affect the insurance program.

**Why this is a good wedge:**  
The producer can create value by reviewing representative contracts without requiring the prospect to immediately replace the incumbent broker.

**Suggested next step:**  
Request two or three representative customer agreements and compare their insurance requirements against the current liability and umbrella structure.

**Priority:**  
High

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a senior commercial insurance advisor preparing for a new prospect meeting. Your objective is to quickly develop a structured, underwriter-level understanding of the business so the producer can lead a high-value conversation and identify meaningful advisory opportunities.
>
> Analyze the company below and generate a practical, real-world prospect intelligence brief using insurance-specific insight—not generic commentary. Where information is limited, infer likely exposures and program structure based on industry norms.
>
> Company Name: [INSERT]  
> Industry: [INSERT]  
> Location: [INSERT]
>
> Think like an experienced advisor preparing for a first meeting with a mid-market client. Focus on how the business operates, where risk exists, and where coverage often falls short.
>
> Structure your response as follows:
>
> - Industry overview highlighting key risks, trends, and operational exposures
> - Likely insurance program structure for a company of this type and size
> - Common coverage gaps specific to this industry
> - Operational risks that should be explored during the conversation
> - Up to 10 high-quality discovery questions designed to uncover risk and opportunity
> - Potential “wedge” opportunities where advisory value can be introduced early
>
> Use practical insurance language. Avoid broad generalizations. Prioritize insight over volume.

---

# Evolution From Prompt to Skill

The original prompt established the desired outcome.

This Skill expands that prompt into a repeatable insurance workflow by adding:

- Required inputs
- Recommended inputs
- Optional intelligence sources
- Research standards
- Source hierarchy
- Evidence classification
- Confidence classification
- Exposure mapping
- Frequency/severity analysis
- Underwriter perspective
- Coverage-gap logic
- Operational risk analysis
- Concentration-risk review
- Discovery-question standards
- Question sequencing
- Wedge identification
- Wedge scoring
- Meeting strategy
- Output requirements
- Quality controls
- Failure conditions
- Guardrails
- Human accountability
- Example implementation
- Version history

The purpose is to transform a useful prompt into a reusable insurance capability.

---

# Related Skills

Future related Apeironix Skills may include:

- Commercial Policy Comparison
- Commercial Renewal Preparation
- Commercial Submission Preparation
- Coverage Gap Analysis
- Loss Run Analysis
- Risk Discovery Questionnaire
- Client Meeting Preparation
- Contractual Risk Transfer Review
- Business Income Analysis
- Workers’ Compensation Benchmarking

Links will be added as those Skills are published.

---

# Suggested Invocation

A user may invoke this Skill with:

```text
Prepare a Commercial Prospect Intelligence Brief.

Company Name: [COMPANY]
Industry: [INDUSTRY]
Location: [LOCATION]
Website: [OPTIONAL]
Known Revenue: [OPTIONAL]
Employee Count: [OPTIONAL]
Additional Context: [OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Company Name: [COMPANY]
Industry: [INDUSTRY]
Location: [LOCATION]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #1 include:

- Structured prospect research workflow
- Verified fact vs. inference framework
- Confidence classification
- Source hierarchy
- Exposure architecture
- Frequency and severity analysis
- Underwriter-question framework
- Coverage-gap framework
- Operational-risk analysis
- Concentration-risk analysis
- Discovery-question standards
- Wedge-opportunity framework
- Wedge prioritization
- Meeting-strategy framework
- Quality-control checklist
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
