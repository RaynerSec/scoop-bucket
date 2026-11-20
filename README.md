# RaynerSec Scoop Bucket

[![Tests](https://github.com/RaynerSec/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/RaynerSec/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/RaynerSec/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/RaynerSec/scoop-bucket/actions/workflows/excavator.yml)
[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

Official Scoop bucket for RaynerSec software.

## Usage

### Add Bucket

```powershell
scoop bucket add raynersec https://github.com/RaynerSec/scoop-bucket
```

### Install an Application

```powershell
scoop install raynersec/<app-name>
```

For example, to install **Hyper-V-Switch**:

```powershell
scoop install raynersec/hyper-v-switch
```

### Update Applications

```powershell
scoop update <app-name>
```

Or update all installed applications at once:

```powershell
scoop update *
```

## Available Packages

| Package | Version | Description | License |
| :--- | :--- | :--- | :--- |
| [hyper-v-switch](https://github.com/RaynerSec/Hyper-V-Switch) | `1.0.1.0` | Enables and disables Hyper-V Hypervisor so you can use other virtualization tools simultaneously. | `GPL-3.0-or-later` |

## Notes

* **Prerequisites:** Some applications (such as `hyper-v-switch`) require the latest Microsoft Visual C/C++ Redistributable (`scoop install extras/vcredist2022`).
* **Permissions:** System-level utilities may trigger a Windows UAC prompt when launched.
* **Issues & Bug Reports:** Please open issues in each application's respective repository rather than this bucket repository.

## License

The manifests and scripts in this Scoop bucket are released into the public domain under **The Unlicense**. Individual software packages installed through this bucket remain subject to their own respective licenses.
