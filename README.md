# Chutkima — Rider App (Prototype)

A self-contained, clickable prototype of the **Chutkima** quick-commerce **Rider (driver) app** for Butwal, Nepal — built as a single HTML file (Tailwind + Inter/Hind + FontAwesome), following the Chutkima Scope of Work (Section 04, features 111A–115C).

> Admin-**assigned** order model (no job feed / accept-reject). Brand teal `#0B8570`, NPR currency, single dark store.

## Open it

Just open **[`chutkima_rider_app.html`](chutkima_rider_app.html)** in a browser — no build, no server needed. A left **Simulation Console** lets you push orders and drive every flow.

## What's inside

- **Auth** — Sign In (phone OTP) + 5-step **Sign Up** (phone → OTP → personal → vehicle → KYC documents)
- **Orders** — online/offline + "On Delivery" status, assigned-order list, **incoming popup with Confirm / Reject**
- **Order detail** — Order Journey timeline (Order Placed → Packing → Picked Up → On the Way → Arrived → Delivered) with timestamps, live GPS map, Pickup→Drop route, customer **Trust Badge**, bill summary, admin note, Help/Report (SOS)
- **Delivery flow** — swipe step actions, auto "near customer", **COD cash re-confirm**, QR-on-delivery, final delivery confirmation, team (multi-rider) orders
- **Earnings** — period segmented control (Week/Month/All), mini bar **chart**, fuel (KM × NPR 4), cash-to-deposit
- **History** — list + tappable **Delivery Receipt** detail (items, bill, customer review)
- **Notifications** centre, **Profile** hub (rating + reviews, Assigned Vehicle, Account Details & KYC, Edit Profile, Language NP/EN, security, About/Privacy/T&C/FAQ)

## Files

| File | Purpose |
|---|---|
| `chutkima_rider_app.html` | The rider app prototype |
| `RIDER_APP_USERFLOW.md` | Full user-flow specification |
| `quick_commerce_rider_dashboard.html` | Original design-system reference mockup |

---
Chutkima Technology Pvt. Ltd. · Butwal, Nepal
