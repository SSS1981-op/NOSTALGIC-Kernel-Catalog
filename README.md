# NOSTALGIC Kernel Catalog

The public download catalog for the NOSTALGIC OnePlus kernel releases.

It contains no private build workflows, device-source checkouts, credentials, or CI configuration. The catalog reads published release assets and provides direct downloads for:

- KernelSU Next 33301 / SuSFS 2.3.0 / NoMount Inline 2.0.0 kernel packages
- ReSukiSU 35055 / SuSFS 2.2.0 kernel packages migrated from the original 2026-08-09 release
- NoMount companion packages for both release families
- KernelSU Next and ReSukiSU normal and spoofed manager APKs

## Download site

After GitHub Pages is enabled from the `docs/` directory, the catalog is available at:

`https://sss1981-op.github.io/NOSTALGIC-Kernel-Catalog/`

Only release assets whose names match the published NOSTALGIC naming convention appear as downloadable cards. Each card links directly to its GitHub release asset.

## Important

Use only the package matching your exact OnePlus device, OxygenOS generation, and kernel version. Keep a known-working boot image available before flashing.

The published catalog includes 51 KernelSU Next kernel 6.1 targets, 15 KernelSU Next kernel 6.12/6.6 targets, and 122 checksum-verified ReSukiSU packages across OxygenOS 14, 15, and 16. The user reported boot testing of the OP13R pilot stack; other devices are not represented as boot-tested.
