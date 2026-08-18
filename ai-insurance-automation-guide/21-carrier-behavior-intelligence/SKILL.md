---
name: carrier-behavior-intelligence
title: Commercial Insurance Carrier Behavior & Placement Intelligence
collection: ai-insurance-automation-guide
prompt_number: 21
category: commercial-pc
capability: placement-intelligence
primary_role: commercial-insurance-marketing-intelligence-analyst
secondary_roles:
  - commercial-insurance-marketing-manager
  - placement-specialist
  - commercial-insurance-producer
  - commercial-account-executive
  - agency-principal
template_version: 2.2
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Carrier Behavior & Placement Intelligence

## Purpose

Capture, structure, and interpret carrier behavior from completed or active marketing efforts so the agency can improve future placement decisions for similar risks.

This Skill is designed to help the insurance professional:

- Convert carrier responses into reusable institutional knowledge
- Identify real appetite patterns
- Distinguish carrier-confirmed behavior from internal interpretation
- Identify underwriting concerns that repeatedly affect quote success
- Capture carrier strengths and deal-breakers
- Evaluate pricing competitiveness
- Identify quote, decline, and no-response patterns
- Compare carrier behavior across similar accounts
- Improve future market sequencing
- Improve account positioning
- Improve submission quality
- Detect changes in carrier behavior over time
- Preserve market intelligence in a structured format
- Reduce unnecessary market submissions
- Improve quote success and placement efficiency

The objective is **not** merely to document what happened on one account.

The objective is to answer:

> What did this marketing effort teach us about these carriers, this risk profile, and how we should approach similar opportunities in the future?

---

# Core Outcome

A successful use of this Skill should allow the marketing or placement team to understand:

- Which carriers demonstrated appetite
- Which carriers declined
- Which carriers were competitive
- Which carriers were conditional
- Which carriers were not viable
- Why carriers made those decisions
- What underwriting concerns mattered most
- What risk characteristics increased interest
- What characteristics created resistance
- Which carriers should be prioritized for similar risks
- Which carriers should be secondary or contingency markets
- Which markets should generally be avoided for similar profiles
- What positioning should be improved
- What information should be gathered earlier
- What market intelligence should be saved for future use

The output should contribute to a long-term **Carrier Intelligence Layer**, not remain isolated inside one account file.

---

# Best Used For

Use this Skill after or during:

- New-business marketing
- Renewal marketing
- Carrier remarketing
- Selective market checks
- Wholesale placements
- E&S placements
- Program placements
- Difficult-risk marketing
- Large-account marketing
- Carrier appetite testing
- Failed placements
- Competitive wins
- Competitive losses
- Carrier declinations
- Quote comparisons
- Post-bind reviews
- Marketing debriefs
- Producer / placement strategy meetings
- Carrier relationship reviews

It is especially useful when the agency wants to learn from:

- Multiple carrier responses
- Similar accounts
- Repeat industry submissions
- Carrier appetite changes
- Pricing changes
- Underwriting requirement changes
- Recurring submission weaknesses

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Current carrier appetite confirmation
- Carrier underwriting authority
- Binding authority
- Formal carrier appointment guidance
- Current market-access confirmation
- Regulatory advice
- Legal advice
- Formal actuarial pricing analysis
- Carrier financial-strength analysis
- Definitive prediction that a carrier will quote
- Definitive prediction of future pricing
- Automatic marketing authorization

This is a **carrier intelligence and placement-learning Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Marketing Intelligence Analysts
- Commercial Insurance Marketing Managers
- Placement Specialists
- Commercial Insurance Producers
- Commercial Account Executives
- Agency Principals
- Wholesale Brokers
- Carrier Relations Teams
- Agency Strategy Leaders

---

# Required Inputs

At minimum, provide:

```text
Account Information:
[INSERT CLIENT NAME + INDUSTRY]

Submission Details:
[INSERT SUMMARY]

Carriers Approached:
[LIST CARRIERS]

Carrier Responses:
[PASTE RESPONSES, QUOTES, DECLINATIONS, FEEDBACK]

Outcome:
[BOUND / LOST / PENDING]
```

The analysis should be based primarily on the supplied carrier behavior.

Do not invent carrier appetite or underwriting reasoning that is not supported.

---

# Recommended Inputs

The following information materially improves the analysis:

- Client industry
- Operations
- Revenue
- Payroll
- Employee count
- Vehicle count
- Property values
- Locations
- States
- Loss history
- Large claims
- Coverage requested
- Limits
- Deductibles
- Retentions
- Current carrier
- Current premium
- Renewal premium
- Target premium
- Submission date
- Quote date
- Decline date
- Underwriter
- Carrier office
- Carrier segment
- Wholesale path
- Carrier appetite notes
- Submission completeness
- Risk controls
- Broker positioning
- Quote terms
- Premium
- Commission
- Subjectivities
- Exclusions
- Deductibles
- Reasons for decline
- Reasons for lost account
- Bound carrier
- Final terms
- Producer feedback
- Client decision rationale
- Similar prior accounts

---

# Optional Intelligence Sources

When appropriate, useful sources may include:

- Current carrier appetite guides
- Carrier underwriting bulletins
- Carrier relationship notes
- Historical agency submissions
- Historical carrier declines
- Historical quotes
- Marketing logs
- Carrier scorecards
- Wholesale feedback
- CRM
- AMS
- Carrier portal data
- Agency placement database
- Current public carrier appetite information
- Current program information

Current carrier appetite should be validated before using historical intelligence as a future placement recommendation.

---

# Preferred Source Documents

Where available, prioritize:

1. Current carrier response
2. Carrier quote
3. Carrier declination
4. Carrier underwriting email
5. Carrier portal response
6. Wholesale broker feedback
7. Submission documentation
8. Bound proposal
9. Final client decision
10. Marketing notes
11. Historical carrier intelligence
12. Professional inference

---

# Document Completeness Standard

Classify the marketing intelligence set as:

### Complete Enough

Carrier responses and outcome information reasonably support meaningful analysis.

### Partially Complete

Useful insights are available, but one or more major carrier responses or outcome details are missing.

### Fragmentary

The available information is too incomplete to support reliable carrier-behavior conclusions.

When incomplete:

- Identify what carrier responses were reviewed
- Identify missing carriers or quotes
- Limit conclusions
- Do not treat silence as a decline unless documented

---

# Market Currency Standard

Carrier intelligence is time-sensitive.

Any future-facing carrier recommendation should consider:

