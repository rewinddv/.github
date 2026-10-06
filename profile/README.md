# rewindDV

Native FireWire DV/HDV preservation and archival capture for modern macOS.

[rewinddv/rewindDV](https://github.com/rewinddv/rewindDV) is the canonical project:
application and driver source, engineering releases, documentation, issues and
contributions all live together.

**Current development: Alpha 0.0.89 / Driver B190 (app188).**
Bounded NTSC DV capture, normal capture STOP and session re-entry have current
development evidence. Live extension unload/hot replacement remains unqualified;
use the documented shutdown/restart maintenance path. Exact public-package
installation and broader hardware qualification remain separate.

[Current development and latest public download](https://github.com/rewinddv/rewindDV#readme)
are separate lifecycle states. The
[canonical project status](https://github.com/rewinddv/rewindDV/blob/main/PROJECT-STATUS.json)
records their independent application versions, driver builds and qualification
limits. A source update does not imply a new downloadable binary.

- [Engineering releases](https://github.com/rewinddv/rewindDV/releases)
- [Installation and security requirements](https://github.com/rewinddv/rewindDV/blob/main/INSTALL.md)
- [Compatibility and limitations](https://github.com/rewinddv/rewindDV/blob/main/COMPATIBILITY.md)
- [Report a bug or compatibility result](https://github.com/rewinddv/rewindDV/issues)
- [Build and contribute](https://github.com/rewinddv/rewindDV/blob/main/CONTRIBUTING.md)
- [Project website](https://rewinddv.com)

Current engineering binaries are ad-hoc signed and not notarized. Installation
requires disabling SIP, which reduces macOS security. They are intended for
experienced users and dedicated test systems. Read the release instructions and
bounded hardware-qualification limits; offline tests do not establish broader
compatibility or production readiness.

> **Help fund the standards behind tape metadata.** Funds raised go toward
> purchasing IEC standards to research all the metadata these tapes can contain
> and expand what rewindDV can decode.
> [**Support on Ko-fi →**](https://ko-fi.com/rewinddv)

Public issues are for sanitized summaries. Keep support ZIPs, raw logs, device
identifiers, personal paths and private footage out of public reports; request a
private transfer channel first.

Project contact: [info@rewinddv.com](mailto:info@rewinddv.com).
