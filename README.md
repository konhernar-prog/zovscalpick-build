# burmaldascalp-build (private)

Build inputs + CI for producing BurmaldaScalp binaries. **Private** — not for distribution.

- `rebuild/BurmaldaScalp.spec` — Windows build (PyInstaller).
- `rebuild/BurmaldaScalp-mac.spec` — macOS build (.app). Runs only on macOS.
- `.github/workflows/build-macos.yml` — builds `BurmaldaScalp.app` on a GitHub macОS runner
  and uploads it as an artifact. Trigger via **Actions → build-macos → Run workflow**.
