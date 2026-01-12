# Birth Model — Nursing & Clinician Handoff Demo

Interactive demonstration of Birth Model's Nursing and Clinician Handoff features for Labor & Delivery units.

## Features

- **Motherboard View**: Overview of all L&D patients at a glance
- **Nursing Handoff**: Comprehensive shift-change documentation with 12+ sections
- **Clinician Handoff (SBAR)**: Structured handoff format for providers with:
  - AI-generated zones (teal background) - auto-updated from EHR
  - My Notes zones (yellow background) - preserved on refresh
  - FHR Manual Entry section
  - Refresh indicators and timestamps
  - Global Notes section
- **Handoff Preview Modal**: Printable document generation
- **Step-by-step Demo**: Guided walkthrough with play/pause and manual navigation
- **A4 Printable PDF**: Print-optimized clinician handoff document

## Files

| File | Description |
|------|-------------|
| `index.html` | Interactive demo with Motherboard, Nursing & Clinician Handoffs |
| `clinician-handoff-print.html` | Print-optimized HTML for Clinician Handoff |
| `clinician-handoff-print.pdf` | Ready-to-print Clinician Handoff PDF |
| `nursing-handoff-print.html` | Print-optimized HTML for Nursing Handoff |
| `nursing-handoff-print.pdf` | Ready-to-print Nursing Handoff PDF |
| `images/Birth_Model_Logo.png` | Logo asset |

## Viewing the Demo

Visit: `https://[your-username].github.io/[repo-name]/`

Or open `index.html` locally in any modern browser.

## Demo Controls

- **▶ Play Full Demo**: Auto-plays through all 31 steps
- **⏸ Pause**: Pauses the demo
- **◀ Back / Next ▶**: Manual step navigation  
- **⟲ Reset**: Returns to initial state
- **1x / 2x**: Playback speed toggle

## Dual-Zone Architecture

Each SBAR section contains two visually distinct zones:

| Zone | Description | On Refresh |
|------|-------------|------------|
| **🤖 AI Zone** | Auto-generated content from EHR + AI synthesis (teal bg) | **REPLACED** |
| **📝 My Notes** | User-added notes, tables, customizations (yellow bg) | **PRESERVED** |

## Hosting on GitHub Pages

1. Create a new repository on GitHub
2. Upload all files maintaining the folder structure
3. Go to Settings → Pages
4. Set Source to "Deploy from a branch"
5. Select `main` branch and `/ (root)` folder
6. Save and wait for deployment

## License

© Birth Model — Confidential Patient Information Demo
