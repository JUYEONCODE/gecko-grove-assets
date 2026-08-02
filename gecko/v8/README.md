# Gecko v8 canonical runtime assets

This directory contains only the approved Gecko v8 individual used by the
runtime. The anatomy and silhouette are immutable inputs; morph, pattern, and
seed variation must be applied without substituting a different Gecko.

- Source repository: `JUYEONCODE/gecko-grove`
- Approved source commit: `c2b179039279d7a33e9c8ea4160830a522770fa7`
- Base image SHA-256: `b5bff1d4974c6afe9e0b062481ec7cf8de1030e93fde0a2a3664e3766a1a1a84`
- Asset count: 25 (`1` base + `24` action frames)
- Dimensions: base `512x512`; action frames `256x256`; all RGBA PNG

The complete per-file hash contract is `SHA256SUMS` in this directory and is
also mirrored by the app repository's canonical runtime manifest.

The active asset repository contains no legacy Gecko individual. Git history
is the audit record; restoring `gecko/adult`, flat growth-stage sprites, or
`geckos/iso` is forbidden.
