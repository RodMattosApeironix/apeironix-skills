---
name: underwriter-submission-email
title: Commercial Insurance Underwriter Submission Email
collection: ai-insurance-automation-guide
prompt_number: 7
category: commercial-pc
capability: submission-intelligence
primary_role: commercial-insurance-broker
secondary_roles:
  - commercial-insurance-producer
  - commercial-account-executive
  - commercial-account-manager
  - placement-specialist
  - marketing-specialist
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Underwriter Submission Email

## Purpose

Transform account information into a concise, underwriter-friendly submission email that helps the risk get understood quickly, highlights why the account deserves attention, addresses likely underwriting concerns, and creates a clear path toward quotation.

This Skill is designed to help the insurance professional:

- Position the account immediately
- Present the risk through an underwriter’s lens
- Highlight favorable attributes without overselling
- Make loss history and risk controls easy to understand
- Surface operational stability and management quality
- Anticipate likely underwriting questions
- Address material concerns proactively
- Clarify the requested coverage structure
- Communicate timing and urgency professionally
- Reduce back-and-forth caused by incomplete or poorly organized submissions

The objective is **not** to write a generic “please quote” email.

The objective is to create a concise broker-to-underwriter narrative that makes the risk easier to evaluate and gives the underwriter a reason to engage.

---

# Core Outcome

A successful use of this Skill should allow an underwriter to understand within a few minutes:

- What the company does
- Why the account is being submitted
- What makes the risk attractive
- What exposures matter most
- What the recent loss experience looks like
- What controls are in place
- Whether there are material underwriting concerns
- What coverage is being requested
- What timing applies
- What action the broker is requesting

The submission should reduce underwriting friction, not create more of it.

---

# Best Used For

Use this Skill when preparing:

- A new-business submission email
- A renewal remarketing submission
- A selective market submission
- An incumbent replacement strategy
- A wholesale submission
- A specialty-market submission
- A program-market submission
- A difficult-risk submission
- A submission following improved loss control
- A submission requiring proactive explanation of prior losses
- A time-sensitive market approach
- A cross-line commercial placement
- A mid-market commercial account submission

This Skill is especially useful when the submission includes enough facts to tell a credible risk story but needs better positioning.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A complete underwriting application
- ACORD forms
- Supplemental applications
- Loss runs
- Statements of values
- Driver schedules
- Payroll schedules
- Exposure schedules
- Financial statements
- Carrier-required documentation
- A formal underwriting narrative where one is separately required
- Binding authority
- Carrier appetite confirmation
- Coverage confirmation

This is a **submission positioning and underwriting communication Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Brokers
- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Placement Specialists
- Marketing Specialists
- Wholesale Brokers
- Practice Leaders
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. Account name and industry
2. Operations summary
3. Key exposures
4. Loss history
5. Risk controls
6. Coverage requested
7. Timeline or urgency

Recommended format:

```text
Account Details:
[CLIENT NAME + INDUSTRY]

Operations Summary:
[BRIEF DESCRIPTION]

Key Exposures:
[INSERT]

Loss History:
[INSERT SUMMARY OR "Favorable / Clean / Improving"]

Risk Controls:
[INSERT]

Coverage Requested:
[INSERT]

Timeline / Urgency:
[INSERT]
```

If any material section is missing, the Skill should identify the information gap.

Do not invent underwriting facts.

---

# Recommended Inputs

The following inputs materially improve the submission:

- Annual revenue
- Payroll
- Employee count
- Number of locations
- States of operation
- Years in business
- Ownership structure
- Management experience
- Current carrier
- Current premium
- Renewal date
- Desired effective date
- Current limits
- Desired limits
- Deductibles
- Self-insured retentions
- Vehicle count
- Fleet type
- Driver count
- Property values
- Building construction
- Protection class
- Sprinkler information
- Equipment values
- Products
- Product end use
- Subcontractor usage
- Contractual controls
- Cyber controls
- Safety programs
- Return-to-work program
- Telematics
- Claims management practices
- Loss-control improvements
- Five-year loss history
- Large-loss details
- Current open claims
- Corrective actions taken
- Reason for marketing
- Incumbent carrier position
- Target pricing or structure when appropriate
- Required quote-by date
- Broker market strategy
- Attachments included

