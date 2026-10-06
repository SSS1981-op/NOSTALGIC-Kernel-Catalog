# NOSTALGIC Kernel Catalog

The public download catalog for the NOSTALGIC OnePlus kernel releases.

It contains no private build workflows, device-source checkouts, credentials, or CI configuration. The catalog reads published release assets and provides direct downloads for:

- KernelSU Next 33301 / SuSFS 2.3.0 / NoMount Inline 2.0.0 kernel packages
- SukiSU Ultra 40940 / SuSFS 2.3.0 / NoMount Inline 2.0.0 kernel packages (158 of 158 verified)
- BakaSU (ReSukiSU) 35212 / SuSFS 2.3.0 kernel packages (77 of 158 verified)
- ReSukiSU 35055 / SuSFS 2.2.0 kernel packages migrated from the original 2026-08-09 release
- NoMount companion packages for both release families
- KernelSU Next, ReSukiSU, and BakaSU normal and spoofed manager APKs

## Download site

After GitHub Pages is enabled from the `docs/` directory, the catalog is available at:

`https://sss1981-op.github.io/NOSTALGIC-Kernel-Catalog/`

Only release assets whose names match the published NOSTALGIC naming convention appear as downloadable cards. Each card links directly to its GitHub release asset.

## Important

Use only the package matching your exact OnePlus device, OxygenOS generation, and kernel version. Keep a known-working boot image available before flashing.

The published catalog includes 77 checksum-verified BakaSU (ReSukiSU) 35212 packages across kernel 5.15 and 6.1, alongside the existing KernelSU, KernelSU Next, KowSU, SukiSU Ultra, and ReSukiSU release families. The BakaSU OP13R pilot stack was device-tested successfully; other devices are build-verified rather than represented as boot-tested.
