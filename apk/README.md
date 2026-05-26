# HexVPN APK Files

Built from source at `/opt/android/hexvpn` on 2026-05-26.

## Files

| File | Architecture | Size | Use case |
|------|-------------|------|----------|
| `hexvpn-arm64-v8a-release.apk` | ARM 64-bit | ~115 MB | **Recommended** — all modern Android phones |
| `hexvpn-armeabi-v7a-release.apk` | ARM 32-bit | ~103 MB | Older / 32-bit devices |
| `hexvpn-x86_64-release.apk` | x86 64-bit | ~124 MB | Emulators |

## Build info

- Flutter: 3.44.0
- Dart SDK: 3.12.0
- Java: OpenJDK 17.0.19
- App version: 4.1.2+40102
- Build type: Release (unsigned)

## Fixes applied

- `font_awesome_flutter` upgraded to 11.x (Flutter 3.44 compatibility)
- `simple_icons` 10.1.3 patched: `SimpleIconData` replaced with direct `IconData` constructors
- 8 usages of `FontAwesomeIcons.xxx` updated to use `.data` for `IconData` compatibility
- Code generation (build_runner) run to produce `.g.dart`, `.freezed.dart` files