---

# Preferred Source Documents

Where available, prioritize:

1. Current ACORD applications
2. Current supplemental applications
3. Current loss runs
4. Current exposure schedules
5. Current statement of values
6. Current vehicle / driver schedules
7. Current payroll information
8. Current policies
9. Current carrier proposal
10. Loss-control reports
11. Client-provided operational information
12. Agency Management System data
13. Producer notes
14. Prior submission information

Do not rely on prior-year submission data when current information is available.

---

# Source Hierarchy

When information conflicts, prioritize:

1. Current carrier-issued or verified underwriting documents
2. Current ACORD and supplemental applications
3. Current loss and exposure data
4. Client-confirmed information
5. Agency-verified information
6. Current policy information
7. Prior-year submission information
8. Producer observations
9. Industry norms and reasonable inference

When sources conflict:

- Identify the discrepancy
- Do not silently choose one
- Use the most current and authoritative source
- Flag material conflicts before finalizing the submission

---

# Evidence Classification

Every material statement should be treated as one of the following.

## Verified Underwriting Fact

Directly supported by current documentation.

Example:

> The insured operates 28 owned vehicles.

---

## Client-Confirmed Operational Fact

Confirmed directly by the insured.

Example:

> Management implemented telematics across the fleet in 2025.

---

## Broker Observation

A professional interpretation based on the account.

Example:

> Management appears highly engaged in loss control.

Use cautiously and support with specifics where possible.

---

## Reasonable Underwriting Inference

A likely conclusion based on the available facts.

Example:

> The recent loss trend suggests that the implemented fleet controls may be having a positive impact.

Do not present inference as certainty.

---

## Requires Underwriter Confirmation

An issue dependent on carrier appetite, form availability, pricing, or underwriting judgment.

Example:

> The requested $10 million umbrella structure remains subject to market capacity and attachment requirements.

---

# Confidence Classification

Where useful, classify material conclusions:

### High Confidence

Supported by current documentation or direct client confirmation.

### Moderate Confidence

Supported by multiple indicators but not fully verified.

### Low Confidence

Possible but requires meaningful confirmation.

Avoid unsupported certainty.

---

# Core Principle

## Think Like the Underwriter Before Writing Like the Broker

Before drafting the email, ask:

> If I were reviewing this submission among dozens of others, what would I need to understand quickly to decide whether to engage?

The submission should answer that question.

The broker’s job is not to make the account sound perfect.

The broker’s job is to make the account:

- Understandable
- Credible
- Organized
- Professionally positioned
- Easy to evaluate

---

# Workflow

Follow the workflow in order unless the circumstances clearly require another sequence.

---

## Step 1 — Establish the Account Profile

Identify:

- Company
- Industry
- Primary operations
- Years in business
- Revenue
- Payroll
- Employees
- Locations
- Geographic footprint
- Ownership
- Management structure
- Major products or services
- Major customer types

Summarize only what an underwriter needs to understand the risk.

---

## Step 2 — Identify the Underwriting Decision

Determine what the underwriter is actually being asked to evaluate.

Examples:

- New business
- Renewal replacement
- Property placement
- General liability
- Auto
- Workers’ compensation
- Umbrella
- Package
- Multi-line program
- Specialty line
- Excess layer
- Cyber
- Professional liability

The email should make the requested decision immediately clear.

---

## Step 3 — Identify What Matters Most for This Risk

Different industries create different underwriting priorities.

Potential factors include:

- Loss history
- Vehicle severity
- Driver controls
- Property protection
- Catastrophe exposure
- Product end use
- Contractual controls
- Safety program
- Payroll mix
- Subcontractor controls
- Management quality
- Cybersecurity
- Financial strength
- Claims management
- Business continuity
- Years in business
- Operational stability

Do not use the same risk story for every account.

---

## Step 4 — Identify the Risk's Strengths

Select 3–4 meaningful strengths.

Examples:

- Favorable loss history
- Improving loss trend
- Stable management
- Long operating history
- Strong safety controls
- Telematics
- Formal driver standards
- Documented return-to-work program
- Strong contractual risk transfer
- Modern facilities
- Sprinkler protection
- Diversified customer base
- Strong financials
- Experienced ownership
- Low employee turnover
- Robust cyber controls
- Effective quality control

