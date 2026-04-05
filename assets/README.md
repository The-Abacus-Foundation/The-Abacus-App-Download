# Versioned installer folders

Each **`assets/v{version}/`** directory holds the published installers for that release, synced from CI.

Filenames match the main app (`web/package.json` version), for example:

- `abacus-accounting-macos-arm64-4.0.1.dmg`
- `abacus-accounting-windows-x64-4.0.1.msi`
- `abacus-accounting-linux-x64-4.0.1.AppImage`

Do not edit these manually in production; the **The-Abacus-Accounting-Web** workflow updates this tree.
