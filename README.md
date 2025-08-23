# JetBrains Toolbox AppImage Builder

This repository automatically creates AppImage packages for JetBrains Toolbox. The official JetBrains Toolbox is distributed as a tarball that requires extraction and setup, which is inconvenient for portable use and distribution.
I prefer having applications as portable AppImages rather than extracting binaries to the filesystem. It's cleaner and more organized (especially when using GearLever).

## What this does

- **Monitors** the JetBrains Toolbox API for new releases every 12 hours
- **Downloads** the latest tarball from JetBrains
- **Extracts** and bundles all dependencies (Java runtime, libraries, binaries)
- **Creates** a proper AppImage with desktop integration
- **Builds** GitHub releases with the AppImage file
- **Checks** for version changes to avoid duplicate releases

## Download

Go to the [Releases](../../releases) page to download the latest JetBrains Toolbox AppImage.


## Quick Start

```bash
# Download the latest AppImage
wget https://github.com/YOUR_USERNAME/jetbrains-toolbox-appimage/releases/latest/download/JetBrains-Toolbox-*.AppImage

# Make executable and run
chmod +x JetBrains-Toolbox-*.AppImage
./JetBrains-Toolbox-*.AppImage
```

## Original Source

The original JetBrains Toolbox can be found at:
- Official website: https://www.jetbrains.com/toolbox-app/

## License

This repository only repackages the official JetBrains Toolbox. All rights belong to JetBrains. This is provided for convenience only.
