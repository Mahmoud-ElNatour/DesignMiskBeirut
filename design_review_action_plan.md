# Misk Beirut Website — Design Review Action Plan
Source: Fatima Shoukeir feedback, 2026-07-12

Legend: **[Blocked]** = needs client input (copy/photos/facts) before it can be finished in code. **[Code]** = can be done now in the repo.

## P0 — Structural / navigation (do first, touches every page)
1. **[Code]** Rework primary nav from `Home – About Us – Services – Careers – Contact Us` to `Home – About Misk – Our Spaces – Menu – Events – Reservations – Contact`.
   - Move Careers out of main nav → footer link + small homepage banner only.
   - Move F&B consultancy out of main nav → own page or under a "Business Services" grouping, not competing with restaurant nav.
   - Files: nav markup is likely duplicated across all `*/code.html` pages — audit each: [index.html](index.html), [misk_beirut_home_refined_spacing/code.html](misk_beirut_home_refined_spacing/code.html), [about_misk_beirut_photo/code.html](about_misk_beirut_photo/code.html), [about_misk_beirut_video/code.html](about_misk_beirut_video/code.html), [careers_misk_beirut/code.html](careers_misk_beirut/code.html), [contact_us_final_prototype_restored_fixed/code.html](contact_us_final_prototype_restored_fixed/code.html), [f_b_consultancy_services_final_prototype/code.html](f_b_consultancy_services_final_prototype/code.html), [our_services_main_hub_final_prototype/code.html](our_services_main_hub_final_prototype/code.html), [venue_event_spaces_final_prototype/code.html](venue_event_spaces_final_prototype/code.html)
2. **[Code]** Reorder homepage sections to: Hero → Short intro → Food & drinks → Spaces/experiences → Events & match screenings → Private events/celebrations → Instagram/social gallery → Real reviews → Location/hours/contact → Small careers banner → Footer.
   - File: [misk_beirut_home_refined_spacing/code.html](misk_beirut_home_refined_spacing/code.html)
3. **[Code]** Shrink Careers section on homepage to a small banner; move full content to dedicated [careers_misk_beirut/code.html](careers_misk_beirut/code.html) page (already exists — just needs to be linked, not embedded).

## P1 — New/missing sections (code work, but copy is placeholder until client content lands)
4. **[Code+Blocked]** Add "A Taste of Misk" food & drinks section to homepage with dish/drink/dessert/shisha photography + "View Menu" CTA. Needs real photos + menu link.
5. **[Code+Blocked]** Add events & match-screening section (upcoming matches, special nights, live entertainment, seasonal offers, private events) — needs to be easy to update from backend/CMS later; static placeholder for now.
6. **[Code]** Split "What We Offer" ([misk_beirut_home_refined_spacing/code.html:229](misk_beirut_home_refined_spacing/code.html)) into distinct categories: Dining & Shisha / Indoor & Outdoor Spaces / Private Events & Celebrations / Football & Live Screenings / Work & Casual Meetings — each with its own photo + CTA. Separate this from F&B consultancy content entirely.
7. **[Blocked]** Real testimonials — current ones are generic placeholders. Need actual Google reviews / verified quotes + rating count from client before swapping in.

## P2 — Copy fixes (can do now, no client input needed)
8. **[Code]** Typo fix: "enviroment" → "environment" — [misk_beirut_home_refined_spacing/code.html:241](misk_beirut_home_refined_spacing/code.html)
9. **[Code]** Update footer copyright year to 2026.
10. **[Blocked]** Rewrite hero headline/subhead (currently "Welcome to Misk Beirut" / "Where heritage meets culinary excellence" — [misk_beirut_home_refined_spacing/code.html:175](misk_beirut_home_refined_spacing/code.html)) — needs client-approved brand messaging, but can draft options for review.
11. **[Code, draft now]** Replace vague "Explore More" secondary CTA — [misk_beirut_home_refined_spacing/code.html:180](misk_beirut_home_refined_spacing/code.html) — with one of: "Discover Misk" / "Explore Our Experience" / "View Our Spaces" / "See What's Happening". Pick one, make "Reserve a Table" visually dominant.
12. **[Blocked]** "Our Story" section ([misk_beirut_home_refined_spacing/code.html:198-200](misk_beirut_home_refined_spacing/code.html)) — remove/verify unconfirmed claims ("Since 1982", "generational mastery", family kitchen). Simplify tone, drop overwrought phrasing ("modern epicurean," "editorial precision," "beacon of luxury"). Needs real story facts from client.

## P3 — Contact & conversion
13. **[Code]** Add action buttons to contact section: Call Now, WhatsApp Us, Get Directions, Reserve a Table. Make WhatsApp prominent, especially on mobile. File: [contact_us_final_prototype_restored_fixed/code.html](contact_us_final_prototype_restored_fixed/code.html)
14. **[Blocked]** Replace placeholder address, phone, email, opening hours with real client-supplied info (same file).
15. **[Code]** Add sticky WhatsApp/reservation button on mobile; audit mobile layout for tap-target size, text-over-image legibility, section length, image load performance.

## P4 — Arabic version
16. **[Blocked/Code]** Arabic version needs to be a proper localization, not a literal translation: RTL layout, Arabic-friendly type, natural Lebanese/accessible Arabic copy, correct RTL alignment of buttons/menus/icons, clearer EN/AR switch. Depends on Arabic copy from client; RTL layout/CSS work can start once English structure is locked.

## P5 — Imagery
17. **[Blocked]** Full photo shoot needed: real venue, customers/social atmosphere, food & drinks, shisha, football screenings, events/gatherings, indoor/outdoor areas — replacing current stock-style images across all pages.

## Deliverables Fatima also requested (separate from code)
- **Copy spreadsheet**: Excel sheet listing every homepage/section copy field with recommended character limits, for her to fill in and hand back.
- **Photo spec list**: which photos are needed, per section, with required dimensions/file specs.

## Suggested sequencing
1. Nav restructure + homepage section reorder (P0) — no dependencies, do first.
2. Typo/copyright/CTA-label fixes (P2 code-only items) — quick wins.
3. Build the copy spreadsheet + photo spec list (the two deliverables Fatima explicitly asked for) so she can start filling content in parallel with your dev work.
4. New sections (food & drinks, events/match screenings, split "what we offer") — build with placeholder content, swap in real copy/photos as they arrive.
5. Contact section CTAs + mobile sticky WhatsApp button.
6. Arabic localization pass once English copy is finalized.
7. Photo shoot integration — swap stock images once delivered.
