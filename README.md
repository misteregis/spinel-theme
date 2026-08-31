# Spinel Theme

Standalone packaging of Shopify's **Spinel** and **Spinel Light** VS Code themes.

This extension contains no Ruby LSP, no Sorbet extension, no `extensionPack`, and no runtime code.

## Install

Use **Extensions: Install from VSIX...** in VS Code and select `spinel-theme-1.0.0.vsix`, or run:

```bash
code --install-extension spinel-theme-1.0.0.vsix
```

Then select **Preferences: Color Theme** → **Spinel** (or **Spinel Light**).

## Dev Container

If you keep the VSIX in your repository, you can install it in the container with the VS Code CLI after the remote VS Code server is available. If you publish this extension to a registry, you can instead use its extension ID in `customizations.vscode.extensions`.

## Attribution

The Spinel theme definitions originate from Shopify's `vscode-shopify-ruby` project, licensed under MIT.
