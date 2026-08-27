# Alan Crew Editz — V4 Combined

This combines the original portfolio content with the new purple/blue reference-inspired UI.

Kept from the original:
- Alan Crew Editz branding
- Sri Lanka / Kurunegala info
- Designer / Editor / Developer positioning
- Freelancer & Creative Artist
- About Me text
- Photoshop, Illustrator, Premiere Pro, After Effects, Filmora
- Portfolio Website / Graphic Designs / Video Edits project categories
- Email, Facebook, Instagram and phone contact
- CV button
- Dashboard

Added from the V3 design:
- Purple/blue neon gradient visual system
- Glass navigation
- Glowing profile hero
- Reference-inspired feature sections
- Modern asymmetrical project grid
- Image + YouTube video project cards
- Matching dashboard

Note: dashboard data is currently browser-local. A shared free backend/API is required for publishing changes to GitHub Pages for all visitors.

## Pricing updates
- `pricing.js` is the single source of truth for memberships, video prices, graphic-design prices, bulk discounts and the USD display rate.
- Open `pricing-admin.html` to edit prices, then download `pricing.js`.
- Replace the existing `pricing.js` in your GitHub repository and push the change. `pricing.html` and its calculator will use the new values automatically.


## Contact form + Email app
The contact forms use the visitor’s default email app via `mailto:` and send inquiries to `alancreweditzofficial@gmail.com`. No EmailJS account or API IDs are required. The pricing calculator details are included automatically in the email body.

Package buttons on `pricing.html` open the home page contact form with the selected package pre-filled. WhatsApp opens chat with the portfolio WhatsApp number.
