# NINSA Avatar Tools

Unity Editor tools for VRChat avatars:
- Avatar Toggle Manager
- Avatar Dynamics Overhaul

## Package

The ready-to-install VPM archive is `Releases/com.ninsa.avatar-tools-1.0.0.zip`. It contains the compiled Editor assembly and package manifest. It requires Unity 2022.3 and VRChat Avatars SDK 3.10.5 or newer.

For local use, open **VCC → Settings → Packages → User Packages → Add** and select an extracted `com.ninsa.avatar-tools` package folder.

## VCC repository listing

The listing source is configured for this repository. To publish version 1.0.0:

1. Create a GitHub release with tag `v1.0.0`.
2. Attach `Releases/com.ninsa.avatar-tools-1.0.0.zip` as the release asset.
3. Publish the release.
4. In **Actions**, manually run **Build Repo Listing** to refresh the VPM index.

GitHub Pages must use **GitHub Actions** as its deployment source. This repository is private, so its listing and release links are not ready to share publicly. Make it public before sharing it as a VCC repository.

## Source archive

The editor source files are in `Source/AvatarTools-Editor-Source.zip`.
