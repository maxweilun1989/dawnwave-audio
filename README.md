# Dawnwave · Audio Assets

Publicly published, processed audio assets used by the **Dawnwave** iOS gradual-wake alarm app.

This repository exists mainly to satisfy the **ShareAlike** obligation of the
Creative Commons BY-SA 4.0 licensed singing-bowl recordings, and to make every
derivative audio file in the shipped app publicly available.

## Contents

| Folder | Files | Use in the app |
|---|---|---|
| `ramp/` | `<tone>-ramp-{30,60,120}s.caf` | gradual-wake alarm sound scheduled through AlarmKit (30 s variant) |
| `steady/` | `<tone>-steady.caf` | bedside mode: continuous full-volume loop after the ramp completes |
| `noise/` | `<name>-loop.caf` | bedside white noise loops (rain, fan, waves, stream, forest night, wind, brown noise) |

All files: mono, 48 kHz, 16-bit CAF.

## Original source for `bowl/*`

https://commons.wikimedia.org/wiki/File:Tibetan_Singing_Bowl_hit_11inch.flac

## Licensing

See [LICENSE](LICENSE) for the per-asset license map and
[ATTRIBUTION.md](ATTRIBUTION.md) for the original source list.

- `bowl/*` — derivative of a Wikimedia Commons recording, **CC BY-SA 4.0**
- `piano/*` — derivative of a Freesound recording, **CC BY 2.5**
- `birds/*`, `bell/*`, all `noise/*` except `brown-noise` — Mixkit License
- `brown-noise` — synthesised by Dawnwave

If you reuse `bowl/*`, you must keep the attribution above and distribute your
derivatives under CC BY-SA 4.0 as well.
