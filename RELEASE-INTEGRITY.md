# Release integrity

Use only the [official releases](https://github.com/AdnanNaous/cs-work-hub-downloads/releases) or the verified Marketplace publisher. Download the accompanying SHA-256 checksum file and compare the exact asset filename and digest (`Get-FileHash -Algorithm SHA256 <file>` on PowerShell, or `sha256sum <file>` on Linux). A checksum detects corruption or mismatch; it does not establish publisher authenticity by itself. Stop if the digest differs or the checksum is missing.

Maintainers must build from the reviewed private commit, inspect every archive entry for private source/personal data and verify the manifest identity, version, license and notices before publication. Retain the reviewed artifact and digest independently of GitHub. Preserve previous licensing grants. This public repository is a distribution catalog, not a backup of private development history. Publishing remains a separate, explicit approval step.