Each strength should be specific.

Weak:

> Great account.

Better:

> Five years of stable ownership, favorable loss performance, and formal fleet controls implemented across all company vehicles.

---

## Step 5 — Review Loss History

Identify:

- Years reviewed
- Total claims
- Frequency
- Severity
- Open claims
- Large losses
- Recent trend
- Loss-free years
- Corrective action following losses
- Claim closure progress

Avoid vague claims such as:

> Losses are good.

Prefer:

> Five-year loss history is favorable, with no individual loss exceeding $75,000 and no open claims.

If loss history is imperfect, do not hide it.

---

## Step 6 — Develop the Loss Story

When losses exist, explain:

1. What happened
2. Whether the issue was isolated or systemic
3. What corrective action was taken
4. What has happened since
5. Why the underwriter should view the current risk differently, if supported

Example:

> Two large auto claims occurred in 2024. Following those losses, management implemented telematics, tightened MVR standards, and formalized driver coaching. The account has had no new auto claims in the past 12 months.

Do not minimize legitimate loss concerns.

---

# Loss Narrative Standard

A strong loss narrative should be:

- Factual
- Concise
- Accountable
- Corrective
- Forward-looking

Avoid:

- Blaming claimants
- Dismissing losses
- Calling losses "bad luck" without support
- Overstating improvement
- Hiding open claims

---

## Step 7 — Identify Risk Controls

Highlight controls directly connected to the exposure.

Potential controls include:

### Fleet

- MVR standards
- Telematics
- Driver training
- Driver monitoring
- Vehicle maintenance
- Distracted-driving policy
- Accident review

### Workers’ Compensation

- Safety meetings
- PPE
- Return-to-work program
- Supervisor training
- Incident investigation
- Ergonomic controls

### Property

- Sprinklers
- Central station alarms
- Hot-work permits
- Fire suppression
- Preventive maintenance
- Equipment inspection
- Catastrophe preparation

### Liability

- Contract review
- Certificates
- Additional insured requirements
- Subcontractor controls
- Quality assurance

### Cyber

- MFA
- EDR
- Backups
- Employee training
- Incident-response plan
- Vendor controls

Focus on controls the underwriter will care about.

---

## Step 8 — Evaluate Operational Stability

Identify factors such as:

- Years in business
- Ownership continuity
- Management tenure
- Stable operations
- Stable employee base
- Financial strength
- Customer diversification
- Consistent growth
- Controlled expansion
- Established processes
- Experienced safety leadership

Do not make unsupported claims about management quality.

Show the evidence behind the conclusion.

---

## Step 9 — Identify Underwriting Concerns

Before drafting, identify likely concerns.

Examples:

- Large prior loss
- Rapid growth
- New operation
- Fleet size
- High-hazard work
- Catastrophe location
- Product severity
- Subcontractor usage
- Cyber controls
- Poor loss trend
- High experience modification
- Open claims
- Property valuation
- Business-income exposure
- Financial instability

Do not ignore an obvious concern.

---

## Step 10 — Address Concerns Proactively

For each material concern, determine whether the submission should include:

- Clarification
- Corrective action
- Updated information
- Supporting documentation
- Context
- Risk-control evidence
- Loss explanation

Example:

> The account's experience modification increased following two prior claims; however, both claims are now closed and management has implemented a formal return-to-work program.

Only include supportable statements.

---

## Step 11 — Establish the Market Positioning

Determine the central positioning statement.

Examples:

> Established regional distributor with favorable five-year losses and strong fleet controls.

> Experienced contractor with stable operations, improving workers’ compensation performance, and formal subcontractor risk-transfer procedures.

> Well-managed manufacturer with strong quality controls and limited product-loss activity.

This should become the core of the opening.

---

## Step 12 — Clarify the Coverage Request

State exactly what is requested.

Examples:

- Package
- General Liability
- Commercial Auto
- Workers’ Compensation
- Umbrella
- Property
- Inland Marine
- Cyber
- Professional Liability
- Specific excess layer

Include where known:

- Limits
- Deductibles
- Retentions
- Effective date
- Structure

Avoid forcing the underwriter to search attachments to understand the basic request.

