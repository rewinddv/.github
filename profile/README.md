# rewindDV

Native FireWire DV preservation and archival capture for Apple silicon.
Requires macOS 26 Tahoe or macOS 27 Golden Gate; will not run on older macOS versions or Intel Macs. Later macOS releases are not currently supported.

[rewinddv/rewindDV](https://github.com/rewinddv/rewindDV) is the canonical project:
application and driver source, engineering releases, documentation, issues and
contributions all live together.

Current source includes human-readable recorded camera metadata, searchable
inspectors, saved-DV review, raw metadata inspection, epoch-aware
mixed-format archival support, lossless segmented exports and local CLI/MCP
interfaces. Consult the canonical project status for current development
versions and the measured scope of automated and hardware qualification.

[Current development and latest public download](https://github.com/rewinddv/rewindDV#readme)
are separate lifecycle states. The
[canonical project status](https://github.com/rewinddv/rewindDV/blob/main/PROJECT-STATUS.json)
records their independent application versions, driver builds and qualification
limits. A source update does not imply a new downloadable binary.

- [Engineering releases](https://github.com/rewinddv/rewindDV/releases)
- [Installation instructions](https://github.com/rewinddv/rewindDV/blob/main/INSTALL.md)
- [Compatibility and limitations](https://github.com/rewinddv/rewindDV/blob/main/COMPATIBILITY.md)
- [Report a bug or compatibility result](https://github.com/rewinddv/rewindDV/issues)
- [Build and contribute](https://github.com/rewinddv/rewindDV/blob/main/CONTRIBUTING.md)
- [Project website](https://rewinddv.com)

The current engineering download contains the full Apple silicon app, its
matching DriverKit extension, and the normal CLI/MCP client. It is Developer ID
signed and notarized. Follow normal macOS approval; no SIP change is required.
Offline playback and archive operations need no driver activation. The earlier
Alpha 0.0.94 offline-only release remains available unchanged in release history.

Signing and the approved controller entitlement do not establish broad hardware
compatibility. Earlier bounded M1 SIP-on observations used different builds;
successful historical PAL captures and a completed whole-tape NTSC workflow
remain scoped to their tested earlier builds. The newest retained Driver203 has
no fresh physical capture/endurance qualification. HDV capture, broader deck
support and live unload remain unqualified. Read the canonical status and exact
release limitations before hardware use.

> **Help fund the standards behind tape metadata.** Funds raised go toward
> purchasing IEC standards to research all the metadata these tapes can contain
> and expand what rewindDV can decode.
> [**Support on Ko-fi →**](https://ko-fi.com/rewinddv)

Public issues are for sanitized summaries. Keep support ZIPs, raw logs, device
identifiers, personal paths and private footage out of public reports; request a
private transfer channel first.

Project contact: [info@rewinddv.com](mailto:info@rewinddv.com).
