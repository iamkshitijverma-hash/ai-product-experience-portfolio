# Case Study 01 — AI-Guided Shopping for Car Interior Organizers

## 1) Problem
People want a tidy and organized car but shopping for organizers and car dustbins is confusing: too many options, uncertain fit, and safety concerns (airbags, pedals, seatbelts). This causes drop-offs and returns.

## 2) Target users
- Commuters who want essentials organized (keys, sunglasses, cables)
- Parents who need quick access to wipes/snacks
- Rideshare drivers who want a clean, professional interior

## 3) Jobs-to-be-done
- Help me find an organizer that fits my car and doesn’t get in the way
- Make my car feel clean and premium fast
- Keep frequently used items within reach

## 4) Proposed AI solution (Guided Discovery)
An AI assistant that:
1) asks 3–5 fit + use-case questions
2) recommends 3 options (Budget / Best Value / Premium)
3) highlights safety + “measure-first” checks
4) shows “why this recommendation” + trade-offs

## Clarifying questions (asked before recommending)
1) Vehicle type (sedan/SUV/truck) and model/year (if known)
2) Where is the clutter mainly? (front seat / back seat / trunk)
3) What items do you need to store? (phone, wipes, bottles, toys, etc.)
4) Any safety constraints? (child seat, side airbags, pedals, seatbelt access)
5) Your preference: hidden/minimal look vs maximum storage

## 5) UX flow (simple)
Landing → “Find my organizer” → Questions → Recommendations → Compare → Add to cart → Post-purchase setup tips

## 6) Success metrics
Primary:
- Add-to-cart rate from assistant users
- Return rate due to “fit/expectation mismatch”

Secondary:
- Time to decide
- Fewer support tickets about fit
- Higher review sentiment

## 7) Guardrails
- Warn about airbag zones, pedals, seatbelts, child seats, driver visibility
- If uncertain fit: say so + recommend measuring + safer universal options
- Do not invent dimensions or compatibility claims

## 8) MVP scope
- Question flow + 3 recommendations + comparison + safety warnings

## 9) Product scope (what the assistant recommends)
The assistant recommends from 3 product types:
1) Seat gap organizer
2) Backseat organizer
3) Car small dustbin (compact trash can)

For each recommendation it will:
- confirm compatibility (or say uncertain and ask for measurements)
- highlight safety notes (airbags/seatbelts/driver visibility)
- give 3 tiers: Budget / Best Value / Premium

