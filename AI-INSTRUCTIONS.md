# AI Implementation Instructions

You are implementing the Figma design: "Responsive Design".

## Project Context

- Project name: logifa
- Selected technologies: HTML, CSS, JavaScript, jQuery, Tailwind CSS
- Additional instructions: None

## Before coding

1. Ask for the absolute project path.
2. Confirm the required technologies, frameworks and versions.
3. Ask whether an existing project structure must be preserved.
4. Inspect the existing project before editing or creating files.
5. Do not assume a framework, build tool, naming convention or directory structure.
6. Wait for the user's answers before implementation.

## Responsive Export Information

- Selection mode: Multiple Independent Frames
- Number of exported designs: 3

### Available Responsive Frames

- Desktop: about us desktop (1440 × 2889px)
- Tablet: about us tablet (768 × 3346px)
- Mobile: about us mobile (390 × 2624px)

### Responsive Implementation Rules

1. Inspect every exported responsive frame before writing code.
2. Desktop, Tablet and Mobile frames are separate design references.
3. Compare corresponding elements across available frames.
4. Identify actual changes in dimensions, spacing, typography, visibility, alignment and layout.
5. Preserve the differences that are visible in the exported designs.
6. Do not assume that a missing responsive frame exists.
7. Do not generate unsupported layouts or visual changes based on assumptions.
8. Use responsive CSS and breakpoints appropriate to the actual design dimensions.
9. Do not treat the width of a frame as an exact CSS breakpoint unless the design or project requirements establish that.
10. If a responsive behavior cannot be determined from the supplied frames, ask the user before making a major assumption.
11. Preserve the visual hierarchy and content across responsive versions unless the Figma references show otherwise.

## Design Fidelity

- Treat design-spec.md, design-data.json and supplied assets as the source of truth.
- Reproduce hierarchy, dimensions, spacing, colors, typography and alignment.
- Use assets from the assets/ directory and preserve their filenames.
- Keep code readable, modular and maintainable.
- Do not replace real assets with generated placeholders.
- Do not invent functionality where the design does not define it.
- If design details conflict or are ambiguous, ask before making a major assumption.

## Export Context

- Figma page: log
- Root frame: Responsive Design
- Root node ID: 435:21807,435:28217,435:34593
- Selection mode: Multiple Independent Frames
- Exported designs: 3
- Exported at: 2026-11-02T12:12:13.055Z

## Expected Workflow

1. Inspect the exported JSON and all design structures.
2. Inspect all supplied assets.
3. Compare the available responsive versions.
4. Plan the component structure.
5. Identify responsive differences.
6. Implement the design using the confirmed technology stack.
7. Verify the result against every available Figma frame.
8. Report missing information instead of inventing design decisions.
