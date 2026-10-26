L2 Mod Manager - Requirements

- A Windows PC.
- A complete, working Lineage II Interlude game client.
- Microsoft .NET Framework 4.8 or 4.8.1.

.NET Framework 4.8 Runtime - official Microsoft download:
https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-offline-installer

If .NET Framework 4.8 or 4.8.1 is already installed, skip this download.

Run L2ModManager.exe and select your game client folder.
The Weapon enchants 3D preview requires a supported Interlude client engine.

Optional Vulkan mode - bundled DXVK 2.6.1

Requires Vulkan 1.3 and the additional Vulkan features used by DXVK.
Install the latest compatible graphics driver, including 32-bit Vulkan support.

Examples of GPU families with Vulkan 1.3-capable drivers:
- NVIDIA: GeForce GTX 900, GTX 10, GTX 16 and RTX 20/30/40/50 series.
- AMD: Radeon RX 400/500, RX Vega, Radeon VII and RX 5000/6000/7000/9000 series.
- Intel: Arc A/B series, Iris Xe and UHD 730/750/770.

This is a hardware guide, not a list of GPUs tested with this manager.
DXVK compatibility on Windows also depends on the driver and game client.
Older Intel HD/UHD graphics can fail with DXVK even when Vulkan 1.3 is listed.
GPUs limited to Vulkan 1.2 or older cannot use the bundled DXVK version.
If Vulkan mode does not work, disable it to use the game's DirectX 9 renderer.

Official graphics drivers:
NVIDIA: https://www.nvidia.com/en-us/drivers/
AMD: https://www.amd.com/en/support/download/drivers.html
Intel: https://www.intel.com/content/www/us/en/download-center/home.html
