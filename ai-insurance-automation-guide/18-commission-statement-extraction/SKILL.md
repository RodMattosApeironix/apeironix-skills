---
name: commission-statement-extraction
title: Insurance Commission Statement Extraction & Reconciliation
collection: ai-insurance-automation-guide
prompt_number: 18
category: agency-operations
capability: revenue-intelligence
primary_role: insurance-financial-operations-analyst
secondary_roles:
  - commission-specialist
  - accounting-specialist
  - agency-operations-manager
  - producer-compensation-analyst
  - agency-principal
template_version: 2.1
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Insurance Commission Statement Extraction & Reconciliation

## Purpose

Transform carrier commission statements, payment reports, remittance statements, or similar financial documents into a clean, structured, reconciliation-ready dataset.

This Skill is designed to help the insurance professional:

- Extract commission transactions accurately
- Normalize inconsistent carrier statement formats
- Identify policy and account-level payment information
- Capture premium and commission amounts
- Identify producer splits when explicitly available
- Distinguish gross commission from producer compensation
- Identify negative adjustments, reversals, chargebacks, and corrections
- Reconcile statement totals where possible
- Detect duplicate or inconsistent transactions
- Flag missing or ambiguous information
- Preserve source traceability
- Produce structured output suitable for accounting, commission reconciliation, reporting, or downstream system processing

The objective is **not** simply to copy fields from a statement.

The objective is to produce a reliable **Commission Intelligence Dataset** that can support financial operations and future automation.

---

# Core Outcome

A successful use of this Skill should allow the financial operations team to understand:

- Which carrier issued the statement
- Which policies or transactions appear on the statement
- Which insured or account is associated with each transaction when available
- What premium or exposure amount is shown
- What commission amount was paid or adjusted
- What commission rate is shown or calculable
- Whether a transaction is positive, negative, reversed, or corrected
- Whether producer splits are explicitly shown
- Whether any producer allocation is only inferred
- Whether statement totals reconcile
- What data remains missing or ambiguous
- Whether the extracted dataset is ready for internal reconciliation or import

The final output should be structured enough to support:

- Accounting review
- Producer compensation
- Commission reconciliation
- Revenue reporting
- Exception handling
- AMS / CRM updates
- Commission automation

---

# Best Used For

Use this Skill when reviewing:

- Carrier commission statements
- Broker commission statements
- MGA statements
- Wholesale commission statements
- Agency-billed commission reports
- Direct-bill commission statements
- Supplemental commission reports
- Bonus commission reports
- Contingency commission reports
- Renewal commission statements
- New-business commission statements
- Chargeback statements
- Correction statements
- Producer compensation reports
- Mixed-line commission statements
- Multi-policy statements
- PDF statements
- Spreadsheet statements
- Portal exports
- Remittance reports

This Skill is especially useful when formats vary across carriers.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Formal accounting reconciliation
- General ledger posting authority
- Producer compensation authorization
- Tax reporting
- Payroll processing
- Bank reconciliation
- Carrier payment dispute resolution
- Legal advice
- Contract interpretation
- Final commission ownership determination
- Commission plan interpretation unless the governing agreement is supplied

This is a **financial data extraction, normalization, and reconciliation support Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Financial Operations Analysts
- Commission Specialists
- Accounting Specialists
- Agency Operations Managers
- Producer Compensation Analysts
- Agency Principals
- Revenue Operations Teams
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Commission statement or commission statement text**

Recommended format:

```text
Input:
[PASTE STATEMENT]
```

The input may include:

- PDF text
- Spreadsheet rows
- Carrier portal export
- OCR output
- Statement tables
- Remittance text
- Transaction detail
- Statement summary

If the source is incomplete or unreadable, identify the limitation.

---

# Recommended Inputs

The following information materially improves extraction and reconciliation:

