# Chiripal Squash Excellence Programme: website design preview

A clickable, static design preview of the CSEP website. Open `index.html` in a browser; it needs no build step and no server.

## Pages

| File | Page |
|---|---|
| `index.html` | Home: hero, impact stats, upcoming competitions, the four pillars, Champions, news (pop-ups), Instagram, Centre of Excellence interest form, partners, contact form |
| `competitions.html` | Competition calendar, 2025–26 season stats, past results, event hub (Overview / Entries / Draws / Results) |
| `champions.html` | Champions squad with filters, athlete profiles (SRFI rankings, Oct 2026), apply-for-selection form |
| `clinics.html` | Clinic sign-up, High Performance Camp, clinic gallery |

## Status

- **Design preview only.** Forms show a confirmation but do not send or store anything.
- Text in `[BRACKETS]` is a placeholder still to be confirmed.
- SRFI rankings and Instagram posts are a snapshot from October 2026; the production build should pull them automatically.
- Partner logos are cropped from the impact report; replace them with official files before launch.
- Fonts load from Google Fonts (Barlow Condensed as a stand-in for Proxima Nova Extra Condensed, and DM Sans).

## Production build (next phase)

Next.js with a headless CMS, so the team can update competitions, results, news and athletes. Form submissions go to email or a CRM, and SRFI rankings and Instagram sync automatically.