- Date of the observed behavior
- Current carrier appetite
- Current underwriting leadership
- Current market conditions
- Current reinsurance conditions
- Current program availability
- Current geographic appetite
- Current industry restrictions
- Current minimum premium
- Current capacity

Historical carrier behavior should be treated as:

> Evidence of prior behavior

not:

> Permanent carrier appetite.

When using historical intelligence for future placement:

- Identify the date of the intelligence
- Revalidate current appetite where material
- Lower confidence as intelligence ages
- Increase confidence when repeated recent observations support the same pattern

---

# Intelligence Freshness Standard

Carrier intelligence should be classified when useful as:

### Current

Observed recently enough to inform present strategy with reasonable confidence.

### Recent

Still useful but should be confirmed.

### Historical

Useful for pattern analysis but not sufficient for current appetite conclusions.

### Stale / Requires Revalidation

Should not be used for future market selection without current confirmation.

The Skill should not define a universal time threshold because market volatility varies by line and segment.

---

# Source Hierarchy

When carrier behavior information conflicts, prioritize:

1. Current carrier underwriter confirmation
2. Current carrier quote / declination
3. Current carrier appetite documentation
4. Current wholesale broker confirmation
5. Recent agency experience
6. Historical agency experience
7. General market knowledge
8. Professional inference

Do not allow old agency experience to override direct current carrier guidance.

---

# Authority vs. Inference Standard

Distinguish clearly between:

### Carrier-Confirmed Signal

Directly stated by the carrier or underwriter.

Example:

> The carrier declined because more than 40% of revenue came from residential construction.

### Observed Behavior

What happened during the marketing effort.

Example:

> The carrier responded within one day and requested additional loss-control information.

### Agency Interpretation

A reasonable conclusion based on behavior.

Example:

> This suggests the carrier may have conditional appetite when residential work is limited and controls are strong.

### Pattern Hypothesis

A possible broader pattern requiring additional observations.

### Decision Authority

The carrier or authorized underwriter remains responsible for actual appetite and quote decisions.

---

# Evidence Classification

Every material insight should be classified internally as one of the following.

## Confirmed Carrier Statement

Explicitly stated by carrier or underwriter.

---

## Observed Outcome

Directly evidenced by:

- Quote
- Decline
- No quote
- Subjectivity
- Pricing
- Coverage term
- Final placement result

---

## Repeated Pattern

Supported by multiple comparable observations.

---

## Preliminary Pattern

Supported by limited observations and requiring more data.

---

## Agency Interpretation

Reasonable explanation derived from available behavior.

---

## Requires Revalidation

Historical or incomplete insight that should not be treated as current.

---

# Confidence Classification

Classify carrier intelligence where useful:

### High Confidence

Supported by repeated recent carrier behavior or direct carrier confirmation.

### Moderate Confidence

Supported by one or more meaningful observations but not fully established.

### Low Confidence

Limited observation, ambiguous reasoning, or stale data.

Avoid turning one decline into a permanent appetite rule.

---

# Neutral Narrative / Attribution Standard

Carrier intelligence should preserve attribution.

Use:

> Carrier A stated that the account exceeded its preferred fleet size.

not:

> Carrier A does not write fleets this size.

unless repeated current evidence supports the broader conclusion.

Use:

> The underwriter cited loss frequency as the primary reason for decline.

not:

> The account was uninsurable because of losses.

Distinguish:

- What the carrier said
- What the carrier did
- What the agency observed
- What the agency inferred

---

# Core Principle

## Learn From Every Marketing Outcome

Every:

- Quote
- Decline
- Subjectivity
- Pricing decision
- Coverage restriction
- No-response
- Bound account
- Lost account

can improve future placement strategy if the behavior is captured accurately.

The purpose is not to create more carrier notes.

The purpose is to compound the agency's placement intelligence over time.

---

# Execution Readiness Standard

Before producing reusable carrier-intelligence conclusions, classify the information as:

### Ready

Enough carrier response and outcome data exists for meaningful analysis.

### Conditionally Ready

Useful insight exists, but important data gaps reduce confidence.

### Not Ready

The marketing data is too incomplete for reliable pattern analysis.

Do not create agency-wide placement rules from insufficient evidence.

---

# Comparison Basis / Like-for-Like Standard

Before comparing carrier behavior across accounts, determine whether the risks are genuinely comparable.

Compare factors such as:

- Industry
- Operations
- Revenue
- Payroll
- Employee count
- Vehicle count
- Geography
- Property values
- Catastrophe exposure
- Loss history
- Large claims
- Coverage requested
- Limits
- Retentions
- Submission quality
- Market cycle
- Submission date

A carrier response to one account should not automatically be generalized to materially different risks.

---

# Risk Segmentation Standard

When useful, define the risk profile that produced the observed behavior.

Example:

```text
Industry:
Commercial Landscaping

Revenue:
$8M–$15M

Fleet:
25–50 vehicles

Geography:
Nevada / California

Loss Profile:
Low severity, moderate auto frequency

Coverage:
GL / Auto / WC / Umbrella
```

Carrier intelligence is more reusable when attached to a clearly defined risk segment.

---

# Workflow State Standard

Relevant intelligence-workflow states may include:

1. Marketing Initiated
2. Carrier Approached
3. Carrier Reviewing
4. Additional Information Requested
5. Quote Received
6. Declined
7. No Quote
8. Quote Revised
9. Finalist
10. Bound
11. Lost
12. Pending
13. Post-Marketing Review
14. Intelligence Captured
15. Revalidation Required

Do not treat:

> Carrier approached

as:

> Carrier demonstrated appetite.

---

# Workflow

## Step 1 — Establish the Account Profile

Capture:

- Industry
- Operations
- Size
- Geography
- Coverage
- Loss profile
- Major exposures
- Risk controls

This defines the context for interpreting carrier behavior.

---

## Step 2 — Establish the Marketing Objective

Determine:

- New business
- Renewal
- Market check
- Full remarketing
- Capacity search
- Difficult placement
- Coverage improvement
- Price competition
- Program restructuring

Carrier behavior should be interpreted in context.

---

## Step 3 — Inventory Markets Approached

For each carrier, capture:

- Carrier
- Market type
- Access path
- Underwriter if known
- Date submitted
- Lines submitted
- Current status

---

## Step 4 — Normalize Carrier Responses

Classify each response as:

### Quoted

Carrier provided actionable terms.

### Conditional Quote

Carrier interest exists but meaningful conditions remain.

### Indication

Preliminary pricing or terms only.

### Declined

Carrier explicitly declined.

### No Quote

Carrier reviewed but would not quote.

### No Response / Incomplete Response

No definitive response received.