---

## Step 13 — Identify Submission Completeness

Before finalizing, verify whether key materials are attached.

Potential attachments:

- ACORD applications
- Supplemental applications
- Loss runs
- Statement of values
- Vehicle schedule
- Driver schedule
- Payroll
- Experience modification
- Financials
- Loss-control reports
- Coverage specifications

If material documents are missing, disclose what is pending.

Example:

> Updated driver schedule is expected tomorrow and will follow separately.

Do not imply the submission is complete when it is not.

---

# Submission Readiness Classification

When useful, classify:

### Market Ready

Core underwriting information is available and the account can reasonably be evaluated.

### Conditionally Ready

Submission can be reviewed, but one or more material items remain outstanding.

### Not Ready

Critical underwriting information is missing.

Do not encourage premature market submission when missing data will materially reduce credibility.

---

## Step 14 — Determine Timeline

Identify:

- Effective date
- Renewal date
- Desired quote date
- Client decision date
- Any urgent operational reason

Be specific.

Weak:

> Need ASAP.

Better:

> Renewal is October 1, and we are targeting initial terms by September 10 to allow sufficient time for client review.

---

## Step 15 — Draft the Subject Line

The subject should help the underwriter understand:

- Account
- Line
- Effective date
- Attractive characteristic where appropriate

Examples:

> New Business Submission — Western Industrial Services — GL/Auto/Umbrella — 12/1

> 10/1 Renewal Opportunity — Regional Food Distributor — Favorable Loss Trend

Avoid gimmicks.

---

## Step 16 — Draft the Opening

The opening should immediately establish:

- What the account is
- What is being requested
- Why it deserves attention

Example:

> I'm sending Western Industrial Services for consideration on its December 1 GL, Auto, and Umbrella program. This is an established industrial contractor with stable ownership, improving auto loss performance, and meaningful fleet controls implemented over the past 18 months.

The underwriter should understand the account immediately.

---

## Step 17 — Build the Attractive-Risk Bullets

Provide 3–4 concise bullets.

Potential topics:

- Loss performance
- Risk controls
- Management
- Operational stability
- Financial strength
- Account tenure
- Exposure characteristics
- Corrective action

Use facts, not adjectives.

---

## Step 18 — Present Key Underwriting Highlights

Summarize the most important underwriting information.

Where useful, include:

- Revenue
- Payroll
- Vehicle count
- Locations
- Loss trend
- Experience modification
- Property values
- Risk controls
- Large-loss explanation
- Operational changes

Do not duplicate the entire application.

---

## Step 19 — Present Coverage Request

State:

- Lines requested
- Limits
- Deductibles
- Structure
- Effective date
- Any desired alternatives

Example:

> We are requesting GL, Auto, and $5M Umbrella effective December 1. Please also provide a $10M umbrella alternative if available.

---

## Step 20 — State Timeline and CTA

End with a clear request.

Examples:

> Please let me know by Friday whether this fits your appetite and whether you need anything further to begin review.

or:

> We are targeting terms by September 10. If the account fits your appetite, please confirm interest and any additional underwriting requirements.

The CTA should be easy to answer.

---

# Underwriter Readability Standard

The email should be optimized for scanning.

Use:

- Short paragraphs
- 3–4 bullets
- Clear labels
- Specific facts
- Direct coverage request
- Clear deadline

Avoid:

- Long narrative blocks
- Excessive attachments without explanation
- Marketing language
- Unnecessary client history
- Repeating ACORD data
- Unsupported adjectives

---

# Decision Rules

## Relevance Before Completeness

The email does not need to repeat every underwriting fact.

It should surface the facts most relevant to deciding whether to engage.

---

## Facts Before Adjectives

Avoid:

> Excellent management.

Prefer:

> Same ownership for 18 years with dedicated safety and operations leadership.

---

## Address the Obvious Concern

If the underwriter will immediately notice a major loss, large fleet, high-hazard operation, or catastrophe exposure, address it directly.

Do not hope it is overlooked.

---

## Do Not Oversell

The goal is credibility.

Avoid:

- Best-in-class
- Incredible account
- Perfect risk
- No concerns
- Easy account

unless those statements are objectively supportable, which is uncommon.

