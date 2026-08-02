# Gecko v8 canonical runtime assets

This directory contains only the approved Gecko v8 individual used by the
runtime. The anatomy and silhouette are immutable inputs; morph, pattern, and
seed variation must be applied without substituting a different Gecko.

- Source repository: `JUYEONCODE/gecko-grove`
- Approved source commit: `c2b179039279d7a33e9c8ea4160830a522770fa7`
- Base image SHA-256: `b5bff1d4974c6afe9e0b062481ec7cf8de1030e93fde0a2a3664e3766a1a1a84`
- Asset count: 25 (`1` base + `24` action frames)
- Dimensions: base `512x512`; action frames `256x256`; all RGBA PNG

The complete per-file hash contract is maintained in
`assets/gecko/v8/phenotype-atlas/input-contract.json` in the source repository.
The contract SHA-256 at publication is
`adb0ac45f3e55d0d9770d9c7e94c5da38707a60f038f8eb309d030f2f442e9b2`.

Legacy `gecko/adult/parts` assets are not valid inputs for v8 work.
