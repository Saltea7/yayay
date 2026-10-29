# Insulens — reference brief

## What it is

Insulens helps people with diabetes and their doctors work together. Patients add everyday context (food, activity, sleep, stress) next to continuous glucose data. Doctors see real events around the numbers, not only charts. AI points out patterns; it never suggests insulin doses.

## Who it is for

- People with diabetes who already use a continuous glucose monitor (or meter) and want their notes next to their readings.
- Their clinicians, who receive a shared summary through a patient-controlled invite code.

## Feel

**Should feel like:** calm · trustworthy · human

**Should not feel like:** clinical · alarming · game-like

## Visual sources

- Landing: warm apricot brand accent, parchment neutrals, Filament-inspired but not a 1:1 copy (see `.cursor/rules/visual-style.mdc`). Soft SVG shapes allowed. Range-OK green is semantic (in-range / logo status), not the brand colour.
- App prototype: Apple Health structure + Strava-style data (see `.cursor/rules/app-style.mdc`).

## Product decisions (for this build)

- Clickable prototype with made-up data in memory. No real sign-in, Apple Health or backend.
- English copy. Glucose in mmol/L by default (target 3.9–10.0); mg/dL switchable in Settings.
- Light and dark themes.
- One alert red for low glucose only, always with an icon and text.
- Waitlist CTA ("Join the waitlist") — the app has not launched.
- No invented stats, testimonials, logos or clinical claims.

## Landing sections

Header · Hero (with live phone) · How it works · Context on the chart · AI insights · For your doctor · Privacy · FAQ · Waitlist · Footer
