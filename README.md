# NOSTALGIC Kernel Catalog

The public download catalog for the NOSTALGIC OnePlus kernel releases.

It contains no private build workflows, device-source checkouts, credentials, or CI configuration. The catalog reads published release assets and provides direct downloads for:

- KernelSU Next 33301 / SuSFS 2.3.0 / NoMount Inline 2.0.0 kernel packages
- KernelSU Next 33214 / SuSFS 2.2.0 / NoMount 1.1.1 kernel packages migrated from the original v2.2.0-r1 release
- KernelSU 32525 / SuSFS 2.2.0 / NoMount 1.1.1 kernel packages migrated from the original v2.2.0-r2 release
- ReSukiSU 35055 / SuSFS 2.2.0 kernel packages migrated from the original 2026-08-09 release
- NoMount 1.1.1 companion packages and the current NoMount 2.0.0 module
- KernelSU, KernelSU Next, and ReSukiSU manager APKs, including the available spoofed variants

## Download site

After GitHub Pages is enabled from the `docs/` directory, the catalog is available at:

`https://sss1981-op.github.io/NOSTALGIC-Kernel-Catalog/`

Only release assets whose names match the published NOSTALGIC naming convention appear as downloadable cards. Each card links directly to its GitHub release asset.

## Important

Use only the package matching your exact OnePlus device, OxygenOS generation, and kernel version. Keep a known-working boot image available before flashing.

The live catalog includes the four final release families: 93 KernelSU Next 33301 packages, 156 KernelSU Next 33214 packages, 156 KernelSU 32525 packages, and 122 checksum-verified ReSukiSU packages across OxygenOS 14, 15, and 16. Superseded 33301 staging batches are intentionally excluded from the catalog.
