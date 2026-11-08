# Genomics LIMS releases

This repository holds the released builds of Genomics LIMS and the signed update feed
(`latest.json`). It contains no source code.

Installed copies check for updates at:

```
https://github.com/Taimoor-Khan-bt/genomics-lims-releases/releases/latest/download/latest.json
```

The feed is signed with the vendor key. Each build's SHA-256 is listed in the feed, and the
application installs a build only when the signature and the hash match.

To install for the first time, download the installer or archive for your platform from the
[latest release](https://github.com/Taimoor-Khan-bt/genomics-lims-releases/releases/latest).
