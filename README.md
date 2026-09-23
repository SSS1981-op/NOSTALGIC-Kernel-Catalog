# NOSTALGIC Kernel Catalog

The public download catalog for the NOSTALGIC OnePlus kernel releases.

It contains no private build workflows, device-source checkouts, credentials, or CI configuration. The catalog reads published release assets and provides direct downloads for:

- KernelSU Next 33301 / SuSFS 2.3.0 / NoMount Inline 2.0.0 kernel packages, with earlier releases retained
- NoMount 2.0 companion package
- KernelSU Next normal and spoofed manager APKs

## Download site

After GitHub Pages is enabled from the `docs/` directory, the catalog is available at:

`https://sss1981-op.github.io/NOSTALGIC-Kernel-Catalog/`

Only release assets whose names match the published NOSTALGIC naming convention appear as downloadable cards. Each card links directly to its GitHub release asset.

## Important

Use only the package matching your exact OnePlus device, OxygenOS generation, and kernel version. Keep a known-working boot image available before flashing.

The 51-target kernel 6.1 release is build-tested. The user reported boot testing of the OP13R pilot stack; other devices are not represented as boot-tested. The remaining 105 matrix targets are not included in this release.