### Pending

Still under review.

Do not combine these states.

---

## Step 5 — Capture Carrier-Stated Reasons

For each carrier, identify stated reasons involving:

- Industry
- Revenue
- Payroll
- Fleet
- Geography
- Property characteristics
- Catastrophe
- Losses
- Large claims
- Operations
- Products
- Professional exposure
- Residential work
- Subcontractors
- Risk controls
- Coverage limits
- Capacity
- Minimum premium
- Pricing
- Internal appetite
- Reinsurance
- Program eligibility

Preserve carrier language conceptually without overgeneralizing.

---

## Step 6 — Separate Stated Reason From Agency Interpretation

Example:

### Carrier Statement

> "Too much residential roofing exposure."

### Agency Interpretation

> Carrier may prefer roofing accounts with limited residential concentration.

### Confidence

Moderate — based on one current decline.

This distinction should be preserved in the intelligence record.

---

## Step 7 — Identify Appetite Signals

Potential positive signals include:

- Fast engagement
- Detailed underwriting questions
- Request for supplemental data
- Willingness to negotiate
- Quote
- Competitive quote
- Broader coverage
- Flexible deductible
- Capacity
- Interest despite known challenge

Potential negative signals include:

- Immediate decline
- Industry restriction
- Geographic restriction
- Loss intolerance
- Coverage limitation
- Capacity limitation
- High minimum premium
- Uncompetitive pricing
- Excessive subjectivities

---

# Appetite Signal Standard

A quote is strong evidence of appetite for the specific submitted risk.

A decline is evidence of non-appetite for the specific submitted risk.

Neither alone establishes permanent carrier-wide appetite.

Broader appetite conclusions should require:

- Direct carrier confirmation
- Multiple comparable observations
- Current appetite documentation
- Or a combination of these

---

## Step 8 — Identify Underwriting Decision Drivers

Determine what appears to influence decisions most strongly.

Potential drivers:

- Industry
- Revenue
- Payroll
- Geography
- Fleet size
- Driver quality
- Property construction
- Protection class
- CAT exposure
- Loss frequency
- Loss severity
- Large claims
- Safety program
- Management experience
- Contract controls
- Subcontractor controls
- Cyber controls
- Professional qualifications
- Product hazard
- Prior carrier history

Rank only supported drivers.

---

## Step 9 — Identify Deal-Breakers

A deal-breaker should be classified carefully.

### Confirmed Deal-Breaker

Carrier explicitly states it will not proceed because of the factor.

### Likely Deal-Breaker

Behavior strongly suggests the issue prevents progress.

### Potential Concern

Carrier raised the issue but did not necessarily decline because of it.

Do not label every underwriting question a deal-breaker.

---

## Step 10 — Identify Positive Risk Attributes

Capture what carriers responded favorably to.

Examples:

- Strong loss performance
- Experienced management
- Low employee turnover
- Formal safety program
- Telemetry
- Strong cyber controls
- Newer fleet
- Diversified customers
- Low catastrophe exposure
- Long operating history
- Strong contractual risk transfer

These attributes should inform future positioning.

---

## Step 11 — Analyze Pricing

For quoted markets, capture when available:

- Premium
- Rate
- Deductible
- Retention
- Limits
- Coverage differences
- Commission
- Subjectivities

Do not compare premium alone when coverage or exposure differs.

---

# Pricing Competitiveness Standard

Classify pricing only relative to comparable terms.

Potential classifications:

### Aggressive

Meaningfully competitive considering coverage and retention.

### Competitive

Within a credible competitive range.

### Conservative

Meaningfully above stronger alternatives.

### Non-Competitive

Pricing or terms make placement unrealistic.

### Unable to Compare

Terms are not sufficiently comparable.

Do not define aggressive solely as "lowest premium."

---

## Step 12 — Adjust Pricing Analysis for Coverage Differences

A lower quote may include:

- Higher deductible
- Reduced limits
- New exclusion
- Reduced sublimit
- Less favorable valuation
- Narrower coverage

Pricing analysis should consider these trade-offs.

---

## Step 13 — Evaluate Responsiveness

Where useful, assess:

- Time to acknowledgment
- Time to first underwriting question
- Time to quote
- Time to decline
- Communication quality
- Willingness to negotiate

Responsiveness is operational intelligence, not necessarily appetite by itself.

---

## Step 14 — Identify Submission Friction

Look for repeated carrier requests involving missing:

- Loss runs
- Exposure schedules
- Driver information
- Property data
- Payroll
- Revenue
- Controls
- Applications
- Supplementals
- Contracts
- Claims narratives

Repeated requests suggest submission-design opportunities.

---

## Step 15 — Evaluate Submission Quality

Classify when useful:

### Strong

Underwriters received enough information to evaluate efficiently.

### Adequate

Submission supported underwriting but required routine follow-up.

### Weak

Missing or unclear information materially delayed or impaired quoting.

### Unable to Assess

Insufficient information.

Do not blame submission quality for declines that clearly resulted from appetite.

---

## Step 16 — Identify Cross-Carrier Patterns

Look for multiple carriers reacting to the same issue.

Example:

If four carriers independently raise:

> Auto loss frequency

this is stronger intelligence than one carrier raising it.

Classify patterns as:

### Repeated Signal

Observed across multiple carriers.

### Isolated Signal

Raised by one carrier.

### Mixed Signal

Carriers responded differently.

---

## Step 17 — Identify Carrier Differentiation

Determine what distinguishes carriers.

Examples:

- Stronger construction appetite
- Better auto pricing
- Better property terms
- Better loss tolerance
- Better large-account capability
- Better catastrophe capacity
- Better responsiveness
- More flexible underwriting
- Better umbrella capacity
- More restrictive exclusions

Use evidence from actual behavior.

---

## Step 18 — Analyze Final Outcome

If bound:

Identify:

- Bound carrier
- Why selected
- Competitive advantage
- Trade-offs accepted

If lost:

Identify:

- Winning carrier if known
- Why client selected alternative
- Pricing difference
- Coverage difference
- Relationship factor
- Execution issue

If pending:

Identify:

- Remaining decisions
- Missing carrier responses
- Outstanding information

---

# Outcome Attribution Standard

Do not assume:

> Lowest price won.

Capture the documented or reported reason when available.

Possible outcome drivers:

- Price
- Coverage
- Deductible
- Carrier reputation
- Relationship
- Claims service
- Risk-management services
- Contract requirements
- Financing
- Client preference
- Timing
- Incumbent retention

---

## Step 19 — Develop Future Carrier Prioritization

