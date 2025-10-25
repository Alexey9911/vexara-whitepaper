# Logo Directory

This directory contains the Vexara logos for light and dark themes.

## Required Files

- `light.png` - Logo for light mode (dark text/elements)
- `dark.png` - Logo for dark mode (light text/elements)

## Logo Specifications

### Dimensions
- **Width:** 120-180px recommended
- **Height:** 30-40px recommended
- **Aspect Ratio:** Maintain consistent ratio across both versions

### Format
- PNG with transparent background
- High resolution (2x for retina)
- Optimized file size (under 50KB each)

### Design Guidelines
- **Light mode:** Dark colors that work on white/light backgrounds
- **Dark mode:** Light colors that work on dark backgrounds
- Ensure readability at small sizes
- Include icon + wordmark or wordmark only

## Configuration

These logos are configured in `docs.json`:

```json
"logo": {
  "light": "/logo/light.png",
  "dark": "/logo/dark.png"
}
```

## Brand Colors

From `docs.json`:
- Primary: #9945FF (Solana purple)
- Light accent: #14F195 (Solana green)
- Dark accent: #9945FF

## Notes

- Logos should be recognizable at 32x32px (favicon size)
- Consider creating favicon.svg separately
- Test visibility on both light and dark backgrounds
