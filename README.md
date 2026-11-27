# DS2Coop Developer Releases

Official public download channel for isolated DS2Coop Developer launcher builds.

## Current Developer prerelease

[Download the portable Windows x64 launcher 1.4.2-dev.21](https://github.com/irkanot/DS2Coop-Developer-Releases/releases/download/launcher-dev-1.4.2-dev.21/DS2CoopLauncher-Developer-1.4.2-dev.21-win-x64.zip).

ZIP SHA-256 is `D592AED54C581DCB86DA76F84EA15ECAA8C64CF4A0FF7D0B7696666403A9034D`. The signed Developer channel selects the read-only diagnostic `2.5.2-streaming-lifecycle.1` for Steam build 23923251. Its protocol and operator instructions are included in the candidate package. Upload requires a private operator profile.

Extract each release into a new directory. Preserve `%LOCALAPPDATA%\DS2Coop\Developer` when replacing an older Developer launcher so the existing workflow session can be recovered.

The executables are currently unsigned with Authenticode, so Windows SmartScreen may display a warning. Developer releases do not modify or replace the stable public channel automatically.
