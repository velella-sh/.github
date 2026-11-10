<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="velella-mark-light.svg">
    <img alt="Velella" src="velella-mark.svg" width="72">
  </picture>
</p>

<h3 align="center">Stay afloat. Ready for any wind.</h3>

<p align="center">Open-source developer tools that find what is about to break in your software,<br>show exactly where, and help you or your coding agent fix it first.</p>

---

<h3 align="center">Our projects</h3>

<p align="center">
  <a href="https://github.com/velella-sh/ebb">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/ebb/main/.github/assets/mark-night.svg">
      <img src="https://raw.githubusercontent.com/velella-sh/ebb/main/.github/assets/mark-day.svg" width="64" height="64" alt="Ebb">
    </picture>
  </a>
</p>

<h2 align="center"><a href="https://github.com/velella-sh/ebb">Ebb</a></h2>

<p align="center">
  <strong>Nothing ships forever. Everything ebbs.</strong><br>
  The open almanac of software end-of-life.
</p>

Ebb is an open dataset of what is deprecated, unsupported, end-of-life or removed, since when, and what to move to. Every rule names its component by [purl](https://github.com/package-url/purl-spec), its versions by [VERS](https://github.com/package-url/vers-spec), and cites the source it came from. It covers 752 rules across 25 ecosystems, with a small TypeScript library to read them, offline.

```ts
import { lookupProduct } from "@velella/ebb/lookup";

const node = await lookupProduct("node", "18.20.4");
node.status;    // "end-of-life"
node.deadline;  // "2025-04-30"
```

Your agent's knowledge has a cutoff. Ebb doesn't.

**[Read the docs](https://velella.sh/ebb/)** · **[README](https://github.com/velella-sh/ebb#readme)** · **[Browse the rules](https://github.com/velella-sh/ebb/tree/main/registry)** · **[Contribute a rule](https://github.com/velella-sh/ebb/blob/main/CONTRIBUTING.md)**

---

<h3 align="center">The docs stack</h3>

<p align="center">
  <a href="https://github.com/velella-sh/mizzen">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/mizzen/main/.github/assets/mark-night.svg">
      <img src="https://raw.githubusercontent.com/velella-sh/mizzen/main/.github/assets/mark-day.svg" width="64" height="64" alt="Mizzen">
    </picture>
  </a>
</p>

<h2 align="center"><a href="https://github.com/velella-sh/mizzen">Mizzen</a></h2>

<p align="center">
  <strong>Same input. Same site.</strong>
</p>

Mizzen is a deterministic docs engine. It turns a folder of Markdown into a fast, right-to-left-ready static site, and every page keeps its exact source positions, so a person or a coding agent can fix the right line.

```sh
npm install --save-dev @velella/mizzen @velella/lateen
npx mizzen build . --out dist
```

**[Read the docs](https://velella.sh/mizzen/)** · **[GitHub](https://github.com/velella-sh/mizzen)** · **[npm](https://www.npmjs.com/package/@velella/mizzen)**

<p align="center">
  <a href="https://github.com/velella-sh/lateen">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/lateen/main/.github/assets/mark-night.svg">
      <img src="https://raw.githubusercontent.com/velella-sh/lateen/main/.github/assets/mark-day.svg" width="64" height="64" alt="Lateen">
    </picture>
  </a>
</p>

<h2 align="center"><a href="https://github.com/velella-sh/lateen">Lateen</a></h2>

<p align="center">
  <strong>Easy to read. Safe to edit.</strong>
</p>

Lateen is the docs theme for people and agents, built on Mizzen: layouts, components and design tokens that work without JavaScript and are tested against WCAG 2.2 AA.

```yaml
theme:
  name: "@velella/lateen"
```

**[Read the docs](https://velella.sh/lateen/)** · **[GitHub](https://github.com/velella-sh/lateen)** · **[npm](https://www.npmjs.com/package/@velella/lateen)**

---

### How we build

- **Exact.** Every finding points to a file and a line.
- **Sourced.** Every claim links to where it came from.
- **Honest.** Nothing unknown is reported as safe.
- **Local-first.** Runs on your machine. No account needed.

### Why Velella

*Velella* is a small blue sailor of the open ocean. What looks like one animal is a colony: many polyps sharing one float and one sail. It comes in two mirror-image forms, so whichever way the wind blows, part of the colony is ready for it. Our projects work the same way: small, each with one job, sharing one way of working.

<sub>[Contributing](https://github.com/velella-sh/.github/blob/main/CONTRIBUTING.md) · [Security](https://github.com/velella-sh/.github/blob/main/SECURITY.md) · [velella.sh](https://velella.sh)</sub>
