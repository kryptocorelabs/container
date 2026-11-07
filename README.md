# KryptoCore Container

[![Preview](https://img.shields.io/badge/status-alpha-orange)](https://github.com/kryptocorelabs/container/releases)

Portable encrypted archives for files and folders. Powered by the open-source
[KryptoCore library](https://github.com/kryptocorelabs/kryptocore).

[Downloads](https://github.com/kryptocorelabs/container/releases)
· [Usage](USAGE.md) · [Security](SECURITY.md)

<img src="assets/logo.png" alt="KryptoCore Container" width="150">

## Get started

Download and extract the Windows x64 ZIP and open KryptoCore-Container.exe.
No separate Python or .NET installation is required.

1. Select **Dateien verschlüsseln**, add copies of files and choose a passphrase.
2. Save the encrypted archive and share the passphrase separately.
3. The recipient opens the archive in Container and extracts it to a new folder.

The Windows runtime is included. Optional OpenSSH and ClamAV tools are installed separately.


## Preview status

Version 0.1.0-alpha.1. Use synthetic data and retain original files and
independent backups. The executable is unsigned. There is no independent
security audit or guarantee of recovery after losing a passphrase or identity.

This repository hosts documentation and downloads. Application source is
maintained separately. KryptoCore is available under MIT. Third-party
components retain their own terms. The ZIP includes license texts and notices.

For an independent offline interface to existing KCC files, see the
[Rescue preview](https://github.com/kryptocorelabs/rescue). It uses the same
authenticated reader and writes to a fresh destination. It does not replace
Container's sender-signature or optional scanner tools.
