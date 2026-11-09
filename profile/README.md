<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="velella-mark-light.svg">
    <img alt="Velella" src="velella-mark.svg" width="72">
  </picture>
</p>

<h3 align="center">Stay afloat. Ready for any wind.</h3>

<p align="center">Open-source developer tools that find what is about to break in your software,<br>show exactly where, and help you or your coding agent fix it first.</p>

---

<h3 align="center">Our first project</h3>

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

<p align="center">
  <a href="https://www.npmjs.com/package/@velella/ebb"><img alt="npm" src="https://img.shields.io/npm/v/@velella/ebb?label=npm&logo=npm&logoColor=white&labelColor=1F1F28&color=3F6E66&style=flat"></a>
  <a href="https://github.com/velella-sh/ebb/actions/workflows/ci.yml"><img alt="CI" src="https://img.shields.io/github/actions/workflow/status/velella-sh/ebb/ci.yml?branch=main&label=CI&logo=github&logoColor=white&labelColor=1F1F28&color=3F6E66&style=flat"></a>
  <a href="https://github.com/velella-sh/ebb/tree/main/registry"><img alt="rules: 752" src="https://img.shields.io/badge/rules-752-3F6E66?labelColor=1F1F28&style=flat"></a>
</p>

Ebb is an open dataset of what is deprecated, unsupported, end-of-life or removed, since when, and what to move to. Every rule names its component by [purl](https://github.com/package-url/purl-spec), its versions by [VERS](https://github.com/package-url/vers-spec), and cites the source it came from. It covers 752 rules across 25 ecosystems, with a small TypeScript library to read them, offline.

```ts
import { lookupProduct } from "@velella/ebb/lookup";

const node = await lookupProduct("node", "18.20.4");
node.status;    // "end-of-life"
node.deadline;  // "2025-04-30"
```

Your agent's knowledge has a cutoff. Ebb doesn't.

**[Read the README](https://github.com/velella-sh/ebb#readme)** · **[Browse the rules](https://github.com/velella-sh/ebb/tree/main/registry)** · **[Contribute a rule](https://github.com/velella-sh/ebb/blob/main/CONTRIBUTING.md)**

---

### How we build

- **Exact.** Every finding points to a file and a line.
- **Sourced.** Every claim links to where it came from.
- **Honest.** Nothing unknown is reported as safe.
- **Local-first.** Runs on your machine. No account needed.

### Why Velella

*Velella* is a small blue sailor of the open ocean. What looks like one animal is a colony: many polyps sharing one float and one sail. It comes in two mirror-image forms, so whichever way the wind blows, part of the colony is ready for it. Our projects work the same way: small, each with one job, sharing one way of working.

<sub>[Contributing](https://github.com/velella-sh/.github/blob/main/CONTRIBUTING.md) · [Security](https://github.com/velella-sh/.github/blob/main/SECURITY.md) · [velella.sh](https://velella.sh)</sub>
