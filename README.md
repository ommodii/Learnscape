# Learnscape

Personal development repository and documentation hub for technical projects and academic notes.

**Live Site:** [jazzy-pithivier-4fc17d.netlify.app](https://jazzy-pithivier-4fc17d.netlify.app)

## Overview
This site serves as a central location for project logs and systems documentation. The focus is on backend logic, infrastructure, and functional utility. Design is handled via templates to prioritize development speed and system architecture.

## Technical Stack
Tools are selected based on functional requirements for the project at hand.

* **Frameworks:** Astro, React
* **Styling:** Tailwind CSS
* **Tools:** Netlify

## Development Workflow
The development process is structured around a macOS environment and automated deployment pipelines.

1. **Secrets:** All API keys and credentials (e.g. Brevo, Google Analytics) are managed via environment variables and excluded from the repository.
2. **Deployment:** Git-based workflow. Pushing to the main branch triggers automated builds on Netlify.
3. **Content:** Written in MDX. This allows for React components to be embedded directly into technical notes and project logs.
