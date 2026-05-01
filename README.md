# Elber Ribeiro

Senior software architect in Boca Raton, FL. Healthcare software at [ModMed](https://www.modmed.com)
by day; cozy games and small experiments by night. On GitHub since 2009.

Site: **[dynaum.com](https://dynaum.com)** &nbsp;·&nbsp; Email: **elber@dynaum.com**

---

### Stack I ship in production

`Ruby` · `Elixir` · `Go` · `TypeScript` · `GDScript` · `Terraform` · `PostgreSQL` · `Docker`

I tend to reach for the boring tool first. I care about clear module boundaries,
tests that actually run in CI, and code I can come back to a year later
without wincing.

---

### Currently building

**[Lanterns](https://lanterns.dynaum.com)** &nbsp;·&nbsp; Godot 4 · GDScript · 1–2p local co-op
A cozy bullet-heaven about a Keeper, a swarm of moths, and the soft light that
holds the night together. Browser demo via a DigitalOcean Spaces + Cloudflare
Pages proxy worker; CI builds the Godot web export and syncs to the bucket on
every push to `master`.

**[Sudoku — three models, one game](https://github.com/dynaum/sudoku)** &nbsp;·&nbsp; vanilla JS · zero deps
The same prompt — _"build a fancy responsive Sudoku, no frameworks, no build
step"_ — given to Claude Opus, Sonnet, and Haiku independently. Repo includes
the three implementations side-by-side plus wall-clock and token data per
run. Live: <https://dynaum.github.io/sudoku/>

**[US Visa Guide](https://github.com/dynaum/us-visa)** &nbsp;·&nbsp; Next.js 15 · React 19 · TS · Tailwind v4 · MDX · next-intl
A bilingual (`pt-BR`, `en`) step-by-step companion for first-time B1/B2 visa
applicants in Brazil. Static export, no backend; progress lives in
`localStorage` behind a Zod schema. Vitest for units, Playwright for e2e.
Live: <https://dynaum.github.io/us-visa/>

---

### Infrastructure as code

I run everything personal as Terraform-managed DigitalOcean. The DNS for
`dynaum.com`, `dynaum.com.br`, and a couple of related domains lives in
[`digitalocean-dns`](https://github.com/dynaum/digitalocean-dns); the CDN +
Cloudflare Pages proxy that fronts the Lanterns demo lives in
[`digitalocean-infra`](https://github.com/dynaum/digitalocean-infra).

---

### Earlier work

A long tail of Ruby/Rails OSS contributions, dotfiles, vim config, Docker base
images, and forks I sent PRs against — `cancancan`, `errbit`,
`elasticsearch-rails`, `business_time`, `spandex`, and a few more. Most of
that is archaeology now.

---

<sub>Find me also as <b><a href="https://twitter.com/dynaum">@dynaum</a></b> on X / Twitter.</sub>
