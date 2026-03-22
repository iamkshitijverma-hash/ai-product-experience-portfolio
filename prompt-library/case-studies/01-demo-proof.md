# Demo Proof — AI Guided Shopping Automation (Car Interior Organizers)

## What this is
A workflow that takes customer inputs via a form and automatically generates safe, structured product recommendations.

## How it works (MVP)
Google Form → Google Sheets (new row) → Make.com → GPT-4.1 mini → JSON output → Parse JSON → Update Sheet AI columns

## Why it matters
- Faster customer guidance
- More confident purchases
- Fewer “wrong fit” returns
- Safety-first recommendations (visibility/airbags/seatbelts/pedals)

## What I shipped
- Working automation scenario (Make)
- Output logging in Google Sheets
- JSON schema + parsing
- Guardrails in prompt (no fake compatibility claims)

## Next improvements
- Add email notifications
- Add catalog lookup (real products + prices)
- Add feedback buttons and quality evaluation
