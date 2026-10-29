# joshramey.com

Josh's portfolio hub. A single static page served by GitHub Pages at https://joshramey.com (www redirects here). It links to each showcase site:

- Race Day: https://raceday.joshramey.com (repo `jlr9842/race-day-site`)
- Pool Position: https://poolposition.joshramey.com (repo `jlr9842/pool-position-site`)

pool.joshramey.com is separate (Firebase Hosting: Pool Position's App Store privacy and support pages). Leave it alone.

## Adding a new showcase site
Every new public showcase site gets a card here. Copy one `<a class="card">` block in `index.html`, give it its own accent color (`--c`), add one landscape screenshot to `img/` (about 1200px wide), and link the subdomain. Newest first. Public pages live only on joshramey.com subdomains, never claude.ai links.
