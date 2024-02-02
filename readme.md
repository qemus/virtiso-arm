<h1 align="center">Virtiso ARM<br />
<div align="center">
<img src="https://github.com/qemus/virtiso-arm/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" />
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso-arm/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso-arm/)
  [![Version](https://img.shields.io/github/v/tag/qemus/virtiso-arm?label=version&sort=semver&color=066da5)](https://github.com/qemus/virtiso-arm/releases)
  [![Size](https://img.shields.io/badge/size-25.9_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso-arm/releases)
  
</div></h1>

Virtiso is a slim image of the KVM/QEMU Virtio drivers for Windows ARM guests.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) of 600 MB to 25 MB in size.

# Methods used

  - Stripped AMD64/i386/x86 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Usage

  It contains every ARM64 driver the official image has, so there is zero loss of functionality.

# Disclaimer

  This project contains binaries provided by Red Hat, Inc. and/or its affiliates.
