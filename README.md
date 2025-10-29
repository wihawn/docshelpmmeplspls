# Makerspace Documentation

Documentation site for the [Makerspace](https://www.ashoka.edu.in/digital-makerspace/) under the [Mphasis AI & Applied Tech Lab at Ashoka](https://www.ashoka.edu.in/page/mphasis-lab/).

## What's Inside

- Equipment guides - 3D printers, woodworking tools, electronics, textiles, drones, and more
- Training resources - Certifications and tutorials
- Safety protocols - Keep everyone safe
- Leave Your Mark - Ways to contribute to the makerspace community

## Quick Start

```bash
npm install
npm start
```

Opens at http://localhost:3000 with live reload.

## Contributing

We'd love your help! Whether you're fixing a typo or documenting equipment:

1. See [CONTRIBUTING.md](./CONTRIBUTING.md) for setup instructions
2. Check [WRITING_TEMPLATES.md](./WRITING_TEMPLATES.md) for documentation templates
3. Browse [Issues](https://github.com/Makerspace-Ashoka/docs/issues) for tasks tagged "good first issue"
4. Visit our ["Leave Your Mark"](#) page for quick contribution ideas

## Project Structure

```
docs/           # All documentation content
static/img/     # Images and assets
blog/           # Announcements and updates
```

See the [detailed sitemap](#sitemap) below for full content structure.

## Build & Deploy

```bash
npm run build        # Generate static site
npm run serve        # Preview production build locally
```

**Deploy to GitHub Pages:**
```bash
GIT_USER=<username> npm run deploy
```

## Tech Stack

Built with [Docusaurus](https://docusaurus.io/) - a modern static site generator optimised for documentation.

---

## Sitemap

<details>
<summary>Click to expand full site structure</summary>

```
docs.makerspace.../
├── Home
├── Getting Started
│   ├── Access & Hours
│   ├── Safety Basics
│   ├── Code of Conduct
│   └── Your First Visit
├── Equipment
│   ├── 3D Printing & Digital Fabrication
│   │   ├── Voron 2.4 (×3)
│   │   ├── Voron 0.2 (×2)
│   │   ├── Ender 3 (×2)
│   │   ├── Ender 6
│   │   ├── Ultimaker
│   │   └── Cricut Maker 3
│   ├── Woodworking
│   │   ├── Mitre Saw
│   │   ├── Power Tools Overview
│   │   └── Hand Tools
│   ├── Electronics & Testing
│   │   ├── Oscilloscope
│   │   ├── Function Generator
│   │   ├── SMD Rework Station
│   │   ├── Hot Plate
│   │   ├── NanoVNA-H
│   │   ├── HackRF One
│   │   └── LimeSDR
│   ├── Textiles & Fabric
│   │   ├── Brother Innovis V3
│   │   ├── Bernette Serger
│   │   ├── Usha Janome Dreammaker 120
│   │   └── Fabric Materials Guide
│   ├── Audio & Video Production
│   │   ├── Recording Setup (Focusrite, DT990)
│   │   ├── DJ Equipment (DDJ FLX4)
│   │   └── Projectors
│   ├── Drones & Aerial
│   │   ├── DJI Matrice 4T
│   │   └── DJI Mavic 3E
│   └── Computing Resources
│       ├── Mac Minis & Studio
│       ├── GPU Workstation (3090)
│       └── iPads
├── Training & Certifications
│   ├── Overview
│   ├── Self-Paced Tutorials
│   ├── Required Certifications
│   └── Safety Quizzes
├── Leave Your Mark
│   ├── Overview
│   ├── Current Opportunities
│   │   ├── Quick Wins (< 1 hour)
│   │   ├── Mini Projects (1-4 hours)
│   │   └── Ongoing Initiatives
│   └── Hall of Fame
├── Resources
│   ├── Tutorials & Guides
│   ├── Material Specifications
│   ├── Software & Downloads
│   └── Project Ideas
├── Policies & Safety
│   ├── General Lab Safety
│   ├── Emergency Procedures
│   ├── Equipment-Specific Safety
│   └── Material Handling
└── Blog
```

</details>

## License

This repository is covered under the Apache 2.0 license, see [LICENSE](./LICENSE).
