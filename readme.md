<h1 align="center">VirtISO ARM<br />
<div align="center">
<a href="https://github.com/qemus/virtiso-arm"><img src="https://github.com/qemus/virtiso-arm/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso-arm/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso-arm/)
  [![Version](https://img.shields.io/github/v/release/qemus/virtiso-arm?label=version&sort=semver&display_name=release&color=066da5)](https://github.com/qemus/virtiso-arm/releases)
  [![Size](https://img.shields.io/badge/size-6.8_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso-arm/releases)
  
</div></h1>

VirtISO is a slim image of the VirtIO drivers for Windows ARM guests.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) from 700 MB to just 6 MB in size.

# Features ✨

  - Stripped all x86/i386/AMD64 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Usage 🚀

  It contains every ARM64 driver the official image has, so there is zero loss of functionality.

> [!TIP]
> See also [VirtISO WHQL](https://github.com/qemus/virtiso-whql/) if you need signed drivers, [VirtISO x64](https://github.com/qemus/virtiso/) for x64 drivers and [VirtISO x86](https://github.com/qemus/virtiso-x86/) for x86 drivers.

# Stars 🌟
[![Stars](https://starchart.cc/qemus/virtiso-arm.svg?variant=adaptive)](https://starchart.cc/qemus/virtiso-arm)

# Disclaimer ⚖️

  *This project contains binaries provided by Red Hat, Inc. and/or its affiliates.*
