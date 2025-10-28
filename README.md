# Makerspace Docs

## Current sitemap (overview)
```
├── Home
├── Getting Started
├── Equipment
├── Training & Certifications
├── Leave Your Mark
├── Resources
├── Policies & Safety
└── Blog
```

## Detail Sitemap

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
├── Leave Your Mark/
│   ├── Overview (why contribute, impact stories)
│   ├── Current Opportunities
│   │   ├── Quick Wins (< 1 hour)
│   │   ├── Mini Projects (1-4 hours)
│   │   └── Ongoing Initiatives (recurring/long-term)
└── Hall of Fame (contributor recognition)
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
└── Blog (for updates/announcements)
```

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
yarn
```

## Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```bash
USE_SSH=true yarn deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
