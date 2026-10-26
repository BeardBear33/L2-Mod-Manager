# L2 Mod Manager

## Requirements

- A Windows PC.
- A complete, working Lineage II Interlude game client.
- Microsoft .NET Framework 4.8 or 4.8.1.

[Download .NET Framework 4.8 Runtime](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-offline-installer) from Microsoft. Skip this download if version 4.8 or 4.8.1 is already installed.

## Getting started

1. Place `L2ModManager.exe` in a folder where you have write access.
2. Run it and select your game client folder or its `system` subfolder.
3. Select a modification and use the available buttons to configure or apply it.

The manager automatically creates `L2ModManager.ini` next to the EXE to store your preferences.

Close the game before applying changes. Changes take effect after restarting the game.

The Weapon enchants 3D preview requires a supported Interlude client engine.

## Updating

1. Close L2 Mod Manager.
2. Replace `L2ModManager.exe` with the new version in the same folder.
3. Keep your existing `L2ModManager.ini` to preserve your preferences.

You do not need to uninstall the previous version. Keep the manager-created backups and profiles in your game client folder as well.

## Optional Vulkan mode

The manager includes **DXVK 2.6.1**, which requires **Vulkan 1.3** and additional Vulkan features used by DXVK.

Install the latest compatible graphics driver, including **32-bit Vulkan support**.

Examples of GPU families with Vulkan 1.3-capable drivers:

| Manufacturer | GPU families |
| --- | --- |
| NVIDIA | GeForce GTX 900, GTX 10, GTX 16 and RTX 20/30/40/50 series |
| AMD | Radeon RX 400/500, RX Vega, Radeon VII and RX 5000/6000/7000/9000 series |
| Intel | Arc A/B series, Iris Xe and UHD 730/750/770 |

This is a hardware guide, not a list of GPUs tested with this manager. Compatibility also depends on the driver and game client.

- Older Intel HD/UHD graphics can fail with DXVK even when Vulkan 1.3 is listed.
- GPUs limited to Vulkan 1.2 or older cannot use the bundled DXVK version.
- If Vulkan mode does not work, disable it to return to the game's DirectX 9 renderer.

**Official graphics drivers:** [NVIDIA](https://www.nvidia.com/en-us/drivers/) | [AMD](https://www.amd.com/en/support/download/drivers.html) | [Intel](https://www.intel.com/content/www/us/en/download-center/home.html)
