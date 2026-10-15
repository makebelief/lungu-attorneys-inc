# Lungu Attorneys Inc. — independent website demonstration

A complete nine-page static HTML/CSS/vanilla JavaScript website adapted from the established South African reference code under Wakili wa Tech’s established South African layout system.

## Firm details
- Firm: Lungu Attorneys Inc. (Mmabatho, North West)
- Director: Able Benson Lungu (LLB, MBA, MSc, as publicly listed)
- Contact: 072 667 2337 / lunguattorneysinc@gmail.com
- Office: Suite 3, 0137 Provident Street, Mmabatho, 2735
- Founded: 2024 according to provided logo/artwork.
- Motto: Justice, Integrity, Excellence. Brand slogan “Your Voice in the Courtroom”.

## Preview
Run `python3 -m http.server 8000` in this directory. Open http://localhost:8000.

## User experience
- Responsive page layouts, fixed header, accessible mobile nav (close button, backdrop, Escape, focus trap).
- One floating WhatsApp link to the published mobile. **WhatsApp registration is not independently verified**.
- Contact form prepares a `mailto:` draft; it is **not** a server-backed submission.
- Map is a Google Maps search for the listed street address, not a verified office pin.
- All HTML carries `noindex` until official publication is authorised. Social crawlers are allowed through robots.txt.
- Open Graph preview: /assets/lungu-whatsapp-preview.jpg, 1200x630; firm logo plus a supplied portrait.
- All stock images have distinct Pexels IDs across all pages; download/rights/live loading should be checked before official publication.

## IMPORTANT prior to going live
1. The source/OG canonical URLs assume `lungu-attorneys-inc.vercel.app`, and must be updated if Vercel assigns a different domain.
2. Obtain approval to use brand, portraits and claims in an official public site; this is an independent marketing concept.
3. Verify professional admissions including attorney/notary/conveyancer status with the client or LPC; credentials are public-source / supplied-advertisement statements, not independently checked with the regulator.
4. Confirm WhatsApp availability and actual office map pin.
5. Verify the desktop and mobile rendering, remote Pexels image availability, OG crawler fetch, all external links on the deployed URL.
6. Client to approve privacy statement and remove noindex only when publication is authorised.

## Deploy
No package manager or build step is required. Place the directory at the root of a Vercel “Other” project (static site). Use `vercel --prod` only after client authorises public publication.
