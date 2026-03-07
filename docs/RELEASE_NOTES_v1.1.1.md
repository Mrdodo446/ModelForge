# ModelForge v1.1.1

Patch release focused on first-launch language defaults, dark-mode readability, and refreshed macOS desktop packaging.

## Highlights

- first launch now defaults to English while still respecting a previously saved language preference
- dark mode surfaces were rebalanced for clearer text contrast in the navigation shell and `Computer Use`
- `Computer Use` now uses darker neutral cards and brighter copy instead of light cards on a dark shell
- macOS desktop packaging was rebuilt from the updated `main` branch

## UI And Localization

- the i18n bootstrap now falls back to `en` and only restores language from saved local storage
- dark theme tokens were tuned to separate background, card, border, and muted text more clearly
- the sidebar and `Computer Use` overview panels now render with dedicated dark surfaces instead of washed-out light cards

## Packaging

- macOS outputs:
  - `release/ModelForge.app`
  - `release/ModelForge-arm64.dmg`

## Notes

- this release does not change the cross-platform `Computer Use` execution model introduced in `v1.1.0`
- Windows packaging flow remains in place and should still be validated on a real Windows machine before release assets are published there