- Carrier name
- Statement date
- Statement period
- Agency name
- Agency code
- Producer codes
- Carrier policy numbers
- Customer names
- Transaction dates
- Effective dates
- Policy periods
- Line of business
- Written premium
- Transaction premium
- Commission rate
- Gross commission
- Net commission
- Producer split
- Producer name
- Adjustment type
- Chargeback
- Bonus payment
- Statement total
- Payment total
- Check / EFT reference
- Prior statement
- Agency commission rules
- Producer compensation agreement
- Expected carrier commission rate

---

# Preferred Source Documents

Where available, prioritize:

1. Original carrier-issued commission statement
2. Carrier portal export
3. Carrier transaction detail
4. Carrier payment / remittance advice
5. Agency accounting record
6. AMS commission record
7. Producer compensation schedule
8. Internal commission worksheet
9. Historical statements

Do not treat internal calculated values as carrier-issued values unless clearly labeled.

---

# Document Completeness Standard

Classify the available commission data as:

### Complete Enough for Extraction

The statement contains sufficient transaction-level information to create a structured dataset.

### Partially Complete

Useful extraction is possible, but one or more important fields or pages are missing.

### Fragmentary

The source is too incomplete or unreadable for reliable transaction extraction.

If the document is incomplete:

- State what was reviewed
- Identify missing pages or sections if apparent
- Limit reconciliation conclusions accordingly

---

# Document Interaction / Override Standard

Commission documents may include:

- Original transaction
- Correction
- Reversal
- Rebill
- Chargeback
- Adjustment
- Supplemental payment

Do not interpret each row independently when another transaction reverses or modifies it.

Where transaction relationships are visible:

1. Identify the original transaction
2. Identify the adjustment
3. Preserve both records
4. Identify the net financial effect
5. Do not delete the original row simply because a reversal exists

---

# Source Hierarchy

When values conflict, prioritize:

1. Current carrier transaction detail
2. Current carrier statement
3. Carrier remittance documentation
4. Agency accounting record
5. AMS record
6. Internal worksheet
7. Historical data
8. Professional inference

When sources conflict:

- Flag the discrepancy
- Do not silently select a value
- Use the most authoritative source for provisional reporting
- Route material financial discrepancies for review

---

# Evidence Classification

Every extracted field should be treated internally as one of the following.

## Directly Stated

Appears explicitly on the carrier statement.

Example:

> Commission Amount: $425.00

---

## Calculated

Derived from source values.

Example:

> $425 commission ÷ $5,000 premium = 8.5%

---

## Inferred

Likely based on context but not explicitly stated.

Example:

> Producer assignment appears associated with producer code RM1.

Inferred fields must be clearly labeled.

---

## Missing

Not provided.

---

## Ambiguous

Multiple interpretations are possible.

---

## Requires Reconciliation

A value conflicts with totals, prior data, or another transaction.

---

# Confidence Classification

Where useful:

### High Confidence

Field is directly stated and internally consistent.

### Moderate Confidence

Field is derived from reliable values.

### Low Confidence

Field depends on ambiguous formatting, incomplete source data, or inference.

---

# Core Principle

## Extract First. Reconcile Second. Never Guess.

Commission processing should preserve the distinction between:

- What the carrier stated
- What was calculated
- What was inferred
- What remains unresolved

A clean-looking table is not valuable if the underlying numbers cannot be trusted.

---

# Execution Readiness Standard

Before producing a reconciliation-ready dataset, classify the source as:

### Ready

Transaction data is sufficiently complete and legible.

### Conditionally Ready

Extraction is possible, but material fields or totals remain unresolved.

### Not Ready

The document quality or completeness is insufficient for reliable extraction.

Do not force producer splits or transaction values when the statement does not support them.

---

# Workflow State Standard

Relevant workflow states may include:

1. Statement Received
2. Statement Validated
3. Extraction In Progress
4. Extracted
5. Reconciliation In Progress
6. Reconciled
7. Exceptions Identified
8. Waiting on Carrier
9. Waiting on Internal Review
10. Approved for Posting
11. Posted
12. Closed

Do not confuse:

> Extracted

with:

