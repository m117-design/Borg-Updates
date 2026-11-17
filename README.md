# BORG Android Updates

Public distribution channel for official, persistently signed BORG Android APK releases.

The BORG source code and build pipeline remain in the private `m117-design/Borg` repository. This repository distributes official APK binaries and update metadata only. It is not a source-code license and does not grant permission to copy, modify, repackage, or redistribute BORG.

## Update metadata

The latest release metadata is published at:

`https://raw.githubusercontent.com/m117-design/Borg-Updates/main/latest.json`

APK packages are distributed as GitHub Release assets. BORG verifies the package signature and SHA-256 before installation.

## Software license

The BORG application and original BORG materials are proprietary. The accompanying [LICENSE](LICENSE) grants end users a limited right to install and use an unmodified official BORG APK. All rights not expressly granted are reserved.

Third-party components bundled in BORG remain governed by their own licenses. Their required copyright notices and license texts must accompany the relevant official release. Separately downloaded AI models, datasets, voices and plugins are not covered by the BORG application license and retain their own terms.

No source code, signing keys, credentials, private native build assets, or internal build artifacts belong in this public distribution repository.
