# Canonical Gecko branding assets

These public compatibility paths are derived only from the approved Gecko v8
base. They do not contain an older Gecko actor.

Source:

- `gecko/v8/normal/base/normal-crested-gecko-v8.png`
- SHA-256: `b5bff1d4974c6afe9e0b062481ec7cf8de1030e93fde0a2a3664e3766a1a1a84`

Outputs:

- `icon.png`: 600x600 opaque RGB. The 512x512 source is placed at `(44, 44)`
  over `#4A7C59`; scale 1, rotation 0, mirror false. SHA-256:
  `6dbec7a92407a3db5381266630e7407f13df81eacddeb3343c96f7f83a147212`.
- `icons/tabs/tab_home.png`: 128x128 RGBA, uniform 0.25 scale using a
  deterministic premultiplied-alpha average over each 4x4 source-pixel block;
  rotation 0, mirror false. SHA-256:
  `c7a1cfeb41ed2a55aefff4826920c472df1ef2f11e3b9870267ee9e98b388921`.

The app repository owns the deterministic generators and verifies both outputs
from the same approved source at the decoded-pixel level before release. The
deprecated `backgrounds/room_bg.png` was removed because it baked older Gecko
actors into an otherwise unused room image.
