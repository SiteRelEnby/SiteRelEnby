# Site Reliability Enby

A transfeminine [plural system](plurality.md); a collective of computerised canine celestial cyberpunks. Non-disordered, pro-endo.

SRE since Kubernetes 1.3.x was new (yes, really). Sysadmin in a former life; kept the LART and the tool-maker mentality.

Primarily building [Sheaf](https://sheaf.sh) and various related tools for the plural community, a few other miscellaneous tools nobody else was going to, and generally just contributing back to things we use regularly.

she/they collectively.

🔦🐺🪽

## What we build

### Plural tools

As a system who has been helped immeasurably by so many people from the community, we enjoy giving back where we can with meaningful tools designed to do the right thing, scale well, and stand the test of time.

- [Sheaf](https://sheaf.sh) - open source plural system tracker. Self-hostable, API-first, imports from other trackers, web/mobile/wearable clients. Running in production.
  - [sheaf](https://github.com/sheaf-project/sheaf): Python FastAPI backend and React SPA webapp for Sheaf.
  - [android](https://github.com/sheaf-project/android): Android and WearOS app for Sheaf.
  - [sheaf-ha](https://github.com/sheaf-project/sheaf-ha): Home Assistant integration for Sheaf.
  - [sheaf-canary](https://github.com/sheaf-canary/sheaf-canary): What most people underthink about warrant canaries is process, clearly-defined rules, and transparency. This is our effort at doing one right.
- [PluralPort](https://github.com/PluralPort): Interoperable data export standard for plural apps. Project maintainer and founding adopter with Sheaf. [Project website](https://pluralport.com).
- [revcord-plural](https://github.com/SiteRelEnby/revcord-plural): Revcord (Discord/Stoat message bridge) fork with proxy bot support and various architectural enhancements. In active development.

### Infra plumbing

We work with infrastructure every day. These tools are mostly designed from a "how is there not a tool for this?" moment of inspiration, expanded to cover all the general use cases.

- [s3duct](https://github.com/SiteRelEnby/s3duct) - chunked, resumable, encrypted pipe to S3-compatible object storage. Written to backup large zpools without equal scratch space requirements, but many general-purpose uses and should drop into most pipeline-based processes seamlessly. In production for our personal infrastructure.
- [keyquorum](https://github.com/SiteRelEnby/keyquorum) - memory-hardened Shamir secret sharing daemon for distributed teams. No shared tmux sessions required. Initially developed for a stalled project; usable and extensively tested but not real-world tested by us.
- [sharkey-prometheus-exporter](https://github.com/SiteRelEnby/sharkey-prometheus-exporter) - Prometheus metrics for Sharkey, with a Grafana template. In production with several known instances including our own.
- [tracebit-python](https://github.com/SiteRelEnby/tracebit-python) - Lightweight Tracebit canary credential (honeytoken) CLI that works on servers, not just desktops. In production on our own systems.

### Git tools

Git is one of the most widely used pieces of software in the world. We build the tools for it that nobody else was going to.

- [git-leash](https://github.com/SiteRelEnby/git-leash) - time-gated commit blocking hook. Helps you stay focused on what you should be doing at certain times of day. Especially if you're a puppy. *Somehow*, our most starred repo...
- [git-redate](https://github.com/SiteRelEnby/git-redate) - maintained fork: rewrite commit dates in bulk, with signing that actually works and many bugfixes.

### Lights

- [anduril-buildenv-docker](https://github.com/SiteRelEnby/anduril-buildenv-docker) - reproducible build environment for Anduril.
- [RGBroadcast](https://github.com/SiteRelEnby/RGBroadcast) - make Home Assistant RGB lighting mimic a television for occupancy simulation.
- [anduril2](https://github.com/SiteRelEnby/anduril2) - a collection of old hacks and patches for an old branch of the Anduril flashlight firmware. Includes many custom features not found in mainline releases, but may need significant refactoring to be compatible with the current Anduril codebase. Will get around to it at some point. "Ran when parked".

### Misc

- [fjortoft](https://github.com/SiteRelEnby/fjortoft) - Global Consciousness Project network coherence and [corru.observer](https://corru.observer) GAD poller, Discord bot, and Grafana dashboard.
- [gfx1103-pytorch-rocm](https://github.com/SiteRelEnby/gfx1103-pytorch-rocm) - PyTorch from source with native Radeon 780M ROCm support, until upstream catches up.

### Other projects we regularly work on

Other stuff we aren't maintainers of but consider important work of ours.

- [anduril](https://github.com/ToyKeeper/anduril): Regular contributor to the best flashlight firmware in the world.
- [signal-export](https://github.com/carderne/signal-export): Export Signal chats to markdown and HTML. Many recent contributions with more planned. Perhaps we have a few archivist tendencies too.

## Elsewhere

- [SiteRelEnby.net](https://SiteRelEnby.net)
- [Fedi: transfem.social/@SiteRelEnby](https://transfem.social/@SiteRelEnby)
- [Bsky: siterelenby.net](https://bsky.app/profile/siterelenby.net)
- [Wolfgirl Reviews](https://wolfgirlreviews.com) - on hiatus due to life stability reasons.
- Sponsor our work via [Sheaf's sponsors page](https://github.com/sponsors/sheaf-project)
- Signal/Discord: ask us.