> Reconciled.

---

# Workflow

## Step 1 — Identify Statement Metadata

Capture when available:

- Carrier
- Statement date
- Statement period
- Agency
- Agency code
- Payment method
- Check / EFT number
- Statement total
- Number of transactions

---

## Step 2 — Identify the Transaction Grain

Determine whether each row represents:

- Policy
- Invoice
- Premium transaction
- Endorsement
- Installment
- Renewal
- New business
- Cancellation
- Reversal
- Adjustment
- Commission-only transaction
- Bonus

Do not assume every row is a unique policy.

---

## Step 3 — Identify Carrier Name

Extract the carrier as stated.

If the statement comes from:

- Parent company
- Writing company
- Program administrator
- MGA

preserve the source name and writing company separately where available.

---

## Step 4 — Identify Policy or Transaction Identifier

Capture:

- Policy number
- Certificate number
- Account number
- Invoice number
- Transaction ID
- Carrier reference

Preserve leading zeros and formatting where possible.

Do not normalize identifiers in a way that changes meaning.

---

## Step 5 — Identify Insured / Account

Where available, capture:

- Named insured
- Customer
- Account name

Do not infer client identity solely from policy number if not supplied.

---

## Step 6 — Identify Line of Business

Where visible, capture:

- Commercial Auto
- Workers' Compensation
- General Liability
- Property
- BOP
- Personal Auto
- Homeowners
- Benefits
- Other line

Do not fabricate LOB from premium size or policy number patterns unless a validated carrier mapping exists.

---

## Step 7 — Identify Transaction Type

Classify when possible:

- New Business
- Renewal
- Endorsement
- Audit
- Cancellation
- Reinstatement
- Installment
- Adjustment
- Reversal
- Chargeback
- Supplemental
- Bonus
- Other

If unclear, use:

`Unknown / Requires Review`

---

## Step 8 — Identify Premium Amount

Capture the premium amount associated with the transaction.

Possible fields include:

- Written premium
- Transaction premium
- Collected premium
- Earned premium
- Billed premium

Do not treat these as interchangeable.

Where the statement does not define the premium basis, preserve the carrier label.

---

# Premium Basis Standard

When multiple premium fields exist, identify the basis.

Example:

| Premium Type | Amount |
|---|---:|
| Written Premium | $5,000 |
| Transaction Premium | $1,250 |

Do not simply output:

> Premium = $5,000

if the source contains multiple premium concepts.

---

## Step 9 — Identify Commission Amount

Capture:

- Gross commission
- Net commission
- Adjustment
- Commission paid
- Commission earned

Preserve sign:

- Positive amount
- Negative amount
- Zero

Negative commissions may represent:

- Cancellation
- Chargeback
- Reversal
- Audit
- Correction

Do not automatically label every negative amount a chargeback.

---

## Step 10 — Identify Commission Rate

If the rate is explicitly stated, capture it.

If it is not stated but can be calculated reliably:

```text
Commission Rate = Commission Amount / Relevant Premium Amount
```

Label calculated rates as:

`Calculated`

Do not calculate a rate when the premium basis is ambiguous.

---

# Calculation Integrity Standard

When calculating commission percentages:

- Use the correct premium basis
- Preserve negative signs
- Do not divide by zero
- Do not calculate from ambiguous premium
- Avoid excessive decimal precision
- Label calculated rates
- Reconcile calculated rate against stated rate when both exist

If calculated and stated rates differ materially, flag the transaction.

---

## Step 11 — Identify Producer Information

Capture when available:

- Producer name
- Producer code
- House account
- Split percentage
- Split amount
- Secondary producer
- Team assignment

Do not assume a producer based solely on prior account ownership unless the Skill is supplied with a governing producer assignment source.

---

# Producer Split Standard

Producer splits may appear as:

### Explicit Split

The statement directly states:

- Producer
- Percentage
- Amount

### Derived Split

The split can be mathematically derived from explicit statement values.

### Inferred Split

