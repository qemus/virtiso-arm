<h1 align="center">VirtISO ARM<br />
<div align="center">
<a href="https://github.com/qemus/virtiso-arm"><img src="https://github.com/qemus/virtiso-arm/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso-arm/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso-arm/)
  [![Version](https://img.shields.io/github/v/release/qemus/virtiso-arm?label=version&sort=date&display_name=release&color=066da5)](https://github.com/qemus/virtiso-arm/releases)
  [![Size](https://img.shields.io/badge/size-6.8_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso-arm/releases)
  
</div></h1>

VirtISO is a slim image of the VirtIO drivers for Windows ARM64 guests as provided by Fedora.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) from 700 MB to just 6 MB in size.

# Features ✨

  - Stripped all x86/i386/AMD64 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Download

  You can download the [latest version](https://github.com/qemus/virtiso-arm/releases/download/v0.1.285-1/virtio-win-0.1.285.iso) from the [Releases](https://github.com/qemus/virtiso-arm/releases) page.

# Usage 🚀

  It contains every ARM64 driver the official image has, so there is zero loss of functionality.

> [!TIP]
> See also [VirtISO x64](https://github.com/qemus/virtiso/) for the x64 drivers, [VirtISO WHQL](https://github.com/qemus/virtiso-whql/) for WHQL certified drivers, and [VirtISO x86](https://github.com/qemus/virtiso-x86/) for x86 drivers.

## Stars 🌟
[![Stargazers](https://raw.githubusercontent.com/star-stats/stars/refs/heads/data/charts/qemus-virtiso-arm.svg)](https://github.com/qemus/virtiso-arm/stargazers)

# Disclaimer ⚖️

  *This project contains binaries provided by Red Hat, Inc. and/or its affiliates.*
