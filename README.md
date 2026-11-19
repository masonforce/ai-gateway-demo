# Contract Servicing Assistant (demo)

A sample project used to demonstrate governed AI agents with Unity AI Gateway.
The assistant answers questions about annuity contract servicing and helps maintain
this repository.

## What the assistant can do

- Explain contract features such as surrender charges, free withdrawals, and
  beneficiary changes
- Summarize files in this repository
- Propose changes through pull requests, which a person must approve

## Guardrails

Every request and response passes through Unity AI Gateway policies:

- Personal data (SSNs, card numbers, emails, phone numbers) is redacted before it
  reaches the model
- Contract numbers are blocked in prompts, responses, and commits
- Prompt-injection attempts are rejected
- The assistant stays on topic and does not give investment advice
- Writes to this repository require human approval, and deletes are not allowed

## Getting started

Customers who want to change a beneficiary should receive a confirmation letter
within five business days.

All data in this repository is fictional.