Classify carriers for similar risks:

### Priority Market

Strong evidence of relevant appetite and competitive potential.

### Secondary Market

Potentially useful under defined conditions.

### Conditional Market

Worth considering only if specific conditions are met.

### Low-Priority Market

Weak fit based on current evidence.

### Avoid for This Risk Profile

Repeated or confirmed non-appetite for the defined segment.

### Revalidate Before Use

Historical evidence may no longer be current.

Avoid permanent carrier labels without risk-segment context.

---

## Step 20 — Define Future Market Sequencing

Recommended structure:

### Wave 1 — Primary Markets

Best-supported fit.

### Wave 2 — Secondary Markets

Useful alternatives if primary markets fail or competition is needed.

### Wave 3 — Contingency Markets

Specialty, E&S, wholesale, or conditional alternatives.

Do not recommend indiscriminate marketing.

---

## Step 21 — Develop Positioning Recommendations

For future similar accounts, identify:

### Lead With

Risk strengths that demonstrated carrier value.

### Explain Proactively

Issues that carriers repeatedly questioned.

### Quantify

Data that should be supported with schedules or analysis.

### Avoid Overemphasizing

Information that creates confusion without helping underwriting.

### Provide Early

Documents repeatedly requested.

---

## Step 22 — Identify Submission Improvements

Potential improvements:

- Better loss narrative
- More complete schedule
- Exposure summary
- Risk-control documentation
- Executive summary
- Claim context
- Vehicle details
- Payroll segmentation
- Revenue segmentation
- Property protection details
- Cyber control summary
- Contract-control explanation
- Submission index

Prioritize improvements based on observed underwriter friction.

---

## Step 23 — Identify Data Gaps

Classify missing intelligence:

### Account Data Gap

Information about the risk was incomplete.

### Carrier Response Gap

Carrier reasoning was not captured.

### Pricing Gap

Quote terms were incomplete.

### Outcome Gap

Final placement rationale is unknown.

### Historical Comparison Gap

Insufficient comparable accounts exist.

---

## Step 24 — Define Intelligence Record

Capture reusable intelligence using fields such as:

```text
carrier
carrier_segment
risk_industry
risk_size_band
geography
line_of_business
submission_date
response_type
appetite_signal
stated_reason
agency_interpretation
key_underwriting_driver
deal_breaker
positive_signal
pricing_position
coverage_position
response_speed
submission_gap
final_outcome
bound_flag
intelligence_date
confidence
revalidation_needed
source_reference
```

---

# Transaction Lineage / Audit Trail Standard

Carrier intelligence should remain traceable to its source.

Preserve:

1. Submission
2. Carrier response
3. Quote / decline
4. Agency interpretation
5. Final outcome
6. Stored intelligence record
7. Later revalidation or correction

Example:

```text
Carrier Declination Email
    ↓
Captured Decline Reason
    ↓
Agency Interpretation
    ↓
Risk-Segment Intelligence Record
    ↓
Future Placement Recommendation
```

Do not overwrite original carrier behavior with later interpretation.

If intelligence is later corrected:

- Preserve prior record where appropriate
- Add revised interpretation
- Record date
- Record source
- Lower or raise confidence accordingly

---

# System-of-Record Standard

When carrier intelligence is stored across systems, identify the authoritative source.

Potential systems:

- CRM
- AMS
- Placement platform
- Carrier intelligence database
- Data warehouse
- Marketing tracker

Recommended approach:

| Data | System of Record | Write-Back |
|---|---|---|
| Account Marketing Activity | CRM / AMS | Current marketing status |
| Carrier Response | Placement / CRM | Response type + reason |
| Final Quote | AMS / Placement | Terms |
| Bound Outcome | AMS | Final carrier / policy |
| Carrier Intelligence | Intelligence Repository | Reusable carrier insight |

Do not allow isolated email notes to become the only record of meaningful carrier intelligence.

---

# Handoff Integrity Standard

When marketing intelligence is transferred from:

- Producer to marketing
- Marketing to producer
- Wholesale broker to agency
- Underwriter to agency
- Account team to intelligence repository
- AI Teammate to human reviewer

the handoff should include:

- Account
- Risk profile
- Carrier
- Response
- Stated reason
- Source
- Interpretation
- Confidence
- Required follow-up
- Current workflow state

A carrier response should not be reduced to:

> Declined.

when the actual reason is valuable future intelligence.

---

# Governance / Conflict Prevention Standard

Before using historical carrier intelligence for a new account:

Check for:

- More recent carrier guidance
- Conflicting appetite experience
- Different geography
- Different business size
- Different operations
- Different line
- Different access path
- Different underwriting office
- Different market cycle
- Different program

Do not apply stale or mismatched intelligence automatically.

---

# Dynamic Reassessment / Monitoring Trigger Standard

Carrier intelligence should be reassessed when material new evidence appears.

Potential triggers:

- Carrier quotes a risk previously considered outside appetite
- Carrier declines multiple previously accepted risks
- New underwriting bulletin
- New minimum premium
- New geographic restriction
- New industry restriction
- New program launch
- Underwriter confirms appetite change
- Pricing behavior materially changes
- Carrier exits market
- Carrier expands capacity
- Reinsurance change affects appetite
- Agency receives repeated conflicting signals

Recommended structure:

### Current Intelligence

[Carrier / Risk Segment / Assessment]

### Reassess When

- [Trigger]
- [Trigger]

### Owner

[Marketing Intelligence / Carrier Relations]

Historical conclusions should evolve with evidence.

---

# Stop Rules

Stop pattern generalization and require further evidence when:

- Only one weak observation exists
- Risk profiles are not comparable
- Carrier reasoning is unknown
- Market conditions materially changed
- Carrier appetite is stale
- Underwriting office differences may explain behavior
- Conflicting current evidence exists
- Intelligence would drive a high-stakes market exclusion

Do not create false certainty from sparse data.

---

# Completion Criteria Standard

The account-level carrier intelligence review is complete when:

1. Account profile is documented
2. Markets approached are captured
3. Carrier response states are normalized
4. Stated reasons are captured
5. Agency interpretations are separated
6. Underwriting drivers are identified
7. Pricing is evaluated where supportable
8. Cross-carrier patterns are identified
9. Submission gaps are identified
10. Outcome is captured
11. Future carrier prioritization is defined
12. Positioning improvements are defined
13. Reusable intelligence is stored
14. Confidence is assigned
15. Revalidation requirements are identified

The broader intelligence loop is not permanently complete.

Carrier behavior should continue to evolve as new evidence is captured.

---

