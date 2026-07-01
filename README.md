# Chutkima — Rider App (Prototype)

A self-contained, clickable prototype of the **Chutkima** quick-commerce **Rider (driver) app** for Butwal, Nepal — built as a single HTML file (Tailwind + Inter/Hind + FontAwesome), following the Chutkima Scope of Work (Section 04, features 111A–115C).

> Admin-**assigned** order model (no job feed / accept-reject). Brand teal `#0B8570`, NPR currency, single dark store.

## Open it

Just open **[`chutkima_rider_app.html`](chutkima_rider_app.html)** in a browser — no build, no server needed. A left **Simulation Console** lets you push orders and drive every flow.

## What's inside

- **Auth** — Sign In (phone OTP) + 5-step **Sign Up** (phone → OTP → personal → vehicle → KYC documents)
- **Orders** — online/offline + "On Delivery" status, assigned-order list, **incoming popup with Confirm / Reject**
- **Order detail** — Order Journey timeline (Order Placed → Packing → Picked Up → On the Way → Arrived → Delivered) with timestamps, live GPS map, Pickup→Drop route, customer **Trust Badge**, bill summary, admin note, Help/Report (SOS)
- **Pickup flow** — after Confirm the order sits in **Packing** until the store marks it **Ready for Pickup** (auto after packing, or via the sim console); only then is *Swipe → Picked Up* enabled
- **Delivery flow** — swipe step actions, auto "near customer", **COD cash re-confirm**, QR-on-delivery, final delivery confirmation, team (multi-rider) orders
- **Tracking** — **Store arrival ETA** before pickup and **Customer arrival ETA** after pickup (route chips + trip tile), plus a **Live-tracking-visibility** card (who can see the rider during delivery)
- **Earnings** — period segmented control (Week/Month/All), mini bar **chart**, three admin-configurable pay models — **Fuel (KM × NPR 4)**, **Fixed Salary**, **Commission** — and a **daily cash settlement** flow on the cash-to-deposit card
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
