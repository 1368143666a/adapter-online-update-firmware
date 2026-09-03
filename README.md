# Adapter Online Update Firmware

Public delivery repository for the Adapter Online Update System.

- `delivery/manifest.json` is the Ed25519-signed delivery catalog read directly by the user client.
- Firmware binaries are published as GitHub Release assets.
- Publishing and policy management are performed by the local on-demand administrator tool.
- Serial-specific upgrade or rollback policies are represented in the signed catalog.

The signing private key is not stored in this repository. Ordinary users receive only the update client and its public verification key.