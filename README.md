
# Unofficial builds of Zed for Windows

[![Test Scripts](https://github.com/deevus/zed-windows-builds/actions/workflows/test.yml/badge.svg)](https://github.com/deevus/zed-windows-builds/actions/workflows/test.yml)
[![Test Integration](https://github.com/deevus/zed-windows-builds/actions/workflows/test-integration.yml/badge.svg)](https://github.com/deevus/zed-windows-builds/actions/workflows/test-integration.yml)
[![Scheduled Nightly Build](https://github.com/deevus/zed-windows-builds/actions/workflows/nightly.yml/badge.svg)](https://github.com/deevus/zed-windows-builds/actions/workflows/nightly.yml)
[![Scheduled Stable Build](https://github.com/deevus/zed-windows-builds/actions/workflows/stable.yml/badge.svg)](https://github.com/deevus/zed-windows-builds/actions/workflows/stable.yml)

#### See the releases section for the latest build

This repository runs a Github Actions workflow daily to build a release version of the Zed Editor for Windows.

It is based on https://github.com/deevus/zed-windows-builds, but adds a bugfix for [zed-industries/zed#20559](https://github.com/zed-industries/zed/issues/20559), an issue that prevented most LSPs from being started.

### Credits
- [deevus](https://github.com/deevus) for creating the Github Actions workflow these builds are forked from. See the [original](https://github.com/deevus/zed-windows-builds).
- [someone120](https://github.com/someone120) for implementing the fix submitted in [zed-industries/zed#22600](https://github.com/zed-industries/zed/pull/22600).
- [zed-industries](https://github.com/zed-industries) for open-sourcing Zed, making community fixes possible.
