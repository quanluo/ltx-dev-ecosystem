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

Status: source-reviewed content complete on the draft pull-request branches;
publication awaits review and merge. Independent runtime validation was waived
for this phase, so execution and benchmark claims remain explicitly excluded.

Target window: days 1–30 after Phase 1 approval.

### Ecosystem hub

- Review and classify at least 20 resources.
- Add resource metadata: owner, type, version, license, relationship, review date.
- Publish transparent inclusion and removal criteria.
- Add automated outbound-link checking.

### Examples

- Publish 3 source-reviewed command recipes:
  - text-to-video CLI;
  - text-to-video Python;
  - image-to-video.
- Record exact model version, dependencies, and seed. Leave hardware, VRAM,
  runtime, and last-tested results unclaimed until observed.
- Add one smoke check that catches missing files and invalid configuration.

### ComfyUI workflows

- Publish 3 immutable upstream workflow indexes:
  - starter text-to-video;
  - image-to-video;
  - synchronized audio-video.
- Link canonical upstream JSON without copying or relabeling it.
- Document required nodes, model categories, setup, safety, and provenance.

### Prompt cookbook

- Publish 30 original source-reviewed prompts across 6 collections.
- Label them as ungenerated drafts rather than proven outputs.
- Organize by use case, camera movement, and input mode.

### Documentation

- Publish 8 source-reviewed guides:
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

- all procedural assets distinguish source review from runtime testing;
- no unobserved compatibility or performance claims appear;
- all relative links and content counts pass repository checks;
- no third-party media is redistributed;
- canonical upstream revisions and ownership are clear.

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
