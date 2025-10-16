<svg xmlns="http://www.w3.org/2000/svg" width="1600" height="420" viewBox="0 0 1600 420">
  <defs>
    <linearGradient id="g" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#6ee7ff"/>
      <stop offset="1" stop-color="#8b5cf6"/>
    </linearGradient>
  </defs>
  <rect width="1600" height="420" fill="#0b1220"/>
  <g transform="translate(120,110)">
    <text x="0" y="0" font-family="Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica" font-size="72" font-weight="800" fill="url(#g)">
      Abgen
    </text>
    <text x="0" y="64" font-family="Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica" font-size="28" fill="#cbd5e1">
      Automated abstract generation for analog & mixed-signal IC layout
    </text>
  </g>
  <g opacity=".15" transform="translate(1100,40)">
    <circle cx="120" cy="120" r="120" fill="url(#g)"/>
    <rect x="220" y="40" width="200" height="36" rx="8" fill="#6ee7ff"/>
    <rect x="220" y="100" width="200" height="36" rx="8" fill="#8b5cf6"/>
    <rect x="220" y="160" width="160" height="36" rx="8" fill="#22d3ee"/>
  </g>
</svg># Abgen — Open Abstract Generation Flow

Abgen provides a clean, reproducible flow for generating layout abstracts in Cadence Virtuoso.  
It helps automate the process of creating block abstracts for integration and verification,  
supporting any PDK or geometry.

## Features
- Unified setup for abstract generation across multiple projects
- Configurable layout boundaries and pin mapping
- Optional SKILL utilities and shell/Python scripting
- Works across analog, digital, and mixed-signal environments

## Directory layout

