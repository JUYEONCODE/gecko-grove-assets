# Gecko v8 canonical runtime assets

This directory contains only the approved Gecko v8 individual used by the
runtime. The anatomy and silhouette are immutable inputs; morph, pattern, and
seed variation must be applied without substituting a different Gecko.

- Source repository: `JUYEONCODE/gecko-grove`
- Canonical source lineage: `c2b179039279d7a33e9c8ea4160830a522770fa7`
- RGB-clean input app commit: `95358d39ff1d1c24da8354346073446b749bc717`
- Approved RGB-clean app commit: `2b1bcf0af8e097bcf9bf3df46e33b59558b7f693`
- Base image SHA-256: `b5bff1d4974c6afe9e0b062481ec7cf8de1030e93fde0a2a3664e3766a1a1a84`
- Asset count: 25 (`1` base + `24` action frames)
- Dimensions: base `512x512`; action frames `256x256`; all RGBA PNG

The complete per-file hash contract is `SHA256SUMS` in this directory. The app
repository's canonical runtime manifest and asset commit pin are downstream
contracts and are intentionally left for a separate integration.

## RGB-only chroma cleanup v1

The 24 action frames are byte-identical to the approved outputs in app commit
`2b1bcf0af8e097bcf9bf3df46e33b59558b7f693`. Its reproducible postprocess,
per-frame input/output/alpha hashes, and QC report are:

- `assets/gecko/v8/normal/chroma-clean-v1/postprocess.py`
- `assets/gecko/v8/normal/chroma-clean-v1/contract.json`
- `assets/gecko/v8/normal/chroma-clean-v1/QC-REPORT.md`

Only selected RGB values changed. All 24 alpha planes, geometry, and the base
PNG are unchanged. Both contracted magenta-residue measures are zero on all
runtime frames.

The active `gecko/v8` runtime namespace contains no legacy Gecko individual.
Git history is the audit record; restoring `gecko/adult`, flat growth-stage
sprites, or `geckos/iso` beneath this namespace is forbidden. Branding icons
and unused historical backgrounds elsewhere in the asset repository are not
covered by this 25-file runtime contract and are tracked for separate removal.