---

## Loss Improvement Requires Evidence

Do not say losses are improving unless the available loss information supports that conclusion.

---

## Do Not Manufacture Urgency

Use actual deadlines.

Do not create artificial pressure.

---

## Underwriter Time Matters

Every paragraph should help the underwriter:

- Understand
- Evaluate
- Decide
- Request information
- Quote

If it does none of these, consider removing it.

---

# Materiality / Prioritization Framework

Prioritize submission content using:

| Factor | Question |
|---|---|
| Underwriting Impact | Could this change appetite or pricing? |
| Severity | Could the exposure create a major loss? |
| Loss Relevance | Does history materially affect the risk? |
| Control Strength | Does the insured mitigate the exposure? |
| Operational Stability | Does the business appear well managed and stable? |
| Data Quality | Is the information reliable and current? |
| Submission Friction | Will this prevent or delay review? |
| Timing | Does the underwriter need to act by a specific date? |

Use professional judgment.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Underwriter Submission Package

## Submission Readiness

**Status:** Market Ready / Conditionally Ready / Not Ready

### Material Information Gaps

- [If any]

---

# 1. Underwriter Positioning Summary

Before the email, provide a concise internal summary:

### Primary Positioning

[One sentence]

### Strongest Underwriting Attributes

1. [Attribute]
2. [Attribute]
3. [Attribute]

### Primary Underwriting Concern

[Concern]

### How It Is Addressed

[Explanation]

This section is internal and should not be included in the email unless useful.

---

# 2. Suggested Subject Line

Provide one primary subject line.

Optionally provide up to 2 alternatives.

---

# 3. Submission Email

Draft the complete underwriter-ready email.

Recommended structure:

### Opening

Immediately position the account.

### Why This Risk Deserves Consideration

3–4 concise bullets.

### Key Underwriting Highlights

Relevant facts, loss trends, and controls.

### Coverage Request

Requested lines, limits, structure, effective date.

### Timeline / CTA

Clear request and deadline.

---

# 4. Underwriter Questions to Anticipate

Provide up to 5 likely underwriting questions when useful.

| Likely Question | Why It Matters | Recommended Response / Information Needed |
|---|---|---|

This helps the broker prepare before the underwriter responds.

---

# 5. Outstanding Submission Items

List any missing materials.

| Item | Owner | Status | Impact |
|---|---|---|---|
| [Item] | [Broker / Client] | Pending | [Impact] |

Omit if submission is complete.

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Correct account and industry are identified
- [ ] Requested coverage is clear
- [ ] Effective date or renewal date is clear
- [ ] Risk positioning is industry-specific
- [ ] 3–4 meaningful strengths are highlighted
- [ ] Strengths are supported by facts
- [ ] Loss history is accurately represented
- [ ] Material losses are not hidden
- [ ] Corrective actions are described when supported
- [ ] Risk controls are exposure-specific
- [ ] Operational stability is supported by evidence
- [ ] Obvious underwriting concerns are addressed
- [ ] Missing submission information is disclosed
- [ ] Submission readiness is realistic
- [ ] Email is concise and easy to scan
- [ ] Coverage request does not require searching attachments
- [ ] Timeline is specific
- [ ] CTA is clear
- [ ] No carrier appetite or pricing outcome is guaranteed
- [ ] No underwriting facts are invented
- [ ] Internal sales language is excluded
- [ ] Tone is confident broker-to-underwriter communication

---

# Failure Conditions

The Skill should not be considered complete if:

- The email is a generic “please quote” request
- The account is not positioned immediately
- The email repeats application data without interpretation
- Strengths are vague or unsupported
- A material loss is ignored
- Loss improvement is claimed without evidence
- Material underwriting concerns are hidden
- Risk controls are generic
- Coverage request is unclear
- Submission completeness is misrepresented
- Timeline is vague
- No clear CTA exists
- The email is excessively long
- Promotional language reduces credibility
- Facts are invented

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Underwriting Information

Never invent:

- Revenue
- Payroll
- Employee count
- Vehicle count
- Losses
- Claim status
- Experience modification
- Property values
- Management tenure
- Risk controls
- Coverage
- Limits
- Carrier
- Premium
- Financial condition
- Safety results

---

