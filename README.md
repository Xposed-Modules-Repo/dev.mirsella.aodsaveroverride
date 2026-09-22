# AOD Battery Saver Override

Keep Always On Display available while Battery Saver is enabled.

Current upstream release: `0.1.3`. Requires an Xposed framework with modern API 102 support. Supports Android 16 QPR2 (SDK 36) and Android 17 (SDK 37).

Updates from 0.1.2 use the same signing key and can be installed directly. Reboot after updating so the framework hook is reloaded.

To upgrade from 0.1.1, uninstall the old APK, install the latest release, enable the module again in LSPosed with `system` scope, and reboot. The signing key changed in 0.1.2.

- Package: `dev.mirsella.aodsaveroverride`
- Support: `https://github.com/mirsella/aod-battery-saver-override/issues`
- Source: `https://github.com/mirsella/aod-battery-saver-override`
