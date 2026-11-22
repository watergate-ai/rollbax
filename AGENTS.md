# AGENTS.md

<!-- release-init:begin -->
## Release

How this repository is released is described in `RELEASING.md` (humans) and summarised here (agents). The process is shared by all watergate-ai services and implemented in `watergate-ai/release-workflows`; this repository contains no caller files (see below).

This repository is **non-deployable**: there is no release pipeline. Do not add release, deploy or tag automation to it; if that changes, run `release-init` and follow `RELEASING.md`. There is deliberately no `.github/workflows/appsec.yml` and no other release-init caller file: this repository is public and cannot call the private shared workflows. Do not re-run `release-init` to add them while it is public (`release-init --check` fails for that reason).
<!-- release-init:end -->