A producer appears associated with the account, but the split is not stated.

Only **Explicit** and reliably **Derived** splits should be treated as reconciliation-ready.

Inferred splits should be flagged.

---

## Step 12 — Distinguish Carrier Commission From Producer Compensation

Carrier commission and producer compensation are different concepts.

Example:

Carrier pays agency:

> $1,000 commission

Producer agreement may pay producer:

> 40% of agency commission

The statement may show only the carrier commission.

Do not assume the carrier commission amount equals producer compensation.

---

# Compensation Boundary Standard

Do not calculate producer compensation unless:

- Producer compensation rules are supplied
- Split basis is known
- Applicable transaction type is known
- House splits or overrides are known where relevant

If compensation rules are not provided, output only the carrier-side commission information.

---

## Step 13 — Identify Reversals and Adjustments

Look for:

- Reversal
- Void
- Chargeback
- Cancellation
- Reinstatement
- Correction
- Prior period adjustment

Preserve all transactions.

Where possible, link related transactions.

---

## Step 14 — Detect Duplicate Transactions

Review for likely duplicates using:

- Policy number
- Transaction date
- Premium
- Commission
- Transaction ID
- Insured

Do not automatically delete duplicates.

Classify:

### Likely Duplicate

Strong evidence of duplication.

### Possible Duplicate

Similar but not conclusive.

### Distinct Transaction

Separate transaction supported by detail.

---

## Step 15 — Reconcile Statement Totals

Where statement totals exist, compare:

```text
Extracted Commission Total
vs.
Carrier Statement Commission Total
```

and where applicable:

```text
Extracted Premium Total
vs.
Carrier Statement Premium Total
```

Calculate the difference.

---

# Reconciliation Standard

Classify:

### Reconciled

Extracted total matches statement total within the applicable precision.

### Reconciled With Explained Difference

Difference is attributable to a known category such as bonus, fee, or non-policy transaction.

### Out of Balance

Totals do not reconcile.

### Unable to Reconcile

Statement does not provide sufficient summary data.

Never mark a statement reconciled merely because the table looks complete.

---

## Step 16 — Identify Exceptions

Potential exceptions include:

- Missing policy number
- Missing premium
- Missing commission
- Commission amount does not match rate
- Producer split missing
- Duplicate transaction
- Unexplained negative amount
- Statement total mismatch
- Unknown transaction type
- Unclear carrier
- Ambiguous premium basis
- Adjustment without reference
- Unexpected commission rate

---

## Step 17 — Assign Exception Priority

### High

Could materially affect financial posting, producer compensation, or reconciliation.

### Moderate

Should be reviewed but may not prevent posting.

### Low

Informational or formatting issue.

---

## Step 18 — Identify Required Follow-Up

Potential owners:

- Carrier
- Accounting
- Producer
- Account Manager
- Operations
- Finance
- Agency Principal

Do not send every ambiguity back to the carrier if internal records can resolve it.

---

## Step 19 — Produce Structured Output

Output should preserve:

- Source detail
- Normalized values
- Evidence status
- Exceptions
- Reconciliation result

---

# Data Integrity Standard

Before finalizing, assess:

- Missing values
- Duplicate rows
- Conflicting transaction amounts
- Sign errors
- Decimal issues
- OCR errors
- Broken table rows
- Misaligned columns
- Inconsistent policy numbers
- Totals that do not reconcile
- Mixed statement periods

Do not silently correct material financial data.

---

# Data Normalization Standard

Safe normalization may include:

- Standardizing date format
- Standardizing currency format
- Standardizing carrier names
- Standardizing LOB labels
- Standardizing transaction types
- Trimming whitespace
- Normalizing producer-code formatting

Do not silently:

- Change policy numbers
- Change premium amounts
- Change commission amounts
- Fill missing splits
- Merge accounts
- Remove negative transactions
- Drop duplicate-looking rows

without support.

---

# Comparison Basis / Like-for-Like Standard

When comparing commission statements across periods:

