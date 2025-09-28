# Macos-utility

A simple utility to fix custom Aerial wallpaper issues on macOS Sequoia and Tahoe.

## The Problem

The original WallpaperVideoExtensionFix worked for earlier macOS versions but failed on **macOS Tahoe (26.x)** and **macOS Sequoia**, causing:
- Blank/gray screens on login
- Custom Aerial wallpapers not loading properly
- System conflicts with WallpaperVideoExtension service

## The Solution

This enhanced version fixes those issues and works seamlessly with modern macOS versions.

## How to Use

1. **Download** the latest release `WallpaperVideoExtensionFix-macos-arm64.zip` as a compiled binary or compile it yourself
2. **Extract** the binary from the downloaded zip file
3. **Allow macOS to run the binary** by executing:
   ```
   chmod +x /path/to/WallpaperVideoExtensionFix.app/Contents/MacOS/WallpaperVideoExtensionFix
   ```
4. **Run the app once** and grant the necessary permissions
5. **Add the binary to your login items** to ensure it launches automatically at login
6. **Log out, then log back in** to start the utility
7. **(Optional)** Confirm the app is running by opening Activity Monitor and searching for `WallpaperVideoExtensionFix`

The utility runs silently in the background and fixes your wallpaper issues automatically.

## Compatibility

- ✅ macOS Sequoia
- ✅ macOS Tahoe
- ❌ Earlier versions (use original version)

## Credits

Based on the original WallpaperVideoExtensionFix by Proton0. Enhanced for modern macOS compatibility.

Credits to @Proton0 for original script

---

**If this fixed your wallpaper issues, please ⭐ star this repo!**
