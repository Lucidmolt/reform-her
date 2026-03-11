# ReformHER Pilates Website
A purely static HTML/TailwindCSS frontend site deployed to Vercel.

## Pre-Launch Modifications (Temp Overrides)
The site is currently configured for lead-generation prior to the official launch. Be sure to revert the following temporary changes when the studio officially opens:

1. **Waitlist Section (`#waitlist`)**: 
   - An email capture form (Formspree endpoint: `https://formspree.io/f/xnjgdvzl`) was added above the footer.
   - When the studio launches, decide whether to keep this for a newsletter or remove it entirely.

2. **Class Schedule (`#book`)**: 
   - The Acuity Scheduling embed code was replaced with a temporary "Coming Soon" placeholder box.
   - The "Stay Tuned" button inside this box scrolls down to the `#waitlist` form.
   - *Launch Todo*: Remove the "Coming Soon" box and inject the official Acuity iframe.

3. **Navigation Links ("Book Now" / "View Schedule")**:
   - The primary CTA buttons (Header "Book Now" and Hero "View Schedule") were temporarily repointed from `href="#book"` to `href="#waitlist"`.
   - *Launch Todo*: Repoint these back to `href="#book"` so users scroll to the actual calendar embed.

## Development Commands
To work on this project locally, simply open `index.html` in a web browser. Deployment is automatically handled via pushes to the `main` branch on GitHub.