## Do Not Misrepresent Loss History

Never:

- Hide material losses
- Describe an account as clean when losses exist
- Call losses isolated without support
- Claim improvement without supporting data
- Misstate open vs. closed claims

---

## Do Not Misrepresent Risk Controls

A control should be described as implemented only when supported.

If planned but not completed, say so.

Example:

> Management plans to implement telematics before renewal.

is materially different from:

> Telematics is in place across the fleet.

---

## Do Not Guarantee Carrier Appetite

Never state:

- The carrier will quote
- The carrier will accept the risk
- The account fits appetite definitively
- Pricing will be competitive
- Capacity will be available

Carrier decisions remain subject to underwriting.

---

## Do Not Misrepresent Submission Completeness

If material items are missing, identify them.

Do not describe a submission as complete when required information remains outstanding.

---

## Protect Confidential Information

Include only information appropriate for the intended underwriter.

Do not unnecessarily expose:

- Personally identifiable information
- Sensitive employee information
- Claimant details beyond what is necessary
- Bank information
- Credentials
- Confidential internal agency strategy
- Other unnecessary sensitive data

---

## No Legal Advice

Contractual or regulatory issues may be identified.

Do not provide unsupported legal conclusions.

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized broker or producer remains responsible for:

- Submission accuracy
- Market selection
- Carrier communication
- Coverage specifications
- Loss representation
- Client authorization
- Compliance
- Binding instructions
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced broker communicating with an experienced underwriter.

The tone should be:

- Concise
- Credible
- Confident
- Direct
- Professional
- Underwriter-aware
- Fact-based
- Respectful of time

Avoid:

- Marketing hype
- Excessive adjectives
- Long introductions
- Generic filler
- Sales clichés
- Artificial urgency
- Defensive explanations
- Attempts to conceal risk
- Unnecessary technical jargon

The goal is to make the underwriter want to evaluate the risk, not feel sold to.

---

# Example

## Example Request

```text
Account Details:
Western Industrial Services — Industrial Contractor

Operations Summary:
Regional industrial maintenance contractor serving manufacturing and mining clients across Nevada and Northern California. In business 18 years.

Key Exposures:
28 commercial vehicles
Field employees working at customer locations
Industrial maintenance operations
$24M annual revenue

Loss History:
Two large auto claims in 2024.
No new auto claims in the past 12 months.
Other lines favorable.

Risk Controls:
Telematics installed across fleet
Tightened MVR standards
Quarterly driver training
Formal accident review process

Coverage Requested:
General Liability
Commercial Auto
Workers' Compensation
$5M Umbrella

Timeline / Urgency:
12/1 effective date
Targeting terms by 11/1
```

---

## Example Output

### Submission Readiness

**Status:** Market Ready

### Primary Positioning

Established industrial contractor with stable management, improving auto loss performance, and meaningful corrective fleet controls implemented following prior losses.

---

### Suggested Subject Line

12/1 New Business Submission — Western Industrial Services — GL / Auto / WC / $5M Umbrella

---

### Submission Email

Hi [Underwriter Name],

I'd like to submit Western Industrial Services for consideration on its December 1 GL, Auto, Workers' Compensation, and $5 million Umbrella program.

Western is an established industrial maintenance contractor with 18 years in business, approximately $24 million in annual revenue, and operations across Nevada and Northern California. The account has stable management and has made meaningful improvements to its fleet controls following two prior auto losses.

A few highlights:

- **Improving auto performance:** Two significant auto losses occurred in 2024, with no new auto claims reported during the past 12 months.
- **Stronger fleet controls:** Telematics is now installed across all 28 company vehicles, supported by tighter MVR standards, quarterly driver training, and a formal accident-review process.
- **Stable operations:** The company has an 18-year operating history and established relationships with manufacturing and mining clients.
- **Favorable performance outside auto:** Other major coverage lines have produced favorable loss experience based on the information provided.

We are requesting consideration for:

- General Liability
- Commercial Auto
- Workers' Compensation
- $5 million Umbrella

The effective date is December 1, and we are targeting initial terms by November 1 to allow time for client review and final negotiations.

The submission materials are attached. Please let me know whether this fits your appetite and if there is anything additional you need to begin your review.

Thank you,

