<div align="center">
  <img width="860" alt="DRH - Object Layout Studio featured image" src="docs/media/Featured_Image.png" />
</div>

<br>

<div align="center">

# DRH - Object Layout Studio

### Support · Documentation · Feedback · Released

Align, distribute, arrange, orient, register, ground, quantize, and transform objects with precision.

![Status](https://img.shields.io/badge/status-Released-22C55E?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-00B7FF?style=for-the-badge)
![Blender](https://img.shields.io/badge/blender-4.2%2B-0B1F4D?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-EAF2FF?style=for-the-badge&labelColor=0B1F4D&color=EAF2FF)

<br>

DRH Blender Tools: support, documentation, and release information.

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

---

<div align="center">

DRH - Object Layout Studio helps Blender users align, distribute, arrange, move, rotate, orient, register, ground, quantize, and position objects through repeatable layout and geometry-aware workflows.

Complete and Lite are available through BlendKit.

This repository provides shared documentation, support, issue tracking, compatibility notes, and release information for both editions.

</div>

---

## Overview

DRH - Object Layout Studio is a Blender workflow utility designed to make object alignment, distribution, arrangement, transform matching, geometric alignment, registration, and precision placement faster and more repeatable.

The product is available in two editions:

- Complete - DRH - Object Layout Studio: Align, Transform, Advanced, and Utility.
- Lite - DRH - Object Layout Studio Lite: Align and Transform only.

The editions use separate extension IDs and can be installed independently. When Complete and Lite are enabled at the same time, both editions display a warning that the Complete edition is active and recommend disabling Lite to avoid duplicate tools.

## Editions

<div align="center">

| Complete | Lite |
|---|---|
| <img width="330" alt="DRH - Object Layout Studio Complete" src="docs/media/Logo.png" /> | <img width="330" alt="DRH - Object Layout Studio Lite" src="docs/media/LogoLite.png" /> |
| Align · Transform · Advanced · Utility | Align · Transform |
| 🟢 Released | 🟢 Released |

</div>

Both editions have released 1.0.0 listings on BlendKit. The support repository remains shared so documentation, issue tracking, compatibility information, and release notes stay in one place.

---

## Media preview

The screenshots below reflect the 1.0.0 interface and are organized by workflow area.

### Core layout workflows

<div align="center">

| Align | Transform |
|---|---|
| <img height="420" alt="Align workflow: origins, bounds, active reference, distribution, rearrange, locks, and hierarchy-safe controls" src="docs/media/ScreenShot_01.png" /> | <img height="420" alt="Transform workflow: separate and arrange controls, fixed step, bounds gap, axis order, locks, and hierarchy-safe controls" src="docs/media/ScreenShot_02.png" /> |

</div>

### Advanced workflows - Complete edition

<div align="center">

| Advanced overview | Active Reference, View Align, and Auto Orient |
|---|---|
| <img height="420" alt="Advanced workflow overview with Active Reference, View Align, Auto Orient, Feature Align, Registration, Surface, Line, Grid, and Circle or Arc tools" src="docs/media/ScreenShot_03.png" /> | <img height="420" alt="Active Reference, View Align, and Auto Orient controls" src="docs/media/ScreenShot_04.png" /> |
| Feature Align, Registration, and Surface | Along Any Line, Advanced Grid, and Circle or Arc |
| <img height="420" alt="Feature Align, point-pair registration, Best Fit or ICP, and Drop to Active Surface controls" src="docs/media/ScreenShot_05.png" /> | <img height="420" alt="Along Any Line, Advanced Grid, and Circle or Arc arrangement controls" src="docs/media/ScreenShot_06.png" /> |

</div>

### Utility workflows - Complete edition

<div align="center">

| Utility overview | Center & Ground, Quantize, and Origin to Bounds |
|---|---|
| <img height="420" alt="Utility workflow overview with Center and Ground, Transform Quantize, Origin tools, and Mesh Edit Align" src="docs/media/ScreenShot_07.png" /> | <img height="420" alt="Center and Ground, Transform Quantize, and Origin to Bounds controls" src="docs/media/ScreenShot_08.png" /> |
| Origin to Surface and Mesh Edit Align | Object context-menu integration |
| <img height="420" alt="Origin to Surface and Mesh Edit Align controls" src="docs/media/ScreenShot_09.png" /> | <img height="420" alt="Object context menu with Active Reference, Layout, Precision, and swap workflows" src="docs/media/ScreenShot_10.png" /> |

</div>

### Interface settings

<div align="center">
  <img width="700" alt="Object Layout Studio settings for sidebar tab, panel title, tabbed layout, collapsible subgroups, context menu, and performance profile" src="docs/media/ScreenShot_11.png" />
</div>

> Screenshots show the 1.0.0 interface. Marketplace packaging may evolve independently of this support documentation.

---

## What DRH - Object Layout Studio does

DRH - Object Layout Studio helps you position and organize objects using explicit alignment, bounds, spacing, transform, view, geometry, registration, and surface rules.

It is designed for scene-layout and geometry workflows where repeatable object relationships matter more than manually adjusting each transform one object at a time.

Use it to:

| Details |
|---|
| Align objects by origin or evaluated bounds |
| Align selected objects to the active object |
| Distribute objects by equal centers or true equal gaps |
| Arrange objects in 1D and 2D layouts |
| Move and rotate objects by exact values in local or world space |
| Match location, rotation, scale, and supported dimensions from the active object |
| Align objects relative to the current viewport |
| Auto-orient objects from mesh geometry |
| Align captured points, lines, and planes |
| Register source and target geometry using captured point pairs |
| Refine object alignment with best-fit / ICP workflows |
| Drop selected objects onto an active mesh surface |
| Center, ground, quantize, and refine object origins |
| Use the Lite edition when only Align and Transform workflows are needed |

---

### Capabilities

| Details |
|---|
| Precision origin and evaluated-bounds alignment |
| Active, selection, cursor, and world references |
| Equal-center and equal-gap distribution |
| Grid, line, circle, and arc arrangement workflows |
| Local and world transform controls |
| View-aware alignment and distribution |
| Geometry-driven Auto Orient |
| Point / Line / Plane feature alignment |
| Point-pair registration and best-fit refinement |
| Surface placement and grounding |
| Mesh Edit alignment helpers |
| Center & Ground and Transform Quantize |
| Configurable Sidebar Tab and Panel Title |
| Collapsible subgroup workflow |
| Object context-menu integration |
| Complete and Lite editions using one shared support repository |

---

<details>
  <summary>Feature reference</summary>

## Feature reference

### Align

| Details |
|---|
| Origin alignment |
| Evaluated bounds alignment |
| Active object reference |
| Selection reference |
| 3D Cursor reference |
| World reference |
| Minimum / Center / Maximum mapping |
| X / Y / Z alignment |
| Align to Active location |
| Align to Active rotation |
| Align to Active scale |
| 1D distribution |
| 2D grid distribution |
| Equal Centers |
| Equal Gaps |
| Swap transforms |
| Randomize transforms |

### Transform

| Details |
|---|
| Separate / Arrange workflow |
| Fixed-step arrangement |
| Bounds-aware arrangement |
| Move by exact distance |
| Rotate by exact angle |
| Local transform space |
| World transform space |
| Respect transform locks |
| Hierarchy-safe transform handling |

### Advanced - Complete edition

| Details |
|---|
| Active Reference |
| Along Any Line |
| Advanced Grid |
| Circle / Arc |
| View Align |
| Auto Orient |
| Surface-normal analysis |
| PCA-based orientation |
| Symmetry Assist |
| Point feature capture and alignment |
| Line feature capture and alignment |
| Plane feature capture and alignment |
| Arbitrary captured-line rotation |
| Directional slide |
| Geometric measurements |
| Point-pair registration |
| Best Fit / ICP |
| Drop to Active Surface |

### Utility - Complete edition

| Details |
|---|
| Mesh Edit Align |
| Flatten selected geometry by axis |
| Store Reference Line |
| Project selected vertices to line |
| Origin to Surface |
| Center & Ground |
| Transform Quantize |
| Origin to Bounds |
| Bottom-center origin placement |
| Bounds-center origin placement |
| Match Active Dimensions |

### Lite edition

| Details |
|---|
| Align |
| Align to Active |
| Distribution |
| Rearrangement |
| Separate / Arrange |
| Move |
| Rotate |
| No Advanced tools |
| No Utility tools |

</details>

---

## Intended users

DRH - Object Layout Studio is designed for:

| Details |
|---|
| Blender modelers |
| Hard-surface artists |
| Environment artists |
| Product visualization artists |
| Architectural visualization users |
| Technical artists |
| Asset creators |
| Scene-layout artists |
| Users working with repeated object arrangements |
| Users who need precise transform matching |
| Users aligning geometry references or scans |
| Users who want a smaller Align + Transform-only edition |

---

## Status

| Item | Details |
|---|---|
| Status | 🟢 Released |
| Current version | 1.0.0 |
| Minimum Blender version | 4.2.0 |
| Platforms | Windows, macOS, Linux |
| Release stage | Public BlendKit release |
| Editions | Complete and Lite |
| Distribution | [Complete on BlendKit](https://www.blendkit.com/asset-gallery-detail/63177030-cdb4-45ae-8bec-76a3ee48d151/) · [Lite on BlendKit](https://www.blendkit.com/asset-gallery-detail/0b1494ca-c801-4cbf-9783-46ddbcf0090f/) |
| Support repository | [DRH Object Layout Studio Support](https://github.com/pacosalasv/DRH_Object_Layout_Studio-Support) |

Both editions are publicly available through BlendKit. Compatibility feedback, usability comments, performance observations, Complete/Lite workflow feedback, and documentation corrections remain welcome.

---

## Technical notes

This add-on is source based, with:

- No obfuscation.
- No binary-only content.
- No external services required for normal operation.
- No account requirements.

The Complete edition uses native Blender geometry, BMesh, KDTree, and BVH workflows where applicable.

The add-on is intended to work locally inside Blender.

---

## Availability

Official installable releases are distributed through BlendKit:

- [DRH - Object Layout Studio Complete](https://www.blendkit.com/asset-gallery-detail/63177030-cdb4-45ae-8bec-76a3ee48d151/)
- [DRH - Object Layout Studio Lite](https://www.blendkit.com/asset-gallery-detail/0b1494ca-c801-4cbf-9783-46ddbcf0090f/)

This GitHub repository remains the central public location for support, documentation, issue tracking, compatibility reports, public feedback, and release notes. It does not serve as the official installable-package download location.

---

## Documentation

- [User Manual](docs/manual/user-manual.pdf)
- [Changelog](CHANGELOG.md)
- [Support](SUPPORT.md)

---


## Support

Use [GitHub Discussions](https://github.com/pacosalasv/DRH_Object_Layout_Studio-Support/discussions) for setup questions, workflow guidance, and general feedback. Use [GitHub Issues](https://github.com/pacosalasv/DRH_Object_Layout_Studio-Support/issues/new/choose) for reproducible bugs, regressions, compatibility problems, and focused feature requests.

Do not post credentials, payment information, license keys, confidential production files, private client material, or sensitive local paths.

Detailed guidance is available in [SUPPORT.md](SUPPORT.md).

## Support DRH development

Development support is optional. Contributions through [Ko-fi](https://ko-fi.com/pacosalasv) help cover maintenance, Blender compatibility work, documentation, and testing.

## License

This repository is distributed under GPL-3.0-or-later.

---

<div align="center">
