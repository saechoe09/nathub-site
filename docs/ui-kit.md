# NatHub UI Kit

This document records the visual language already present in the app and the constraints for new v1 surfaces.

## Principles

- Phenomenon first: controls recede until touched.
- Dark, quiet, tactile: black space, restrained light, glass and metal used with clear material intent.
- Native where it matters: navigation, settings, accessibility and system feedback follow iOS conventions.
- One visual hierarchy: one primary action per state; secondary controls must not compete with the experiment.

## Foundations

### Color

- Canvas: near black (`#020304` to `#000000`).
- Elevated surface: graphite (`#1B1C1F`) with low-opacity white edge light.
- Primary text: white at 94–100% opacity.
- Secondary text: cool white at 60–68% opacity.
- Tertiary text: white at 30–40% opacity.
- Accent light: blue-violet, reserved for the home orb and selected optical effects.
- Physical colors retain meaning: magnet north red, south blue; spectra use wavelength color.

### Type

- Display and card titles: GenWanMin2 TW where available.
- System and settings controls: the native iOS system font.
- Avoid long instructional copy over experiments.

### Shape and spacing

- Home card corner radius: approximately 29 pt, continuous curve.
- Primary control touch target: at least 44 × 44 pt.
- Page horizontal margin: 30 pt on phone.
- Card stack spacing: 14 pt.
- Settings rows use native grouped-list spacing and separators.

## Materials

- Glass is translucent, has one readable edge, and must not accumulate decorative rings.
- Metal uses restrained specular highlights and a stable light source.
- A material must be visually identifiable; otherwise prefer a simple matte surface.
- Do not use double borders on small circular controls or magnetic-needle bases.

## Controls

- Top navigation uses native `UIBarButtonItem` with SF Symbols.
- Left and right navigation items share placement, size and visual weight.
- Home settings uses one 44 pt circular icon button aligned to the title area.
- Pressed cards scale to 98.5% and darken slightly for 120 ms.
- Disabled controls remain legible but do not glow.

## Motion and feedback

- Decorative transitions: 120–320 ms with gentle ease-out.
- Physics motion follows the simulation rather than UI easing.
- Continuous gestures do not produce continuous haptics.
- Automatic demonstrations never produce haptics.
- When Reduce Motion is enabled, remove breathing and decorative motion while preserving user-triggered physical phenomena.

## Accessibility

- Every icon-only control has a localized accessibility label.
- Interactive targets are at least 44 × 44 pt.
- Do not communicate state through color alone.
- Keep experiment controls usable without relying on instructional text.