# Decision Rules

## One Decline Is Not Permanent Appetite

Do not build a carrier rule from a single isolated observation.

---

## A Quote Is Risk-Specific Evidence

It demonstrates appetite for the submitted risk under those circumstances.

Do not automatically generalize beyond comparable risks.

---

## Carrier-Stated Reason Before Agency Theory

Use direct carrier reasoning first.

---

## Historical Intelligence Must Be Revalidated

Market conditions change.

---

## Pricing Must Be Coverage-Adjusted

The lowest premium is not automatically the most competitive quote.

---

## Submission Problems Are Not Appetite Problems

Distinguish:

> Carrier could not evaluate the submission

from:

> Carrier does not want the risk.

---

## No-Response Is Not Automatically Decline

Keep statuses distinct.

---

## Market Learning Should Reduce Waste

The goal is not to market to more carriers.

The goal is to select better carriers.

---

## Mixed Signals Should Remain Mixed

Do not force a single appetite conclusion when carriers or observations conflict.

---

# Materiality / Prioritization Framework

Prioritize intelligence using:

| Factor | Question |
|---|---|
| Repeatability | Has this behavior occurred more than once? |
| Recency | How recent is the observation? |
| Carrier Confirmation | Did the carrier explicitly state the reason? |
| Risk Similarity | Is the comparison truly similar? |
| Placement Impact | Could this meaningfully improve future placement? |
| Pricing Impact | Does it reveal a competitive tendency? |
| Coverage Impact | Does the carrier regularly offer stronger or weaker terms? |
| Submission Impact | Could better data improve quote success? |
| Relationship Impact | Does access path or underwriter matter? |
| Confidence | How reliable is the intelligence? |

---

# Trade-Off Transparency Standard

When recommending one carrier over another, identify:

1. What the carrier appears strong at
2. Where the carrier appears weaker
3. Conditions that may limit fit
4. What evidence supports the recommendation
5. What needs current confirmation

Example:

> Carrier A appears to be a stronger primary market for mid-sized contractors because of demonstrated appetite and competitive GL pricing, but its auto pricing was less competitive on this account. Current appetite should still be confirmed before future submission.

---

# Ownership Standard

For future intelligence actions, identify an owner.

Potential owners:

- Marketing Intelligence
- Marketing Manager
- Placement Specialist
- Producer
- Carrier Relations
- Account Executive
- Data Operations
- AI Teammate

Example:

| Action | Owner |
|---|---|
| Confirm current appetite | Marketing |
| Update carrier intelligence record | AI Teammate / Marketing |
| Validate pricing pattern | Marketing Intelligence |
| Improve loss narrative | Producer / Account Executive |

---

# Obligation Extraction Standard

Where carrier responses create explicit future requirements, capture them.

Examples:

- Required supplemental
- Required loss runs
- Minimum premium
- Required risk control
- Required telematics
- Required driver criteria
- Required property protection
- Required deductible

Recommended structure:

| Carrier Requirement | Trigger | Required For | Evidence | Source | Revalidate? |
|---|---|---|---|---|---|
| [Requirement] | [Trigger] | [Quote / Submission] | [Evidence] | [Carrier response] | Yes / No |

Do not convert an underwriting preference into a mandatory requirement unless the carrier states it as such.

---

# Human Review Escalation Standard

Require human review when intelligence would:

- Exclude a major carrier from future strategy
- Drive agency-wide carrier appetite rules
- Change market sequencing materially
- Affect exclusive market access
- Influence wholesaler selection
- Contradict current carrier guidance
- Depend on stale data
- Create producer or carrier relationship concerns
- Contain confidential underwriter commentary
- Influence major placement strategy

AI can identify patterns.

Senior marketing professionals should approve agency-wide conclusions.

---

# Internal vs. External Information Boundary Standard

Carrier intelligence is primarily internal.

### Internal Appropriate

- Carrier appetite notes
- Pricing tendencies
- Underwriter responsiveness
- Decline reasons
- Negotiation observations
- Submission weaknesses
- Carrier rankings
- Relationship notes

### External Appropriate

Only information appropriate for the intended client or carrier audience.

Do not automatically expose internal carrier scoring or strategy to clients.

Do not expose confidential carrier commentary unnecessarily.

---

# Output Requirements

Use the following structure unless the user requests another format.

# Commercial Insurance Carrier Behavior & Placement Intelligence

## 1. Intelligence Readiness

**Status:** Ready / Conditionally Ready / Not Ready

**Outcome:** Bound / Lost / Pending

**Account:** [Client]  
**Industry:** [Industry]  
**Risk Segment:** [Short description]  
**Marketing Date / Period:** [Date]

---

## 2. Executive Placement Intelligence

Provide a concise summary answering:

- What did this marketing effort teach us?
- Which carriers demonstrated the strongest fit?
- What issues mattered most to underwriters?
- What should change the next time a similar risk is marketed?

---

## 3. Carrier Response Matrix

| Carrier | Response | Appetite Signal | Carrier-Stated Reason | Pricing Position | Coverage Position | Confidence |
|---|---|---|---|---|---|---|
| [Carrier] | Quote / Decline / Pending | Strong / Conditional / Weak | [Reason] | Aggressive / Competitive / Conservative / N/A | [Observation] | High / Moderate / Low |

---

## 4. Carrier Appetite Insights

### [Carrier]

**Observed behavior:**  
[What happened]

**Carrier-stated rationale:**  
[Reason]

**Agency interpretation:**  
[Interpretation]

**Risk profile fit:**  
[Where carrier appears strongest]

**Confidence:**  
High / Moderate / Low

**Revalidation needed:**  
Yes / No

Repeat for material carriers.

---

## 5. Cross-Carrier Underwriting Signals

| Signal / Risk Factor | Carriers Raising It | Direction | Strength of Signal | Future Implication |
|---|---|---|---|---|
| [Loss frequency] | [A, B, C] | Negative | Strong | Address proactively |
| [Risk controls] | [A, D] | Positive | Moderate | Lead with controls |

---

## 6. Deal-Breakers & Conditional Factors

| Factor | Carrier(s) | Classification | Evidence | Future Strategy |
|---|---|---|---|---|
| [Factor] | [Carrier] | Confirmed Deal-Breaker / Likely / Concern | [Source] | [Action] |

---

## 7. Positive Risk Attributes

Identify characteristics that increased carrier interest.

Examples:

- Strong loss history
- Good controls
- Experienced management
- Stable operations
- Strong fleet management
- Good property protection

Explain which carriers responded positively.

---

## 8. Pricing & Competitiveness Observations

