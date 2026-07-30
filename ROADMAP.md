# LTX.dev GitHub Ecosystem Roadmap

Last updated: 2026-07-30

This roadmap covers the independent open-content ecosystem maintained by
[LTX.dev](https://ltx.dev). It does not represent the official Lightricks
roadmap.

## Operating principles

- Publish useful, reproducible assets before pursuing promotion.
- Keep official LTX sources clearly distinguished from LTX.dev resources.
- Use feature branches and draft pull requests for all content changes.
- Require version, test date, provenance, and rights information.
- Expand a repository only when it has a maintainer and a distinct user need.
- Measure qualified usage and earned citations, not raw backlink volume.

## Phase 1 — Foundation

Status: ready for review in draft pull requests.

Deliverables:

- five public repositories with distinct responsibilities;
- independent-platform and trademark relationship notices;
- SEO-friendly README navigation;
- contribution and quality requirements;
- MIT licensing for original repository content;
- upstream-first linking and anti-link-scheme rules.

Exit criteria:

- stakeholder review completed;
- canonical destination confirmed as `https://ltx.dev`;
- repository descriptions, notices, and licenses approved;
- foundation pull requests merged intentionally.

## Phase 2 — Minimum Useful Ecosystem

Target window: days 1–30 after Phase 1 approval.

### Ecosystem hub

- Review and classify at least 20 resources.
- Add resource metadata: owner, type, version, license, relationship, review date.
- Publish transparent inclusion and removal criteria.
- Add automated outbound-link checking.

### Examples

- Publish 3 end-to-end verified recipes:
  - text-to-video CLI;
  - text-to-video Python;
  - image-to-video.
- Record exact model version, dependencies, seed, hardware, VRAM, runtime, and
  last-tested date.
- Add one smoke check that catches missing files and invalid configuration.

### ComfyUI workflows

- Publish 3 validated workflows:
  - starter text-to-video;
  - image-to-video;
  - synchronized audio-video.
- Include portable JSON, manifest, preview, required nodes, model paths, and
  asset rights.
- Propose canonical workflows upstream before maintaining independent forks.

### Prompt cookbook

- Publish 30 tested prompts across 6 collections.
- Include settings, model/pipeline version, expected behavior, and provenance.
- Add schema validation and filters for use case, camera movement, and input
  mode.

### Documentation

- Publish 8 source-reviewed and tested guides:
  - installation;
  - first text-to-video generation;
  - image-to-video;
  - GPU/VRAM guide;
  - low-VRAM options;
  - ComfyUI setup;
  - CUDA/memory troubleshooting;
  - prompting synchronized audio-video.
- Connect every guide to a relevant example, workflow, or prompt collection.

Phase 2 exit criteria:

- all published procedural assets have a reviewer and last-tested date;
- no placeholder compatibility or performance claims remain on published pages;
- all outbound links pass validation;
- all media has recorded provenance and redistribution rights;
- at least one person other than the author can reproduce each core recipe.

## Phase 3 — Distribution and Authority

Target window: days 31–60.

Deliverables:

- compatibility matrix by LTX version, task, GPU class, and workflow;
- migration guide from LTX-Video to LTX-2;
- 5 issue-driven troubleshooting pages;
- 2 integrations or upstream contributions accepted or under review;
- a monthly ecosystem update based on actual releases and community work;
- a small, reproducible benchmark only if raw settings and limitations can be
  published.

Distribution rules:

- contribute useful fixes before mentioning LTX.dev;
- never mass-open issues or pull requests;
- do not request reciprocal links;
- disclose LTX.dev ownership on every contributed resource;
- prefer deep links that answer the immediate task.

Phase 3 exit criteria:

- first external contribution accepted;
- at least 80% of assets reviewed within the freshness window;
- recurring setup failures produce documentation improvements;
- search and referral baselines are established.

## Phase 4 — Scale Proven Content

Target window: days 61–90.

Deliverables:

- expand the two clusters with the strongest qualified engagement;
- add release-specific migration and compatibility notes;
- launch a reviewed community showcase with objective inclusion rules;
- introduce quarterly link, license, claim, and version audits;
- decide whether prompts or workflows need independent releases and maintainers.

Do not scale page or repository count unless Phase 2 quality criteria continue
to pass.

## Required operating inputs

Phase 2 execution depends on:

1. access to an NVIDIA GPU environment capable of running the selected LTX
   release, or a named reviewer who will execute and sign off on recipes;
2. approved model/checkpoint versions and target hardware classes;
3. permission to use and redistribute generated previews;
4. access to any non-public LTX.dev product or API documentation intended for
   developer guides;
5. one named technical reviewer and one editorial/brand approver.

If GPU access is unavailable, prioritize the ecosystem index, source-reviewed
documentation, prompt methodology, and LTX.dev platform guides. Keep local
inference recipes in draft until a reproducible test is completed.

## Measurement

Establish a 28-day baseline before setting growth targets.

| Area | Primary metric | Guardrail |
|---|---|---|
| Discovery | Non-brand impressions to useful assets | No keyword stuffing |
| Referral | Qualified visits to relevant LTX.dev pages | No repeated homepage links |
| Adoption | Reproduced recipes and downloaded workflows | Test evidence required |
| Community | Substantive accepted contributions | No link-for-inclusion deals |
| Reliability | Passing validation and freshness checks | Broken-link rate below 1% |
| Trust | Correct relationship and provenance labeling | Zero misleading official claims |

## Review cadence

- Weekly: issue triage, broken links, failed reproduction reports.
- Monthly: search queries, referral paths, stale assets, compatibility updates.
- Quarterly: repository architecture, licenses, claims, benchmarks, and
  community inclusion policy.

