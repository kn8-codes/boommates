# BoomMates

> Room rental platform. Craigslist meets Match.com. Akron-first.

---

## What it is

BoomMates is a room rental platform built for people who actually need housing — not investors, not landlords optimizing yield, not out-of-town developers. People who need a room. People who have a room. Making that match work safely, clearly, and with dignity.

The name: BoomMates. As in Rust Belt. As in the boom that left. As in the people who stayed and still need somewhere to live.

---

## The problem

Craigslist is dangerous and unaccountable.
Facebook Marketplace is a privacy nightmare.
Zillow doesn't care about your $600/month budget.
Nobody is building for the people who actually live here.

Housing insecurity in Akron is personal, not theoretical.
This platform comes from lived experience with that.

---

## What it does

- Room listings with real information
- Compatibility matching between hosts and tenants
- Written agreements baked in — not optional
- Tenant and host rights education built into the flow
- AI-assisted mediation (later sprint)
- Landlord and property vetting tools
- Public housing data aggregation — beat the city to it

---

## Who it's for

### Primary segments
- UA (University of Akron) college students
- Travel nurses and clinical interns on 13-week rotations
  - Summa Health
  - Cleveland Clinic Akron General
  - Akron Children's Hospital

### Secondary
- Anyone in Akron needing short or medium term housing
- Hosts with a spare room who want a vetted, matched tenant

---

## Stack

- SvelteKit frontend
- Supabase backend
- Magic Link auth (no passwords by default)
- Vercel deployment

---

## Design principles

- Akron-first. Not built to scale nationally. Built to work here.
- Anonymous-first where possible. Privacy by design.
- Written agreements are not optional. They protect everyone.
- No password auth unless explicitly required. Magic Link default.
- Aggregate public housing data before the city does.
- Civic play — directly relevant to Unify Akron housing proposals.

---

## Civic context

BoomMates exists in direct relationship to the Unify Akron Civic Assembly housing track.

Session 5 proposals (April 16, 2026):
- Public Code Violations Database
- Criminal History as Protected Class

Both are directly relevant to what BoomMates is trying to do. The platform is the technical arm of the housing work. The Civic Assembly is the political arm. They feed each other.

---

## Strategic mental model

BoomMates = foundation.
Stable housing, modest local income, Akron-first, no scale pressure.
This pays rent before anything else does.

Everything else (OLA arbitrage, OBDsidian, agents, Multiverse School) = lab.
Tech aspirations stay out of BoomMates until it's paying rent.

Don't over-engineer this. Don't add features because they're interesting.
Build what makes a match happen safely. That's the product.

---

## What it is NOT

- Not a vacation rental platform
- Not built for landlords with multiple units optimizing yield
- Not trying to be national
- Not adding AI features until the basic match works

---

## V1 scope (rough)

- [ ] Room listings (host creates, tenant browses)
- [ ] Basic compatibility questions
- [ ] Magic Link auth
- [ ] Written agreement template
- [ ] Tenant rights info page
- [ ] Host vetting basics
- [ ] Supabase backend wired

---

## Later sprints

- AI-assisted mediation
- Admin portal
- Public code violations database integration
- Criminal history protected class implementation
- Travel nurse / clinical intern specific flow
- UA student specific flow
- Landlord reputation system
- Public housing data aggregation layer

---

## Repo notes

This README is a scratchpad. It's incoherent in places. That's fine.
GitHub is the source of truth. Push everything. Sort it out later.
Open source is the one true way.

---

## Status

Pre-code. Concept locked. Stack decided. Building when BoomMates is next up.
