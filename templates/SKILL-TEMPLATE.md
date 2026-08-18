---
name: skill-name
title: Human-Readable Skill Title
description: A concise description of what this Skill helps accomplish.
category: category-name
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
---

# Skill Title

## Purpose

Clearly explain what this Skill is designed to accomplish.

Describe the business problem or insurance workflow it addresses and the value it should create for the user.

This section should answer:

- What does this Skill do?
- Who is it designed for?
- What business outcome should it produce?

---

## Best Used For

Use this Skill when the user needs help with:

- [Use case 1]
- [Use case 2]
- [Use case 3]
- [Use case 4]

Do not use this Skill when:

- [Out-of-scope situation 1]
- [Out-of-scope situation 2]
- [Situation requiring another Skill, licensed professional, carrier, legal counsel, etc.]

---

## Intended Users

This Skill may be useful for:

- Insurance Producers
- Account Managers
- Account Executives
- Client Service Professionals
- Agency Operations Teams
- Insurance Analysts
- Other authorized insurance professionals

Modify this list based on the specific Skill.

---

## Required Inputs

Before beginning, obtain the information required to complete the workflow.

Required inputs may include:

1. [Required input]
2. [Required input]
3. [Required input]
4. [Required input]

If a required input is missing, identify what is missing before completing any analysis that depends on it.

Do not invent missing insurance information.

---

## Optional Inputs

The following information may improve the quality of the result:

- [Optional input]
- [Optional input]
- [Optional input]
- [Optional input]

If optional information is unavailable, proceed when the required inputs are sufficient.

---

## Source Hierarchy

When multiple sources of information are available, prioritize them according to the needs of this Skill.

Typical hierarchy:

1. Current policy, quote, proposal, schedule, or carrier document
2. Official carrier-issued information
3. Agency Management System or CRM data
4. Client-provided information
5. Prior policy or historical documentation
6. Other supporting information

When sources conflict:

- Identify the discrepancy.
- Do not silently choose one value.
- State which source was used and why.
- Flag material discrepancies for human review.

---

# Workflow

Follow the workflow in order unless the specific circumstances require a documented exception.

## Step 1 — Review the Request

Determine:

- What the user is asking for
- Which client/account/policy is involved
- Which lines of coverage or business are relevant
- The desired output
- Whether sufficient information has been provided

---

## Step 2 — Validate Inputs

Confirm that the required documents and data are present.

Check for:

- Correct named insured
- Correct policy or quote period
- Correct carrier
- Correct line of coverage
- Complete document set
- Relevant schedules, endorsements, or supporting information

Flag missing or potentially outdated information.

---

## Step 3 — Extract Relevant Information

Identify and organize the information needed for the workflow.

Use structured categories whenever possible.

Examples may include:

- Named insured
- Carrier
- Policy number
- Effective dates
- Limits
- Deductibles
- Premium
- Locations
- Vehicles
- Payroll
- Class codes
- Covered employees
- Plan provisions
- Endorsements
- Exclusions
- Conditions
- Other workflow-specific information

Do not infer a value merely because it would normally be expected.

---

## Step 4 — Perform the Analysis

Apply the insurance-specific logic defined for this Skill.

Evaluate the information objectively and consistently.

Where relevant:

- Compare current and proposed terms
- Identify material changes
- Identify gaps
- Identify improvements
- Identify restrictions
- Identify potential client impact
- Distinguish factual findings from professional judgment

---

## Step 5 — Identify Exceptions and Issues

Flag anything requiring additional attention.

Examples:

- Missing information
- Conflicting information
- Material coverage reduction
- Unusual exclusions
- Significant premium changes
- Unclear policy language
- Regulatory considerations
- Carrier-specific requirements
- Items requiring producer or Account Manager judgment

Classify issues when helpful:

### Critical
Potentially significant client, coverage, compliance, financial, or operational impact.

### Important
Should be reviewed before a recommendation or final decision.

### Informational
Useful context but not necessarily decision-changing.

---

## Step 6 — Develop the Output

Present findings in the format defined under **Output Requirements**.

Prioritize:

1. Material findings
2. Client impact
3. Recommended next steps
4. Supporting details

Avoid overwhelming the user with information that does not affect the decision.

---

## Step 7 — Human Review

Before treating the work as final, identify anything requiring professional review.

The AI supports the insurance professional.

It does not replace:

- Licensed insurance judgment
- Carrier underwriting authority
- Legal advice
- Compliance review
- Client authorization
- Binding authority

