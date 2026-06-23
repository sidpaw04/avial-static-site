Avial static local website - revised luxury version
====================================================

What changed:
- Reduced font sizes and visual scale for a calmer, more premium feel.
- Removed Pricing from the top navigation.
- Converted Platform, For Clubs, About and Contact into separate pages.
- Finished the Home page before any pricing content; no pricing section appears on the homepage.
- Kept the bottle green and beige brand system.
- Kept all resources local: no cross-origin images, scripts, fonts or stylesheets.

How to run locally:
1. Unzip this folder.
2. From inside the folder, run:
   python -m http.server 8000
3. Open:
   http://localhost:8000

How to host:
Upload all files and the assets folder to your web host:
- index.html
- platform.html
- for-clubs.html
- about.html
- contact.html
- privacy-policy.html
- assets/styles.css
- assets/AvialClubLogo.jpeg

Note:
The contact form currently uses mailto:admin@avialclub.com.
For production, replace this with a real form endpoint such as Formspree, Netlify Forms, Tally, HubSpot, Supabase, or your own backend.


v3 changes:
- Removed dot/bullet styling from the hero tagline and Members/Teams/Payments/Finance pills.
- Updated Club communications copy to reflect WhatsApp integration/support rather than avoiding WhatsApp.
- Updated club structure to the hierarchy: Club -> Sections -> Groups -> Teams.
- Updated sections/examples so Cricket, Tennis, Bar & Events and Facilities are treated as Sections.
- Added Men’s, Women’s, Junior and Social examples as Groups.
- Removed cricket-heavy positioning from For Clubs and reframed Avial as configurable for all sports and club types.
