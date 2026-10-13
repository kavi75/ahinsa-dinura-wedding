# Ahinsa & Dinura — Wedding Invitation Website

A responsive, animated static wedding website built with HTML, CSS and JavaScript. No build step or framework is required.

## Preview locally
Open `index.html` in a modern browser. An internet connection is only needed to load the optional Google Fonts.

## Deploy to Vercel
1. Upload `index.html`, `vercel.json`, and this README to the root of a GitHub repository.
2. Import the repository at https://vercel.com/new.
3. Select **Other** as the framework preset.
4. Leave Build Command and Output Directory empty, and set Root Directory to `./`.
5. Deploy. `index.html` must be at the repository root.

## Before sharing with guests
- In `index.html`, find `const rsvpEmail=''` and enter the couple's RSVP email address between the quotes. This enables the email-app RSVP fallback.
- For reliable online RSVP collection (without requiring guests to open an email app), connect a form backend such as Formspree or a serverless endpoint and replace the demo handler.
- Confirm the wedding date, time, venue, and RSVP destination with the couple.

## Design notes
- Sage, ivory, blush and champagne palette inspired by the printed invitation.
- Animated hero atmosphere, floating petals, scroll reveals, live countdown, mobile navigation, venue map link and RSVP form.
- Background ambience is created with CSS, so there are no broken image paths or missing local assets.


## Mobile polish update
The header monogram is constrained to the circle, mobile header alignment is tightened, the hero's vertical spacing is reduced on phones, and the menu button's accessible label updates when opened or closed.