Confirm whether the comparison uses the same:

- Carrier
- Statement period length
- Business mix
- Premium basis
- Commission type
- Producer population
- Transaction type

Do not describe commission growth as rate improvement when growth may be driven by premium volume.

---

# Governance / Conflict Prevention Standard

Before posting or updating systems:

Check for:

- Duplicate imported statement
- Previously posted transaction
- Existing correction
- Open reconciliation
- Producer split override
- Prior-period adjustment
- Duplicate carrier payment

Avoid double posting.

---

# Ownership Standard

Every exception should have an owner.

Example:

| Exception | Owner |
|---|---|
| Missing producer split | Finance / Producer Compensation |
| Carrier total mismatch | Accounting |
| Unclear policy number | Operations |
| Unexplained carrier adjustment | Carrier / Accounting |

---

# Stop Rules

Stop automated reconciliation and escalate when:

- Statement totals materially fail to reconcile
- Commission rate appears implausible
- Producer split conflicts with governing compensation data
- Duplicate payment is suspected
- Source document is materially incomplete
- OCR or parsing uncertainty could change financial values
- Posting would create financial risk

Accuracy takes priority over automation throughput.

---

# Completion Criteria Standard

Commission extraction is complete when:

1. All readable transactions are captured
2. Carrier and statement metadata are recorded
3. Policy identifiers are preserved
4. Premium amounts are captured where provided
5. Commission amounts are captured
6. Producer split status is identified
7. Adjustments and negatives are preserved
8. Exceptions are documented
9. Statement reconciliation status is determined

If used in an operational posting workflow, completion may additionally require:

10. Exceptions resolved or approved
11. Transactions approved for posting
12. Accounting / AMS import completed
13. Posting totals reconciled to carrier payment
14. Producer compensation workflow initiated where applicable

Do not treat extraction as final financial posting.

---

# Decision Rules

## Accuracy Over Completion

Missing values should remain missing.

---

## Never Guess Producer Splits

If producer allocation is not stated or supported, flag it.

---

## Preserve Negative Transactions

Do not remove reversals or chargebacks.

---

## Do Not Merge Transactions Without Evidence

Similar rows may represent separate installments or endorsements.

---

## Premium and Commission Must Remain Distinct

Do not confuse the transaction premium with commission.

---

## Carrier Commission Is Not Producer Compensation

Keep the concepts separate.

---

## Calculated Rates Must Be Labeled

A calculated commission rate is not the same as a carrier-stated rate.

---

## Totals Must Reconcile Before Final Posting

Where summary totals exist, compare them.

---

# Materiality / Prioritization Framework

Prioritize commission exceptions using:

| Factor | Question |
|---|---|
| Financial Impact | Could this materially affect agency revenue? |
| Producer Impact | Could this affect producer compensation? |
| Reconciliation Impact | Does it prevent statement balancing? |
| Posting Risk | Could this create an incorrect accounting entry? |
| Duplicate Risk | Could the transaction be posted twice? |
| Evidence Strength | How reliable is the source value? |
| Frequency | Is the issue isolated or systemic? |

---

# Authority vs. Inference Standard

Distinguish:

### Carrier-Stated Data

Values from the carrier statement.

### Calculated Data

Values mathematically derived from the carrier statement.

### Internal Agency Data

Values from accounting, AMS, or compensation systems.

### AI Inference

Interpretation of ambiguous source material.

### Decision Authority

Accounting, finance leadership, agency principal, carrier, or authorized compensation administrator.

AI extraction does not constitute financial approval.

---

# Human Review Escalation Standard

Require human review before posting when:

- Statement is out of balance
- Producer split is ambiguous
- Large negative adjustment appears
- Duplicate payment is suspected
- Material commission rate discrepancy exists
- Bonus or contingency payment is unclear
- Source quality may have changed monetary values
- Large producer compensation impact exists
- Prior-period correction is involved
- Transaction cannot be mapped confidently

---

# Output Requirements

Use the following structure unless the user requests another format.

