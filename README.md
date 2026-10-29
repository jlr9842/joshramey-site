# joshramey.com

Josh's portfolio hub. A single static page served by GitHub Pages at https://joshramey.com (www redirects here). It links to each showcase site:

- Race Day: https://raceday.joshramey.com (repo `jlr9842/race-day-site`)
- Pool Position: https://poolposition.joshramey.com (repo `jlr9842/pool-position-site`)

pool.joshramey.com is separate (Firebase Hosting: Pool Position's App Store privacy and support pages). Leave it alone.

## Adding a new showcase site
Every new public showcase site gets a card here. Copy one `<a class="card">` block in `index.html`, give it its own accent color (`--c`), add one landscape screenshot to `img/` (about 1200px wide), and link the subdomain. Newest first. Public pages live only on joshramey.com subdomains, never claude.ai links.

## Unlisted working pages
Some folders are private-ish working pages: not linked from anywhere, `noindex`, and named with a random string so nobody stumbles on them. Don't link them, don't list them in a sitemap or robots.txt, and don't add cards for them. This repo is public, so nothing secret goes in them.

- `ic3ruo2cthzp/`: the pool game shoot, sound and art list (https://joshramey.com/ic3ruo2cthzp/). The content is `list.md` (plain Markdown: `##` sections, `- [ ]` / `- [x]` tick items, `**bold**`, lists, paragraphs, and an `Updated <date>` line under the title). Edit only that file to change the list; `index.html` renders it. Ticks people make on the page are saved on their own phone until `list.md` shows them; the page's "Send to Josh" button shares what they ticked so the list can be updated.
