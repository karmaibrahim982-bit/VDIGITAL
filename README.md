# Veralex Landing — Image Slots

Drop the final image files in this folder using these exact names — the page already
references them via CSS `background-image`, so nothing else needs to change once a file lands here.

## Required (wired into the page already)
- `hero-veralex-saudi.webp` — Hero section background (`.hero`)
- `about-office-veralex.webp` — Credibility panel background (`.cred-panel`, "من نحن" section)
- `industries-medical-veralex.webp` — Feature industry tile background (`.iv1`, medical/clinics card)

## Optional (not wired yet — phase two)
- `engine-dashboard-veralex.png` (transparent background)
- `proof-clinic-veralex.webp`
- `proof-realestate-veralex.webp`
- `proof-amazon-veralex.webp`

Each required slot is layered as `gradient, url(image), fallback-gradient` in CSS, so the
page renders correctly (gradient-only) even before the real file is added — dropping the
file in with the right name is the only step needed to activate it.
