<div align="center">

<img width="860" alt="DRH Object Layout Studio" src="docs/media/Logo.png" />

# DRH - Object Layout Studio

**Align to the geometry you actually see, not the origin point that lied to you.**

![Status](https://img.shields.io/badge/Status-Released-22C55E?style=for-the-badge) ![Version](https://img.shields.io/badge/Version-1.0.0-00B7FF?style=for-the-badge) ![Blender](https://img.shields.io/badge/Blender-4.2%2B-0B1F4D?style=for-the-badge)

[![Complete](https://img.shields.io/badge/Download-Complete-0B1F4D?style=for-the-badge)](https://www.blendkit.com/asset-gallery-detail/63177030-cdb4-45ae-8bec-76a3ee48d151/) [![Lite](https://img.shields.io/badge/Download-Lite-334155?style=for-the-badge)](https://www.blendkit.com/asset-gallery-detail/0b1494ca-c801-4cbf-9783-46ddbcf0090f/) [![Issues](https://img.shields.io/badge/Support-Issues-1E5BFF?style=for-the-badge)](https://github.com/pacosalasv/DRH_Object_Layout_Studio-Support/issues)

</div>

## The wall

Blender aligns to origins. Your model has a bevel, a solidify, and a mirror on it, so the origin sits nowhere near the visible edge. You align two chairs to the left, look at the viewport, and one of them is floating 4 cm off the wall.

Object Layout Studio aligns against evaluated bounds: the shape after modifiers do their work. That single difference removes most of the nudge, eyeball, nudge again loop.

<img src="docs/media/ScreenShot_01.png" alt="Layout tools panel" width="100%" />

## Two builds, one panel

**Complete** is the full workflow: align, distribute, arrange, orient, register, ground, quantize, and transform, with geometry-aware handling for objects whose real bounds don't match their origin.

**Lite** is the same alignment core without the geometry-aware extras. Align, space, rotate, match transforms. Smaller surface, fewer decisions.

## References you can align against

Origin, evaluated bounds, the active object, the selection, the 3D cursor, or world space. Each reference maps through minimum, center, or maximum, so "align left" means the left edge of the thing you see.

<img src="docs/media/ScreenShot_02.png" alt="Reference and mapping options" width="100%" />

## Who it's for

Scene assembly where objects were modeled by someone else. Interior and product layouts measured against walls and shelves. Kitbashing sessions where 60 pieces need to sit at consistent heights.

## Get it

Free on BlendKit, Blender 4.2 or newer.

| Build | Download |
|---|---|
| Object Layout Studio Complete 1.0.0 | [BlendKit](https://www.blendkit.com/asset-gallery-detail/63177030-cdb4-45ae-8bec-76a3ee48d151/) |
| Object Layout Studio Lite 1.0.0 | [BlendKit](https://www.blendkit.com/asset-gallery-detail/0b1494ca-c801-4cbf-9783-46ddbcf0090f/) |

Changelog: [CHANGELOG.md](CHANGELOG.md) · Bugs and requests: [open an issue](https://github.com/pacosalasv/DRH_Object_Layout_Studio-Support/issues)

<div align="center">
  <a href="https://ko-fi.com/pacosalasv">
    <img width="560" alt="Support on Ko-fi" src="docs/media/SupportMe.png" />
  </a>
</div>