# Insurance Commission Statement Extraction

## 1. Extraction Readiness

**Status:** Ready / Conditionally Ready / Not Ready

**Carrier:** [Carrier]  
**Statement Date:** [Date]  
**Statement Period:** [Period]  
**Agency Code:** [If available]

---

## 2. Statement Summary

**Total Transactions:** [ ]  
**Statement Premium Total:** [ ]  
**Extracted Premium Total:** [ ]  
**Statement Commission Total:** [ ]  
**Extracted Commission Total:** [ ]  
**Difference:** [ ]  
**Reconciliation Status:** Reconciled / Explained Difference / Out of Balance / Unable to Reconcile

---

## 3. Commission Transactions

| Carrier | Insured / Account | Policy / Identifier | Transaction Type | Premium Amount | Commission Rate | Commission Amount | Producer | Producer Split | Evidence / Notes |
|---|---|---|---|---:|---:|---:|---|---|---|
| [Carrier] | [Account] | [Policy] | [Type] | [$] | [%] | [$] | [Producer] | [Split] | [Notes] |

If a field is unavailable, use:

`Not shown`

Do not guess.

---

## 4. Adjustments / Reversals

| Policy / Identifier | Transaction Type | Premium Impact | Commission Impact | Related Transaction | Notes |
|---|---|---:|---:|---|---|

Omit if none exist.

---

## 5. Producer Split Review

| Policy / Identifier | Producer | Split Status | Split % / Amount | Basis | Review Needed |
|---|---|---|---|---|---|
| [Policy] | [Producer] | Explicit / Derived / Inferred / Missing | [Value] | [Source] | Yes / No |

---

## 6. Exceptions

| Priority | Policy / Transaction | Exception | Financial Impact | Owner | Recommended Action |
|---|---|---|---|---|---|
| High / Moderate / Low | [ID] | [Issue] | [If known] | [Owner] | [Action] |

---

## 7. Reconciliation Summary

Provide a concise explanation of:

- Whether the statement balances
- What differences remain
- Whether those differences are explained
- Whether the dataset is ready for posting or requires review

---

## 8. Recommended Next Steps

| Priority | Action | Owner | Completion Requirement |
|---|---|---|---|
| 1 | [Action] | [Owner] | [Requirement] |

---

# Machine-Readable Output Option

When requested, also produce a normalized dataset using fields such as:

```text
carrier_name
statement_date
statement_period
agency_code
insured_name
policy_number
transaction_id
transaction_date
transaction_type
line_of_business
premium_type
premium_amount
commission_rate
commission_rate_source
commission_amount
producer_name
producer_code
producer_split_percent
producer_split_amount
producer_split_source
adjustment_flag
reversal_flag
source_confidence
exception_flag
exception_reason
```

Do not create values for fields that are not supported by the statement.

---

# Assumptions & Items Requiring Confirmation

| Assumption / Ambiguity | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Item] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Correct carrier is identified
- [ ] Statement date / period is identified where available
- [ ] All readable transaction rows are captured
- [ ] Policy numbers preserve formatting
- [ ] Premium basis is identified where possible
- [ ] Commission amount is captured accurately
- [ ] Negative transactions are preserved
- [ ] Commission rates are labeled as stated or calculated
- [ ] Calculated rates use the correct denominator
- [ ] Producer splits are not guessed
- [ ] Carrier commission is not confused with producer compensation
- [ ] Reversals and adjustments are identified
- [ ] Duplicate transactions are reviewed
- [ ] Statement totals are reconciled where possible
- [ ] Exceptions are prioritized
- [ ] Financial discrepancies are not silently corrected
- [ ] Dataset readiness is stated
- [ ] Human review is triggered when required
- [ ] Extraction is not confused with final posting

---

# Failure Conditions

The Skill should not be considered complete if:

