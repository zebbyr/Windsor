THE WINDSOR — Q2 2026 INVESTOR BRIEF
Deploy to Vercel (no CLI, no token, ~30 seconds)

1. Go to  https://vercel.com/new
2. Drag this ENTIRE FOLDER (windsor-q2-2026) onto the page.
   - If you are asked for a framework, choose "Other".
   - Do not select just index.html; drop the folder so vercel.json is picked up.
3. Click Deploy. You get a live URL like
   https://windsor-q2-2026.vercel.app

WHAT'S IN HERE
  index.html    the complete brief (all CSS, JS and charts inlined; no external assets)
  vercel.json   sets X-Robots-Tag noindex + basic security headers
  robots.txt    blocks search engine crawling

IMPORTANT — ACCESS CONTROL
A default Vercel URL is PUBLIC. Anyone with the link can read Windsor's
financials. The noindex headers keep it out of Google, but they do not
restrict access.

To require a password, open the project in Vercel and go to
  Settings -> Deployment Protection -> Password Protection
This requires a Vercel Pro plan. If the brief should stay LP-only,
posting it in Juniper Square instead is the safer route.

CUSTOM DOMAIN
Settings -> Domains -> add e.g. investors.brixtoncapital.com,
then add the CNAME Vercel gives you to your DNS.
