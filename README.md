# E-paper Weather Station

A home weather station with an e-paper display, a battery-powered outdoor sensor
and a self-hosted server.

**Status:** concept and design phase.

## Goals

- outdoor sensor running for a year or more on batteries, verified by measurement
- documented measurement accuracy
- local short-term forecast from the pressure trend
- custom PCB and 3D-printed enclosure

## Repository layout

| Directory          | Contents                              |
|--------------------|---------------------------------------|
| `firmware/indoor`  | indoor unit with e-paper display      |
| `firmware/outdoor` | battery-powered outdoor sensor        |
| `hardware/`        | PCB designs                           |
| `enclosure/`       | 3D enclosure models                   |
| `server/`          | Raspberry Pi configuration            |
| `docs/`            | concept, measurements, photos         |

## License

MIT, see [LICENSE](LICENSE).