- Commission values are guessed
- Producer splits are fabricated
- Negative transactions are omitted
- Policy numbers are changed incorrectly
- Premium and commission are confused
- Commission rate is calculated from an ambiguous premium basis
- Duplicate-looking transactions are deleted without evidence
- Carrier commission is treated as producer compensation
- Statement totals are available but not checked
- Out-of-balance statements are treated as reconciled
- Ambiguous rows are silently interpreted
- Financially material exceptions are not identified

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Fabricate Financial Data

Never invent:

- Premium
- Commission
- Commission rate
- Policy number
- Producer
- Producer split
- Carrier
- Transaction type
- Statement total

---

## Do Not Silently Correct Monetary Values

If the source appears incorrect or unclear:

- Preserve the source value
- Flag the issue
- Recommend confirmation

---

## Do Not Guess Producer Compensation

Carrier payment data alone does not establish producer compensation.

---

## Do Not Delete Reversals

Preserve transaction history.

---

## Do Not Post Financial Data Without Appropriate Authority

This Skill may prepare reconciliation-ready output.

Posting authority remains with authorized financial personnel or systems.

---

## No Tax or Legal Advice

Commission records may have accounting or tax consequences.

Do not provide unsupported legal or tax conclusions.

---

## Protect Confidential Information

Do not unnecessarily expose:

- Bank account information
- Tax IDs
- Personal financial information
- Producer compensation details outside authorized audiences
- Credentials
- Confidential agency financial information

---

## Preserve Human Accountability

This Skill supports financial operations.

The authorized accounting, finance, agency operations, producer compensation, or carrier personnel remain responsible for:

- Final reconciliation
- Financial posting
- Producer compensation
- Corrections
- Carrier disputes
- Accounting treatment
- Tax treatment
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced insurance financial operations analyst.

The tone should be:

- Precise
- Structured
- Objective
- Financially disciplined
- Concise
- Audit-friendly
- Non-speculative

Avoid:

- Guessing
- Loose terminology
- Unexplained calculations
- Hidden corrections
- Generic commentary
- Mixing carrier commission with producer compensation

The output should be easy for finance or accounting personnel to verify.

---

# Example

## Example Request

```text
Input:

Carrier: Summit Insurance
Statement Date: 08/15/2026
Agency: Apex Insurance Services

Policy              Insured                  Premium      Comm %      Commission
CPP100245            Smith Manufacturing      12,500.00    12.00       1,500.00
BA200398             Jones Logistics           8,200.00    10.00         820.00
WC300129             Alpine Construction      -4,000.00    10.00        -400.00
GL400881             Valley Foods              6,000.00                 720.00

Producer:
CPP100245 — RM — 50%
BA200398 — KM — 40%
```

---

## Example Output

# Insurance Commission Statement Extraction

## 1. Extraction Readiness

**Status:** Ready  
**Carrier:** Summit Insurance  
**Statement Date:** 08/15/2026

---

## 2. Commission Transactions

| Carrier | Insured / Account | Policy / Identifier | Transaction Type | Premium Amount | Commission Rate | Commission Amount | Producer | Producer Split | Evidence / Notes |
|---|---|---|---|---:|---:|---:|---|---|---|
| Summit Insurance | Smith Manufacturing | CPP100245 | Not shown | $12,500.00 | 12.00% | $1,500.00 | RM | 50% | Split explicitly stated |
| Summit Insurance | Jones Logistics | BA200398 | Not shown | $8,200.00 | 10.00% | $820.00 | KM | 40% | Split explicitly stated |
| Summit Insurance | Alpine Construction | WC300129 | Adjustment / negative transaction requires confirmation | -$4,000.00 | 10.00% | -$400.00 | Not shown | Not shown | Negative transaction preserved |
| Summit Insurance | Valley Foods | GL400881 | Not shown | $6,000.00 | 12.00% calculated | $720.00 | Not shown | Not shown | Rate calculated from premium and commission |

---

## 3. Producer Split Review

