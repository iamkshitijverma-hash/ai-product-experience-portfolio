# Case Study — AI Guided Shopping Automation (Car Interior Organizers)

## Problem
Customers don’t know what organizer fits their needs; choice overload + safety concerns → drop-offs and returns.

## Solution
An AI-guided shopping assistant workflow that collects user needs, generates structured recommendations (Budget/Best Value/Premium), adds safety notes, logs outputs, and emails results.

## Workflow (MVP)
Google Form → Google Sheets → Make.com → GPT-4.1 mini → JSON → Parse JSON → Update Sheet → Email notification

## Guardrails
- Only recommends: seat gap organizer, backseat organizer, car small dustbin
- No fake compatibility claims; “measure-first” when uncertain
- Safety notes: visibility / airbags / seatbelts / pedals

## What I shipped
- Working Make scenario
- Sheet logging + human-readable columns
- Email notification template

## Success metrics (how I’d measure)
- Add-to-cart uplift for assistant users
- Reduction in “fit/expectation mismatch” returns
- Reduction in “which one should I buy?” support tickets

## Next improvements
- Add real product catalog lookup + prices
- Add feedback buttons + evaluation rubric
- Deploy on site (Shopify form/widget)
