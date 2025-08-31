# JetBrains Toolbox Linux 

This repository automatically creates AppImage/Flatpak packages for JetBrains Toolbox. The official JetBrains Toolbox is distributed as a tarball that requires extraction and setup, which is inconvenient for portable use and distribution.
I prefer having applications be portable rather than extracting binaries to the filesystem.

## What this does

- **Monitors** the JetBrains Toolbox API for new releases every 24 hours
- **Downloads** the latest tarball from JetBrains
- **Extracts** and bundles all dependencies (Java runtime, libraries, binaries)
- **Creates** a proper AppImage with desktop integration
- **Builds** GitHub releases with the AppImage file
- **Checks** for version changes to avoid duplicate releases

## Original Source

The original JetBrains Toolbox can be found at:
- Official website: https://www.jetbrains.com/toolbox-app/

## License

This repository only repackages the official JetBrains Toolbox. All rights belong to JetBrains. This is provided for convenience only.
