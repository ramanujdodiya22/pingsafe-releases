# PingSafe test releases

Test builds of PingSafe for Android. This repository holds only the APK files; the app checks it for updates.

**Download the newest version:**
https://github.com/ramanujdodiya22/pingsafe-releases/releases/latest/download/PingSafe.apk

Already installed? PingSafe tells you when a new version is out (Settings → Check for updates).

## Is the APK genuine?

Every test build is signed with this certificate:

```
SHA-256: 84:FC:4C:68:E8:64:E9:93:D2:BA:C7:25:46:14:BB:8A:06:2C:C0:0E:AF:52:94:AA:8D:3A:0F:91:75:96:23:A5
```

Check a file with `apksigner verify --print-certs PingSafe.apk`. If the SHA-256 differs, don't install it.
