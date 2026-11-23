# Changelog

## [0.0.3] - 2026-11-23

- Move from Expo SDK `58.0.0-preview.7` and React Native `0.88.0-rc.2` to
  stable Expo `58.0.26` and React Native `0.88.1` (with matching pnpm
  overrides).
- Align SDK 58 packages: `expo-crypto` `58.0.8`, `expo-modules-core` `58.1.0`,
  `expo-build-properties` `58.0.12`, `expo-secure-store` `58.0.3`, plus
  `react` `19.3.1` (#35). This fixes the Gradle autolinking failure with
  `expo-crypto` 58.0.5 and later (#37).
- Wear package/app version `0.0.3`; Android `versionCode` `3`.
- Still a Wear OS developer prerelease, sideloaded from GitHub Releases only —
  not production-stable. Play Store, Firebase push, multi-host/SSH, off-network
  access, and screen-off notifications remain unverified unless separately
  confirmed.

## [0.0.2] - 2026-09-27

- Keep Expo SDK at `58.0.0-preview.7` and bump React Native to `0.88.0-rc.2`
  (with matching pnpm overrides).
- Wear package/app version `0.0.2`; Android `versionCode` `2`.
- Still a Wear OS developer prerelease on Expo 58 preview + RN 0.88 RC — not
  production-stable. Play Store, Firebase push, multi-host/SSH, off-network
  access, and screen-off notifications remain unverified unless separately
  confirmed.

## [0.0.1] - 2026-09-26

- Direct Wear-scoped enrollment with Attention, Agents, Usage, conversations,
  and exact-target replies.
- Bounded cached dashboard and periodic refresh with explicit freshness.
- Physical Watch8 installation, pairing, and live Attention dashboard observed
  on a reachable LAN host. Other physical flows remain unverified.
