# Neutralizing antibody gp120 data

The complete `Neutralizing_Antibody_gp120` directory is stored as a lossless
xz-compressed tar archive split into numbered parts to stay below GitHub's
100 MB per-file limit.

## Reassemble and verify

From this directory, run:

```sh
cat Neutralizing_Antibody_gp120.tar.xz.part-* > Neutralizing_Antibody_gp120.tar.xz
sha256sum Neutralizing_Antibody_gp120.tar.xz
```

The expected SHA-256 checksum is:

```text
5e46373a71cbdcd9d6e2b24ec970864611394e5c995a45d59b2d3c089f29df3c  Neutralizing_Antibody_gp120.tar.xz
```

## Extract

```sh
tar -xJf Neutralizing_Antibody_gp120.tar.xz
```

The archive contains 35,714 filesystem entries under the top-level
`Neutralizing_Antibody_gp120` directory.
