## Description

This flake allows building [pixeldroid](https://pixeldroid.org/) app using
[nix](https://nix.dev/install-nix).

### TODO

- [ ] Bug with deps.json reproducibility with dependency `group-index` in
      `maven.google.com` section.
- [ ] Emulator setup to launch the application.
- [ ] Document how to build and run and setup `pixelfed` as well with `forge`.
- [ ] Debug vs release builds and signing the apks.
- [ ] Move to forge once an android builder is implemented in forge.
- [ ] Github actions PoC to use nix to build and sign the apks.