| Policy / Identifier | Producer | Split Status | Split % / Amount | Basis | Review Needed |
|---|---|---|---|---|---|
| CPP100245 | RM | Explicit | 50% | Statement | No |
| BA200398 | KM | Explicit | 40% | Statement | No |
| WC300129 | Not shown | Missing | Not shown | Statement | Yes |
| GL400881 | Not shown | Missing | Not shown | Statement | Yes |

The statement does not provide enough information to calculate producer compensation for the transactions without explicit splits or a separate producer compensation schedule.

---

## 4. Exceptions

| Priority | Policy / Transaction | Exception | Recommended Action |
|---|---|---|---|
| Moderate | WC300129 | Negative premium and commission transaction; transaction type not stated | Confirm whether cancellation, audit, reversal, or other adjustment |
| Moderate | GL400881 | Commission rate not explicitly stated | Confirm if 12% calculated rate is expected |
| Moderate | WC300129 | Producer split missing | Review internal compensation record if required |
| Moderate | GL400881 | Producer split missing | Review internal compensation record if required |

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a financial operations analyst responsible for extracting and organizing commission data from carrier statements into a clean, structured format.
>
> Review the input below and identify all relevant commission-related information. Focus on accuracy, consistency, and clarity.
>
> Input:
> [PASTE STATEMENT]
>
> Interpret the document as needed, recognizing that formats may vary by carrier. Where data is unclear or missing, note it appropriately rather than guessing.
>
> Present the output as a clean, structured table including:
>
> - Carrier name
> - Policy number or identifier
> - Premium amount
> - Commission amount
> - Producer splits (if visible or implied)
>
> Ensure the table is easy to read and suitable for internal reconciliation or reporting.

---

# Evolution From Prompt to Skill

The original prompt established the goal of extracting commission-related data into a structured table.

This Skill expands that prompt into a reusable Revenue Intelligence workflow by adding:

- Statement metadata extraction
- Document completeness review
- Transaction-grain identification
- Source hierarchy
- Evidence classification
- Commission and premium separation
- Premium Basis Standard
- Calculation Integrity Standard
- Producer Split Standard
- Compensation Boundary Standard
- Adjustment and reversal handling
- Duplicate transaction detection
- Statement reconciliation
- Reconciliation Standard
- Exception prioritization
- Data Integrity Standard
- Data Normalization Standard
- Like-for-like comparison controls
- Governance / duplicate posting prevention
- Workflow state
- Ownership
- Stop rules
- Completion criteria
- Authority vs. Inference Standard
- Human Review Escalation Standard
- Machine-readable output option
- Financial operations guardrails
- Example implementation

The purpose is to transform a commission-extraction prompt into a reusable **Commission Intelligence Skill** capable of supporting future AI Teammates for commission processing and reconciliation.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Insurance Exposure Summary Builder](../08-exposure-summary-builder/SKILL.md)
- [Commercial Insurance Client Service Response](../15-client-service-response/SKILL.md)
- Commission Reconciliation
- Producer Compensation Calculation
- Carrier Statement Import
- Revenue Exception Analysis
- Commission Variance Detection
- Accounting Posting Preparation

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Extract and reconcile this Insurance Commission Statement.

Carrier:
[OPTIONAL]

Statement Period:
[OPTIONAL]

Input:
[PASTE STATEMENT]

Known Producer Splits:
[OPTIONAL]

Expected Commission Rates:
[OPTIONAL]

Prior Statement / Accounting Data:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Input:
[PASTE STATEMENT]
```

---

# Version History

## 1.0.0

Initial public release using the Apeironix Gold Standard Template v2.1.

Enhancements from the original Prompt #18 include:

- Structured commission extraction
- Premium-basis handling
- Commission-rate validation
- Producer split classification
- Carrier commission vs. producer compensation separation
- Reversal and adjustment handling
- Duplicate detection
- Statement reconciliation
- Exception management
- Data integrity controls
- Workflow state
- Posting governance
- Completion criteria
- Financial human-review triggers
- Machine-readable schema
- Example implementation

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Revenue operations
- Financial analysis
- Reconciliation
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