---

# Decision Rules

Apply the following principles throughout the Skill.

## Accuracy Over Completion

Never invent information simply to complete the workflow.

If information is unavailable, state:

**Not provided**

**Not found**

or

**Requires confirmation**

as appropriate.

---

## Materiality Over Volume

Prioritize information that could materially affect:

- Coverage
- Cost
- Risk
- Compliance
- Client decisions
- Agency operations

Do not treat every difference as equally important.

---

## Facts vs. Recommendations

Clearly distinguish:

### Documented Fact
Information directly supported by the supplied source material.

### Observation
A meaningful pattern, difference, or issue identified from the information.

### Recommendation
A suggested action requiring professional judgment.

---

## No Silent Assumptions

If an assumption is necessary:

1. State the assumption.
2. Explain why it is necessary.
3. Identify what would confirm it.

---

## Current Information Takes Priority

When comparing documents across periods, clearly identify which information is current and which is historical.

Do not present expired information as current.

---

# Output Requirements

Unless the user requests another format, provide the result using the following structure.

## Executive Summary

Briefly explain:

- What was reviewed
- Most important findings
- Overall impact
- Immediate action needed, if any

---

## Key Findings

Present the most important findings in priority order.

Use concise explanations focused on business or client impact.

---

## Detailed Analysis

Use tables where comparison improves understanding.

Example:

| Item | Current | Proposed / Comparison | Impact | Review Needed |
|---|---|---|---|---|
| [Item] | [Value] | [Value] | [Explanation] | Yes / No |

---

## Issues Requiring Attention

Identify:

- Critical issues
- Important issues
- Missing information
- Items requiring human review

---

## Recommended Next Steps

Provide specific actions.

Examples:

1. Confirm [item].
2. Request [document].
3. Review [coverage or term].
4. Discuss [issue] with the client.
5. Obtain carrier clarification.
6. Document the final decision.

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Correct client/account was reviewed
- [ ] Correct policy or plan period was used
- [ ] Required documents were available
- [ ] Material information was captured
- [ ] No unsupported values were invented
- [ ] Material differences were identified
- [ ] Facts and recommendations are clearly distinguished
- [ ] Missing information is clearly disclosed
- [ ] Client-impacting issues are prioritized
- [ ] Output is understandable to the intended insurance professional
- [ ] Items requiring licensed professional review are identified

Add Skill-specific quality checks as needed.

---

# Guardrails

## Do Not Invent Insurance Information

Never fabricate:

- Coverage
- Limits
- Premiums
- Deductibles
- Endorsements
- Exclusions
- Carrier requirements
- Policy provisions
- Client information

---

## Do Not Bind or Alter Coverage

This Skill cannot:

- Bind insurance
- Change coverage
- Confirm carrier acceptance
- Issue a policy
- Guarantee coverage
- Guarantee claim payment

---

## Do Not Provide Legal Advice

Identify contractual, regulatory, or legal issues when relevant, but do not present legal conclusions unless the Skill is specifically supported by authorized legal guidance.

Recommend appropriate professional review when necessary.

---

## Protect Confidential Information

Only use client or agency information necessary to perform the requested workflow.

Do not unnecessarily expose, reproduce, or distribute:

- Personally identifiable information
- Protected health information
- Financial account information
- Credentials
- Confidential client records
- Proprietary agency information

---

## Preserve Human Accountability

The final insurance decision remains with the authorized insurance professional, client, carrier, or other responsible party.

### Your people make the decisions. Your AI Teammates do the work.

---

# Example

## Example Request

> [Provide a short example of how a user might invoke this Skill.]

## Example Inputs

- [Input]
- [Input]
- [Input]

## Example Output

Provide a shortened example demonstrating the expected structure and level of analysis.

Do not use real confidential client information in public examples.

---

# Skill-Specific Notes

Add any additional information unique to this workflow, including:

- Carrier considerations
- Line-of-business rules
- State-specific considerations
- Terminology
- Known limitations
- Related Skills

---

# Related Skills

When applicable:

- `[related-skill-name](../path-to-related-skill/SKILL.md)`
- `[related-skill-name](../path-to-related-skill/SKILL.md)`

---

# Version History

## 1.0.0

- Initial public release.

---

## About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for judgment, relationships, service, and growth while AI handles more of the repetitive work.

**Keep your systems. Activate an AI Workforce.**

Learn more at [Apeironix.com](https://apeironix.com).

---

## License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
