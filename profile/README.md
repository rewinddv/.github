# rewindDV

Native FireWire DV/HDV preservation and archival capture for modern macOS.

[rewinddv/rewindDV](https://github.com/rewinddv/rewindDV) is the canonical project:
application and driver source, engineering releases, documentation, issues and
contributions all live together.

Current source includes saved-DV review, raw metadata inspection, epoch-aware
mixed-format archival support, lossless segmented exports and local CLI/MCP
interfaces. Consult the canonical project status for current development
versions and the measured scope of automated and hardware qualification.

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

Current engineering binaries are ad-hoc signed and not notarized. Offline
playback, inspection and supported archive operations do not require DriverKit
activation. Activating an included ad-hoc DriverKit extension may require
disabling SIP, which reduces macOS security; normal SIP-on driver installation
is not qualified for these packages. Read the exact release instructions and
hardware-qualification limits. Offline tests do not establish physical capture
compatibility or production readiness.

> **Help fund the standards behind tape metadata.** Funds raised go toward
> purchasing IEC standards to research all the metadata these tapes can contain
> and expand what rewindDV can decode.
> [**Support on Ko-fi →**](https://ko-fi.com/rewinddv)

Public issues are for sanitized summaries. Keep support ZIPs, raw logs, device
identifiers, personal paths and private footage out of public reports; request a
private transfer channel first.

Project contact: [info@rewinddv.com](mailto:info@rewinddv.com).
