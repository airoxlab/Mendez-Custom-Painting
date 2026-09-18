# Mendez Custom Painting Company

Single-page website for Mendez Custom Painting Company — a licensed C-33 painting contractor
based in Marina, California, serving the Monterey Peninsula.

- **CSLB license:** #1155803, C-33 Painting & Decorating, issued 05/27/2026
- **Based:** Carmel Ave, Marina, CA
- **Status:** Sole owner; contractor bond and workers' compensation both active
- **Service area:** Marina, Seaside, Monterey, Pacific Grove, Carmel, Del Rey Oaks,
  Sand City, Salinas, Castroville

Services: interior painting, exterior painting, cabinets and millwork, repaints and turnovers.
Free written estimates.

## Structure

- `index.html` - the complete site (self-contained CSS, no build step)
- `img/` - 9 verified stock photographs of residential painting work, credited in the footer

Nine sections: hero, services, coastal conditions, how it works, why us, the work, areas served,
free estimate, contact. Mobile-first, dark-mode aware.

## Sourcing notes

**No phone number was supplied**, so no `tel:` link appears anywhere. Every call-to-action routes
to the on-page estimate/contact section instead. Add the number to the header button, the CTAs,
and the footer when it's available.

No online presence exists for this business - every search hit for the name is a different
company (Sanger, Selma, San Francisco, Los Angeles). The footer states non-affiliation explicitly.

The CSLB license number is published since it is a matter of public record and verifiable. The
owner's first name is not published anywhere and is deliberately omitted; the site never names
an individual. No review count, years in business, or project claims appear anywhere.

Active workers' comp indicates at least one employee, so the copy refers to a small crew with the
owner on the job - it does not claim a specific crew size.

All photos are verified stock, disclosed in the footer as representative rather than completed
projects.

Open `index.html` in a browser, or deploy the folder as-is to any static host.
