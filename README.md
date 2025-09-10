# Cody Spec Driven Development Framework

![Cody Spec Driven Development (SDD) Framework](./cody-logo.png)

© Copyright 2025 - Red Pill Blue Pill Studios, LLC - All Rights Reserved.

![Version](https://img.shields.io/badge/version-1.0.6-blue) [![License](https://img.shields.io/badge/license-Custom-green)](LICENSE.md)

Cody is a spec-driven development framework for builders who work with AI coding assistants. It helps Vibe Coders and teams turn rough ideas into organized projects through a repeatable **Plan → Build → Version** workflow.

See [Best Practices](#best-practices) and [Troubleshooting](#troubleshooting) for more guidance.

## Quick Start
1. **Download**: clone or download this repository.
2. **Install**: copy the `.cody` directory into your project's root.
3. **Activate**: ask your AI assistant to read `@.cody/config/activate.md`.
4. **Plan**: run `:cody plan` to generate discovery, PRD, and plan documents.
5. **Build**: run `:cody build` to create the feature backlog, then `:cody build version` to implement a specific version.

## Workflow Overview

```
Plan → Build → Version
```

- **Plan** – refine your idea into Discovery, PRD, and plan docs.
- **Build** – convert plans into a feature backlog.
- **Version** – implement features using design, tasklist, and retrospective docs.

## Command Reference

| Command | Purpose |
| --- | --- |
| `:cody help` | List available commands |
| `:cody plan` | Start planning and create docs |
| `:cody build` | Generate the feature backlog |
| `:cody build version` | Begin work on a specific version |
| `:cody add version` | Add a new version to the backlog |
| `:cody refresh` | Reload current context |
| `:cody refresh update` | Refresh and update `plan.md` and `prd.md` |
| `:cody relearn` | Re-read the `agent.md` instructions |
| `:cody assets list` | Show files in the assets folder |

## `.cody` Folder Structure

```
.cody/
  config/    # command definitions, templates, components
  project/   # generated planning and build documents
```

`config/` holds activation instructions and command files. `project/` contains your `plan/` and `build/` docs, including per-version directories.

## Best Practices

### For Planning Phase
> In the planning phase, be thorough in discovery since the Q&A sets the direction and de-risks assumptions. Iterate on your documents and do not rush; refine each section until it clearly reflects the intent. Think modularly by breaking complex ideas into manageable components that can be built, tested, and reused. Finally, consider dependencies early by identifying external requirements and integrations upfront so timelines and scope remain realistic.

### For Build Phase
> During the build phase, start small by delivering foundational features in the early versions to create momentum and validate the direction. Maintain the backlog consistently, updating it as requirements evolve to keep priorities clear and aligned. Incorporate regular retrospectives to reflect on what worked, what didn’t, and how to improve in the next cycle. Version strategically by grouping related features into logical sets, ensuring that each release delivers cohesive value while keeping the development process organized.

### For AI Collaboration
> When collaborating with AI, always provide context, the more detail captured during discovery, the more effective the AI’s assistance will be. Treat generated content as a draft, reviewing and refining it to ensure accuracy and alignment with your vision. Ask questions freely, using the AI to explore edge cases and uncover considerations you may not have thought of. Embrace iteration, as the process is designed for multiple rounds of refinement that gradually sharpen both the output and the overall direction.

## Troubleshooting

### Common Issues
- **Stuck in planning**: Set time limits for each document iteration
- **Overwhelming backlog**: Focus on next 2-3 versions, keep others high-level
- **Version scope creep**: Use the design document to maintain focus
- **Skipping retrospectives**: These are crucial for continuous improvement

### Getting Unstuck
- Return to the discovery document to reconnect with core vision
- Break large features into smaller, more manageable pieces
- Use the AI agent to explore alternative approaches
- Review successful past versions for patterns to repeat

## License

This project is licensed under a custom license. See the [LICENSE.md](LICENSE.md) file for details.