| Carrier | Premium / Pricing | Terms | Competitiveness | Important Trade-Off |
|---|---:|---|---|---|
| [Carrier] | [$] | [Key terms] | Aggressive / Competitive / Conservative | [Trade-off] |

If terms are not comparable:

> Unable to make a reliable pricing comparison.

---

## 9. Submission Quality & Friction

### Submission Quality

Strong / Adequate / Weak / Unable to Assess

### Repeated Information Requests

- [Item]
- [Item]

### Missing / Unclear Information

- [Item]

### Impact on Quoting

[Explanation]

---

## 10. Final Outcome Analysis

**Bound Carrier:** [If applicable]

### Why the Outcome Occurred

[Documented reason]

### What Worked

- [Item]

### What Did Not Work

- [Item]

### Important Trade-Offs

[Explanation]

---

## 11. Future Carrier Prioritization

| Carrier | Future Priority | Best-Fit Risk Profile | Conditions | Current Revalidation Needed |
|---|---|---|---|---|
| [Carrier] | Priority / Secondary / Conditional / Low / Avoid | [Profile] | [Conditions] | Yes / No |

---

## 12. Recommended Market Sequencing

### Wave 1 — Primary Markets

1. [Carrier / Carrier Type]
2. [Carrier / Carrier Type]

### Wave 2 — Secondary Markets

1. [Carrier]

### Wave 3 — Contingency Markets

1. [Carrier / Wholesale / E&S]

Explain the reasoning.

---

## 13. Future Positioning Strategy

### Lead With

- [Strength]

### Address Proactively

- [Concern]

### Quantify

- [Exposure]

### Provide Early

- [Document]

### Avoid Leaving Unexplained

- [Issue]

---

## 14. Data Gaps & Submission Improvements

| Gap | Impact | Recommended Improvement | Owner |
|---|---|---|---|
| [Gap] | [Impact] | [Action] | [Owner] |

---

## 15. Reusable Carrier Intelligence Records

| Carrier | Risk Segment | Intelligence | Evidence Type | Confidence | Date | Revalidate |
|---|---|---|---|---|---|---|
| [Carrier] | [Segment] | [Insight] | Confirmed / Observed / Pattern | High / Moderate / Low | [Date] | Yes / No |

---

## 16. Monitoring / Reassessment Triggers

Reassess this intelligence if:

- [Carrier appetite changes]
- [New quote contradicts prior behavior]
- [New carrier bulletin]
- [Pricing changes materially]
- [Repeated similar accounts produce different outcomes]

---

## 17. Recommended Agency Actions

| Priority | Action | Owner | Timing | Completion Criteria |
|---|---|---|---|---|
| 1 | [Action] | [Owner] | [Timing] | [Criteria] |

---

# Carrier Intelligence Snapshot

When requested, also provide a short structured record.

```text
Carrier:
[Carrier]

Risk Segment:
[Industry / Size / Geography]

Observed Appetite:
[Strong / Conditional / Weak]

Primary Drivers:
[Drivers]

Pricing:
[Aggressive / Competitive / Conservative / Unknown]

Key Concern:
[Concern]

Best Positioning:
[Approach]

Avoid / Confirm:
[Issue]

Confidence:
[High / Moderate / Low]

Intelligence Date:
[Date]

Revalidate:
[Yes / No]
```

---

# Machine-Readable Intelligence Output

When requested, produce normalized fields such as:

```text
account_name
industry
risk_segment
marketing_date
carrier_name
carrier_segment
access_path
response_type
response_date
appetite_signal
carrier_stated_reason
agency_interpretation
underwriting_driver
deal_breaker
positive_signal
pricing_position
quoted_premium
coverage_position
response_speed
submission_gap
final_outcome
bound_flag
intelligence_confidence
intelligence_date
revalidation_required
source_reference
```

Do not populate unsupported fields.

---

# Assumptions & Items Requiring Confirmation

| Assumption / Interpretation | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Item] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Account risk profile is identified
- [ ] Marketing objective is understood
- [ ] All known markets approached are captured
- [ ] Quote / decline / no quote / pending statuses are distinguished
- [ ] Carrier-stated reasons are preserved
- [ ] Agency interpretation is separate from carrier fact
- [ ] Intelligence is dated
- [ ] Current vs. historical intelligence is distinguished
- [ ] Appetite conclusions are risk-segment specific
- [ ] One account is not overgeneralized
- [ ] Comparable risks are used for pattern analysis
- [ ] Pricing comparison considers coverage differences
- [ ] Submission friction is identified
- [ ] Repeated cross-carrier signals are distinguished from isolated signals
- [ ] Final outcome rationale is captured
- [ ] Future carrier prioritization is evidence-based
- [ ] Current appetite revalidation is flagged where needed
- [ ] Handoff information is sufficient
- [ ] System-of-record requirements are addressed where operational
- [ ] Intelligence lineage is preserved
- [ ] Monitoring triggers are defined
- [ ] Human review is triggered for agency-wide rules
- [ ] Internal carrier intelligence is not exposed externally without judgment
- [ ] No unsupported appetite claims are fabricated

---

# Failure Conditions

The Skill should not be considered complete if:

- Carrier responses are merely summarized
- One decline becomes a permanent appetite rule
- Carrier reasoning is invented
- Agency interpretation is presented as carrier fact
- No-response is treated as decline
- Pricing is compared without adjusting for material coverage differences
- Historical intelligence is presented as current
- Risk segments are not defined
- Cross-carrier patterns are claimed without evidence
- Submission problems are confused with appetite problems
- Final placement outcome is not analyzed
- Future market recommendations are generic
- Carrier intelligence is not traceable to source
- Revalidation triggers are absent
- Agency-wide carrier exclusions are recommended without human review

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Fabricate Carrier Appetite

Never invent:

- Appetite
- Decline reason
- Minimum premium
- Pricing tendency
- Capacity
- Program availability
- Underwriting requirement
- Geographic restriction
- Industry restriction

---

## Do Not Treat Historical Behavior as Permanent

Carrier appetite changes.

Date intelligence.

Revalidate when material.

---

## Preserve Attribution

Distinguish:

- Carrier statement
- Observed response
- Agency interpretation
- Pattern hypothesis

---

## Do Not Blacklist Carriers From Sparse Evidence

An isolated decline is not sufficient to create an agency-wide avoidance rule.

---

## Do Not Equate Lowest Price With Best Market

Consider:

- Coverage
- Retention
- Limits
- Exclusions
- Service
- Capacity
- Fit

---

## Do Not Over-Market

