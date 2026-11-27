# DS2Coop Developer Releases

Official public download channel for isolated DS2Coop Developer launcher builds.

## Current Developer prerelease

[Download the portable Windows x64 launcher 1.4.2-dev.23](https://github.com/irkanot/DS2Coop-Developer-Releases/releases/download/launcher-dev-1.4.2-dev.23/DS2CoopLauncher-Developer-1.4.2-dev.23-win-x64.zip).

ZIP SHA-256 is `CA4244CCD2B2EA509D65CD3D1367E8264D7E710A49B0E8F75B3B535E6961BDD4`. The signed Developer channel selects the read-only diagnostic `2.5.2-scene-patrol.2` for Steam build 23923251. The operator protocol is available in Italian and included in the signed candidate package. [Protocollo nl202](versions/developer-1.4.2-dev.23/PROTOCOLLO_NL202.md). Upload requires a private operator profile.

Extract each release into a new directory. Preserve `%LOCALAPPDATA%\DS2Coop\Developer` when replacing an older Developer launcher so the existing workflow session can be recovered.

The executables are currently unsigned with Authenticode, so Windows SmartScreen may display a warning. Developer releases do not modify or replace the stable public channel automatically.
