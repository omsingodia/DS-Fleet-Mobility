# DS Fleet Mobility — Multi-page website

## Files
- `index.html` — Home
- `school-transport.html` — School student transportation
- `office-commute.html` — Corporate / employee commute
- `rajasthan-travel.html` — Commercial and group travel across Rajasthan
- `about.html` — About DS Fleet Mobility
- `contact.html` — Contact details and WhatsApp enquiry form
- `styles.css` — shared responsive styles
- `script.js` — mobile navigation, FAQ accordion, enquiry form helper
- `assets/ds-fleet-mobility-logo.png` — exact logo image supplied by the user

## Run locally
Open `index.html` in a browser. All page links are relative, so the site can run locally without a database or backend. Internet is needed for Google Fonts and remote Unsplash images.

## Enquiry form
The contact form validates the required fields and opens WhatsApp to `+91 83870 51023` with a pre-filled enquiry message. It does not use a database or save submitted information. Test the WhatsApp link on the target device before publishing.

## Before deployment
- Confirm final text, service coverage and vehicle availability.
- Confirm all images and replace with approved licensed/local images if desired.
- Test phone links, social links and WhatsApp form on mobile and desktop.
- Publish the folder as a static website (e.g. Netlify, Vercel, GitHub Pages or standard hosting).
