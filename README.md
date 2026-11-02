# tws downloads

Public native executables and SHA-256 checksums for Tuggit Workspace.
Application source remains in separate private repositories.

**Wannabe stable** uses the latest non-prerelease GitHub Release. It is the
default for new installations and receives explicitly promoted versions such
as v0.3.0 and v0.3.1.

**Frontier 1980's** is an opt-in under tws Account settings. Experimental main
builds have tags such as `v0.3.1-frontier.1` (displayed as v0.3.01 in the UI)
and also update the rolling `frontier` release. Frontier releases are marked
prerelease and never become latest stable. Each release includes four native
archives, SHA-256 files, and version/checksum JSON manifests.

Installed clients check their selected channel automatically; API and website
containers do not need to be redeployed when a new terminal client is published.

This repository contains only distribution artifacts and their publishing workflow.
