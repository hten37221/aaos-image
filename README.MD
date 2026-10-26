# AOSP-Images

Prebuilt AOSP emulator images prepared for sharing through GitHub.

## Automotive MySystemApp image v5

- Build date: 2026-10-26
- Product: `sdk_car_mysystemapp_x86_64`
- Android: 17 (Baklava), API 37
- ABI: `x86_64`
- Build ID: `CP2A.260605.016`
- Image: Automotive AVD containing the latest `My-System-App` build (branch `ux-gui-audit-improvements`: UX/UI audit improvements, 3D hotspots, card spacing/alignment, tab pending selection, Full-screen 1920x1080 display).
- Original ZIP SHA-256:
  `ec06e9e8df8252b8fd668d10b3e7eaffe11a47391649e14ee3deee3b6231f6ae`
- The archive is split into 8 volumes, each below 100 MB, for GitHub upload:
  `sdk-repo-linux-system-images-automotive-mysystemapp-v5.7z.001` through
  `.008`.

### Restore the v5 image

Place all 8 v5 volumes in one directory, then run:

```bash
7z t sdk-repo-linux-system-images-automotive-mysystemapp-v5.7z.001
7z x sdk-repo-linux-system-images-automotive-mysystemapp-v5.7z.001
```

The extracted file is `sdk-repo-linux-system-images-automotive-mysystemapp-v5.zip`.
See `sdk-repo-linux-system-images-automotive-mysystemapp-v5.manifest` for
checksums and exact volume sizes.