The objective is better market selection, not more submissions.

---

## Preserve Market Governance

Avoid:

- Duplicate submissions
- Market blocking
- Conflicting wholesale approaches
- Multiple access paths without coordination

---

## Protect Confidential Information

Do not unnecessarily expose:

- Confidential underwriter commentary
- Internal carrier scores
- Negotiation strategy
- Producer strategy
- Client-sensitive information
- Proprietary agency intelligence

---

## No Unauthorized Carrier Representation

Do not state that a carrier:

- Will quote
- Will bind
- Will accept the account

unless confirmed by authorized carrier personnel.

---

## Preserve Human Accountability

This Skill supports placement strategy.

The authorized marketing professional, producer, carrier, underwriter, wholesale broker, or agency principal remains responsible for:

- Market selection
- Carrier submissions
- Market access
- Binding
- Carrier relationship management
- Agency-wide appetite conclusions
- Placement recommendations
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like a senior commercial insurance marketing leader analyzing placement outcomes for future strategic use.

The tone should be:

- Analytical
- Practical
- Specific
- Evidence-based
- Commercially aware
- Non-alarmist
- Strategic
- Concise

Avoid:

- Generic carrier descriptions
- Permanent labels from isolated results
- Unsupported appetite claims
- Carrier bashing
- Emotional commentary
- Excessive underwriting jargon
- Long unprioritized lists

The output should help the agency make better market decisions next time.

---

# Example

## Example Request

```text
Account Information:

Western Industrial Services
Commercial mechanical contractor
$18M revenue
Nevada and Northern California
45 vehicles
10% residential work
5-year loss history includes several small auto claims and one $350,000 liability loss.

Submission Details:

GL, Auto, Property, WC, $5M Umbrella.
Formal safety program.
Telematics installed in all vehicles.
Loss-control narrative provided.

Carriers Approached:

Carrier A
Carrier B
Carrier C
Carrier D

Carrier Responses:

Carrier A:
Declined. Underwriter stated auto frequency was outside current appetite.

Carrier B:
Quoted GL, Property, WC and Auto at $412,000 total. Requested $25,000 auto deductible. Underwriter specifically liked telematics and management controls.

Carrier C:
Declined. Underwriter stated residential contracting exposure was outside appetite.

Carrier D:
Quoted at $368,000 but excluded residential work and offered only $2M umbrella capacity.

Outcome:

Bound with Carrier B.
```

---

## Example Output

# Commercial Insurance Carrier Behavior & Placement Intelligence

## 1. Intelligence Readiness

**Status:** Ready

**Outcome:** Bound  
**Account:** Western Industrial Services  
**Industry:** Commercial Mechanical Contractor  
**Risk Segment:** $10M–$25M contractor, 25–50 vehicle fleet, NV / Northern CA, limited residential exposure

---

## 2. Executive Placement Intelligence

This marketing effort suggests that the strongest carrier fit was with markets willing to accept moderate commercial-auto frequency when the account could demonstrate meaningful fleet controls.

Auto performance was the most important cross-carrier underwriting issue.

Carrier B demonstrated the strongest overall fit because it was willing to quote the full program, recognized the value of telematics and management controls, and provided sufficient umbrella capacity.

Carrier D produced the lowest headline premium, but the residential-work exclusion and reduced umbrella capacity materially weakened the offer.

The primary lesson for future similar contractors is to lead early with fleet-management controls and explain auto frequency proactively rather than allowing loss runs to speak for themselves.

---

## 3. Carrier Response Matrix

| Carrier | Response | Appetite Signal | Carrier-Stated Reason | Pricing Position | Coverage Position | Confidence |
|---|---|---|---|---|---|---|
| Carrier A | Declined | Weak for this profile | Auto frequency outside appetite | N/A | N/A | High |
| Carrier B | Quoted / Bound | Strong | Positive response to controls | Competitive | Full program with higher auto deductible | High |
| Carrier C | Declined | Weak / Conditional | Residential contracting outside appetite | N/A | N/A | High |
| Carrier D | Quoted | Conditional | No explicit decline concern | Aggressive headline price | Residential excluded; only $2M umbrella | High |

---

## 4. Cross-Carrier Underwriting Signals

| Signal | Carriers | Direction | Strength | Future Implication |
|---|---|---|---|---|
| Auto loss frequency | A, B | Negative / conditional | Strong | Address proactively |
| Telematics | B | Positive | Moderate | Lead with documented fleet controls |
| Residential exposure | C, D | Negative | Strong | Quantify residential percentage early |
| Umbrella capacity | D | Restrictive | Moderate | Confirm capacity before relying on market |

---

## 5. Pricing & Competitiveness

Carrier D appeared most aggressive on premium at $368,000 versus Carrier B at $412,000.

However, the terms were not equivalent.

Carrier D:

- Excluded residential work
- Offered only $2 million of umbrella capacity

Carrier B offered a more complete structure with $5 million umbrella capacity but required a $25,000 auto deductible.

Carrier D should therefore not automatically be characterized as the more competitive overall program solely because of premium.

---

## 6. Future Carrier Prioritization

| Carrier | Future Priority | Best-Fit Profile | Conditions | Revalidate |
|---|---|---|---|---|
| Carrier B | Priority | Commercial contractors with fleet controls | Be prepared for higher auto retention | Yes |
| Carrier D | Conditional | Primarily commercial contractors with limited residential work | Verify umbrella capacity and residential restriction | Yes |
| Carrier A | Low for current profile | Potentially stronger with improved auto frequency | Revalidate if loss profile improves | Yes |
| Carrier C | Low / Avoid for risks with meaningful residential work | Primarily commercial-only contractors | Confirm current residential appetite | Yes |

---

## 7. Future Positioning Strategy

### Lead With

- 100% fleet telematics
- Formal safety program
- Management oversight
- Commercial-project concentration

### Address Proactively

- Auto frequency
- $350,000 liability loss
- Residential exposure

### Quantify

- Percentage of residential revenue
- Auto claim frequency by vehicle / driver
- Improvement since telematics implementation

### Provide Early

- Fleet safety narrative
- Five-year loss analysis
- Driver-control process
- Residential/commercial revenue split

---

## 8. Reusable Carrier Intelligence

| Carrier | Risk Segment | Intelligence | Evidence Type | Confidence | Revalidate |
|---|---|---|---|---|---|
| Carrier B | Mid-market mechanical contractors with fleet | Demonstrated willingness to quote despite auto frequency when strong fleet controls exist | Observed Quote + UW Feedback | High | Yes |
| Carrier C | Contractors with residential exposure | Declined because of residential work | Confirmed Carrier Statement | Moderate | Yes |
| Carrier D | Commercial-dominant contractors | Aggressive pricing but restrictive residential and umbrella terms | Observed Quote | High | Yes |