[Broker Name]

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a senior commercial insurance broker preparing a submission email to an underwriter. Your objective is to position this account so it is quickly understood, viewed as desirable, and prioritized for quoting.
>
> Before drafting the email, think like an underwriter reviewing multiple submissions. Identify what matters most for this type of risk—such as loss history, operational stability, management quality, and exposure profile—and ensure those elements are clearly emphasized.
>
> Use the information below to create a concise, high-impact submission that reduces friction and makes it easy to evaluate quickly.
>
> Account Details:
> [INSERT CLIENT NAME + INDUSTRY]
>
> Operations Summary:
> [INSERT BRIEF DESCRIPTION]
>
> Key Exposures:
> [INSERT]
>
> Loss History:
> [INSERT SUMMARY OR “Favorable / Clean / Improving”]
>
> Risk Controls:
> [INSERT]
>
> Coverage Requested:
> [INSERT]
>
> Timeline / Urgency:
> [INSERT]
>
> Write an email that an underwriter would want to open, read, and respond to.
>
> Structure the email as:
>
> - A compelling, professional subject line
> - A clear opening that positions the account immediately
> - 3–4 concise bullets explaining why this is an attractive risk
> - Key underwriting highlights (loss trends, controls, operational stability)
> - Coverage request and structure
> - Timeline and clear call to action
>
> Keep the email tight and underwriter-friendly. Avoid filler language. Anticipate concerns and address them proactively. Use confident, broker-to-underwriter communication.

---

# Evolution From Prompt to Skill

The original prompt established the objective of creating a concise, high-impact underwriter submission email.

This Skill expands that prompt into a repeatable Submission Intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Preferred source documents
- Source hierarchy
- Evidence classification
- Confidence classification
- Underwriting-decision analysis
- Industry-specific underwriting priorities
- Risk-strength identification
- Loss-history analysis
- Loss Narrative Standard
- Risk-control framework
- Operational-stability analysis
- Underwriting-concern identification
- Proactive concern management
- Market positioning
- Coverage-request standard
- Submission completeness review
- Submission Readiness Classification
- Timeline standard
- Subject-line framework
- Underwriter readability standard
- Anticipated underwriting questions
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a submission-writing prompt into a reusable **Submission Intelligence Skill**.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Prospect Intelligence Brief](../01-prospect-intelligence-brief/SKILL.md)
- [Commercial Insurance Meeting Strategy Builder](../02-meeting-strategy-builder/SKILL.md)
- [Commercial Insurance Coverage Gap Analysis](../03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Renewal Strategy Builder](../04-renewal-strategy-builder/SKILL.md)
- [Commercial Insurance Post-Meeting Follow-Up](../05-post-meeting-follow-up/SKILL.md)
- [Commercial Insurance Executive Proposal Summary](../06-executive-proposal-summary/SKILL.md)
- Commercial Submission Preparation
- Loss Run Analysis
- Underwriting Narrative Builder
- Market Selection Strategy
- Carrier Appetite Analysis

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Draft a Commercial Insurance Underwriter Submission Email.

Account Details:
[CLIENT NAME + INDUSTRY]

Operations Summary:
[DESCRIPTION]

Key Exposures:
[EXPOSURES]

Loss History:
[LOSS SUMMARY]

Risk Controls:
[CONTROLS]

Coverage Requested:
[COVERAGE]

Timeline / Urgency:
[TIMELINE]

Additional Underwriting Context:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Account Details:
[CLIENT NAME + INDUSTRY]

Operations Summary:
[DESCRIPTION]

Key Exposures:
[EXPOSURES]

Loss History:
[LOSS SUMMARY]

Risk Controls:
[CONTROLS]

Coverage Requested:
[COVERAGE]

Timeline / Urgency:
[TIMELINE]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #7 include:

- Underwriting-decision framework
- Source hierarchy
- Evidence classification
- Risk-strength framework
- Loss-history analysis
- Loss Narrative Standard
- Risk-control analysis
- Operational-stability analysis
- Proactive underwriting-concern management
- Market-positioning framework
- Submission completeness review
- Submission Readiness Classification
- Underwriter readability standard
- Anticipated underwriting questions
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
- Submission development
- Carrier strategy
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
