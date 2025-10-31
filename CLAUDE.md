# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a personal GitHub profile repository for Hawkli-1994, designed as a showcase/landing page. The repository contains only a README.md file with a cyberpunk-themed design featuring dynamic SVG typing effects, technology badges, and GitHub statistics.

## Repository Structure

- **README.md**: Main profile showcase page with:
  - Dynamic typing SVG headers (using readme-typing-svg.herokuapp.com)
  - Technology stack badges (Python, JavaScript, TypeScript, Go, Rust, React, Vue.js, Next.js, Docker, Kubernetes, AWS, GCP)
  - GitHub statistics and activity visualization
  - Profile metrics (views, followers, stars)

## Design Theme

The README follows a consistent cyberpunk aesthetic with:
- **Primary Colors**: Gold (#FFD700) for text and highlights
- **Secondary Colors**: Orange-Red (#FF4500) for accent elements
- **Background**: Black (#000000) throughout
- **Fonts**: Fira Code and Orbitron for a modern tech aesthetic
- **Layout**: Centered design with responsive elements

## External Services Used

The README integrates with multiple external services for dynamic content:
- `readme-typing-svg.herokuapp.com` - Animated typing effects
- `komarev.com/ghpvc` - Profile view counter
- `img.shields.io` - Technology badges
- `github-readme-stats.vercel.app` - GitHub statistics visualization
- `github-profile-trophy.vercel.app` - Achievement showcase

## Common Tasks

### Updating README Content
When making changes to the README:
1. Maintain the cyberpunk color scheme (gold, orange-red, black)
2. Use consistent fonts (Fira Code, Orbitron)
3. Keep external service URLs intact for dynamic content
4. Test changes in GitHub's markdown preview before committing

### Modifying Technology Stack
To update technology badges:
- Use shields.io format: `https://img.shields.io/badge/-TECHNAME-COLOR?style=for-the-badge&logo=LOGO&logoColor=FFD700&color=000000`
- Replace TECHNAME, COLOR, and LOGO with appropriate values
- Maintain consistent styling with gold logo colors on black backgrounds

### Adjusting SVG Animations
For typing SVG modifications:
- Use `readme-typing-svg.herokuapp.com` endpoint
- Maintain current color parameters (color=FFD700, background=000000)
- Keep fonts consistent (Fira Code for headers, Orbitron for titles)
- Adjust width/height parameters as needed for content

## Git Workflow

This repository follows a simple single-branch workflow:
- Main development happens on `main` branch
- Recent commits show iterative refinements to README design and layout
- Focus is on visual presentation improvements rather than functional code

## Notes

- This is a profile showcase repository, not a code project
- No build scripts, tests, or development dependencies
- All content is markdown with embedded HTML for external service integration
- The primary purpose is visual presentation and GitHub profile enhancement