---

## 9. Reassessment Triggers

Reassess this intelligence if:

- Carrier A begins quoting similar fleet accounts
- Carrier C changes residential contracting appetite
- Carrier D increases umbrella capacity
- Carrier B begins declining similar auto-frequency profiles
- New carrier appetite bulletins contradict these observations

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a commercial insurance marketing intelligence analyst responsible for capturing and interpreting carrier behavior over time to improve future placement strategy across the agency.
>
> Review the information below and evaluate the outcome as if you are building a long-term understanding of how carriers respond to similar risks. Focus on identifying patterns, signals, and decision drivers—not just describing what happened.
>
> Account Information:
> [INSERT CLIENT NAME + INDUSTRY]
>
> Submission Details:
> [INSERT SUMMARY]
>
> Carriers Approached:
> [LIST CARRIERS]
>
> Carrier Responses:
> [PASTE RESPONSES, QUOTES, DECLINATIONS, FEEDBACK]
>
> Outcome:
> [BOUND / LOST / PENDING]
>
> Analyze the responses and provide structured insight that can be reused for future marketing efforts involving similar risks.
>
> Structure your response as:
>
> - Carrier appetite insights, including which carriers showed interest, which declined, and the underlying reasons driving those decisions. Identify any patterns in appetite based on industry, size, exposure, or loss profile.
> - Underwriting signals, highlighting the factors that influenced decision-making, including specific concerns, strengths, or deal-breakers observed across carriers.
> - Pricing and competitiveness observations, identifying which carriers were aggressive, conservative, or inconsistent, and any notable pricing behavior relative to the risk profile.
> - Future placement recommendations, including which carriers should be prioritized for similar risks, which should be avoided, and how the account should be positioned differently to improve outcomes.
> - Data gaps and submission improvements, identifying what information was missing, unclear, or could have been presented more effectively to improve quoting success.
>
> Approach this as a senior marketing leader reviewing outcomes across multiple accounts. Look for repeatable insights that can inform future strategy—not one-off commentary.
>
> Keep the output practical, specific, and directly applicable to improving placement decisions going forward.

---

# Evolution From Prompt to Skill

The original prompt established the goal of learning from carrier marketing outcomes.

This Skill expands that prompt into a reusable Placement Intelligence workflow by adding:

- Risk-segment definition
- Intelligence freshness
- Market Currency Standard
- Source hierarchy
- Authority vs. Inference Standard
- Evidence classification
- Neutral Narrative / Attribution Standard
- Execution readiness
- Comparison Basis / Like-for-Like Standard
- Carrier-response normalization
- Appetite Signal Standard
- Underwriting driver analysis
- Deal-breaker classification
- Positive-risk signal analysis
- Pricing Competitiveness Standard
- Coverage-adjusted pricing comparison
- Responsiveness analysis
- Submission-friction analysis
- Cross-carrier pattern detection
- Carrier differentiation
- Outcome Attribution Standard
- Future carrier prioritization
- Market sequencing
- Positioning recommendations
- Submission improvements
- Reusable intelligence record
- Transaction Lineage / Audit Trail Standard
- System-of-Record Standard
- Handoff Integrity Standard
- Governance / Conflict Prevention Standard
- Dynamic Reassessment / Monitoring Trigger Standard
- Stop rules
- Completion criteria
- Obligation Extraction Standard
- Human Review Escalation Standard
- Internal / external information controls
- Machine-readable intelligence schema
- Example implementation

The purpose is to transform a post-marketing review prompt into a reusable **Carrier Intelligence Skill** that allows agency placement knowledge to compound over time.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Prospect Intelligence Brief](../01-prospect-intelligence-brief/SKILL.md)
- [Commercial Insurance Renewal Strategy Builder](../04-renewal-strategy-builder/SKILL.md)
- [Commercial Insurance Underwriter Submission Email](../07-underwriter-submission-email/SKILL.md)
- [Commercial Insurance Exposure Summary Builder](../08-exposure-summary-builder/SKILL.md)
- [Commercial Insurance Carrier Placement Strategy](../09-carrier-placement-strategy/SKILL.md)
- [Commercial Insurance Business Classification Analysis](../10-business-classification-analysis/SKILL.md)
- [Commercial Insurance Renewal Comparison Analysis](../13-renewal-comparison-analysis/SKILL.md)
- [Insurance Document Intelligence & Decision Impact Analysis](../19-insurance-document-intelligence/SKILL.md)
- [Insurance Standard Operating Procedure (SOP) Builder](../20-standard-operating-procedure-builder/SKILL.md)

---

# Suggested Invocation

```text
Perform a Commercial Insurance Carrier Behavior & Placement Intelligence Review.

Account Information:
[CLIENT + INDUSTRY + RISK PROFILE]

Submission Details:
[SUMMARY]

Carriers Approached:
[LIST]

Carrier Responses:
[PASTE QUOTES / DECLINES / FEEDBACK]

Outcome:
[BOUND / LOST / PENDING]

Final Pricing / Terms:
[OPTIONAL]

Client Decision Rationale:
[OPTIONAL]

Historical Similar Accounts:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Account Information:
[INSERT]

Submission Details:
[INSERT]

Carriers Approached:
[LIST]

Carrier Responses:
[PASTE]

Outcome:
[BOUND / LOST / PENDING]
```

---

# Version History

## 1.0.0

Initial public release using the Apeironix Gold Standard Template v2.2.

Enhancements from the original Prompt #21 include:

- Carrier response normalization
- Risk segmentation
- Market intelligence freshness
- Neutral attribution
- Appetite-signal controls
- Cross-carrier pattern detection
- Pricing normalization
- Submission-friction analysis
- Outcome attribution
- Future market sequencing
- Reusable carrier intelligence records
- Transaction lineage
- System-of-record controls
- Handoff integrity
- Dynamic reassessment
- Human review
- Machine-readable intelligence structure
- Example implementation

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Placement strategy
- Carrier intelligence
- Risk advisory
- Analysis
- Growth

while AI handles more of the repetitive work surrounding those responsibilities.

Apeironix is building an AI Operating Layer designed to work alongside the systems insurance agencies already use.

The long-term objective is to turn individual agency experience into reusable operational intelligence that improves every future decision.

### Your people make the decisions. Your AI Teammates do the work.

**Keep your systems. Activate an AI Workforce.**

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
