# Stock Signals - releases

This page only hosts signed builds of the **Stock Signals** Windows app (`StockSignals.exe`) so that installed copies can update themselves.
There is no source code here.

Each release contains:
- `StockSignals.exe` - the app
- `manifest.json` - the build number and SHA-256 of the exe, signed with the developer's private key

The app verifies that signature before installing anything. Files that do not verify are ignored.

Stock Signals is a personal research tool. It is not investment advice and it does not place orders.
