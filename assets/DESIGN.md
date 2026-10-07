# Design system

## Intent
This profile README uses a restrained engineering-console aesthetic: instrumentation panels, system labels, precise spacing, and a subtle telemetry grid. The goal is to read like a technical dashboard rather than a badge wall or social media mockup.

## Theme tokens

### Dark theme
- Background: `#0D1117`
- Surface: `#111827`
- Surface-alt: `#161D2B`
- Panel border: `#2B3748`
- Primary text: `#E6EDF3`
- Secondary text: `#8B949E`
- Accent primary: `#D89B4A` (amber instrumentation tone)
- Accent secondary: `#6BD7D1` (cool telemetry cyan)
- Status green: `#4ADE80`

### Light theme
- Background: `#F6F8FA`
- Surface: `#FFFFFF`
- Surface-alt: `#EEF2F7`
- Panel border: `#D0D7DE`
- Primary text: `#1F2328`
- Secondary text: `#57606A`
- Accent primary: `#B76F1D`
- Accent secondary: `#1A8A9B`
- Status green: `#1F9D55`

## Typography
- Technical labels: `ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace`
- Headings and body: `-apple-system, "Segoe UI", Helvetica, Arial, sans-serif`
- SVGs use system fonts only; no external web fonts or CSS imports are used.

## Layout rules
- Define one clear information hierarchy: hero summary, active stack, projects, then social links.
- Use an 8px spacing scale and restrained panel borders.
- Favor modular blocks over decorative fills.
- Keep accent usage to one warm amber and one cool cyan; use status green only for activity indicators.

## Motion guidance
- Animation is subtle: faint grid drift or scanline movement at low opacity.
- No flashing or high-contrast pulsing.
- Static frames remain complete and intentional; reduced motion is respected when supported by the browser.

## Rationale
The amber accent references telemetry warning lights and dashboard instrumentation; the cyan accent suggests system traces and cloud/network signals. This keeps the interface technical without drifting into neon or gaming aesthetics.
