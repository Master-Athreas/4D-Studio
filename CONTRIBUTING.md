# Contributing to 4D Studio

Thanks for your interest in contributing! Here's how to get involved.

## How It Works

1. **Fork** this repo to your own GitHub account
2. **Clone** your fork locally
3. **Create a branch** for your feature or fix (`git checkout -b feature/my-thing`)
4. **Make your changes** in `index.html`
5. **Test** by opening `index.html` in a browser — no build step needed
6. **Commit** with a clear message
7. **Push** to your fork
8. **Open a Pull Request** back to this repo

All PRs are reviewed before merging. Nothing goes in without approval.

## What to Work On

Check the [Issues](../../issues) tab for open tasks. Good first contributions:

- **Bug fixes** — if something doesn't work right, fix it and PR
- **UI improvements** — better layouts, colors, interactions
- **New export formats** — FBX, OBJ, etc.
- **Performance** — faster rendering, less memory usage
- **Documentation** — better README, tutorials, examples

### Bigger Features (discuss first)

For larger features, open an Issue first to discuss the approach:

- Rigging tools
- Mesh editing/splitting
- AI animation improvements
- Curve editor
- Cloud features

## Code Style

- The studio is a single HTML file — keep it that way for now
- Use `const`/`let`, never `var`
- Functions that need to be called from HTML use `window.functionName = function(){}`
- Keep CSS variables in `:root` for theming
- Three.js imports use import maps from CDN

## Testing

Open `index.html` in Chrome and test:

1. Import a GLB model
2. Click bones, move them
3. Add keyframes, play timeline
4. Export GLB and JSON
5. Import JSON back
6. Undo/redo
7. Check highlight/chain/bones toggles

If all of that works, you're good.

## Reporting Bugs

Open an Issue with:

- What you expected to happen
- What actually happened
- Browser + OS
- Screenshot if possible
- Console errors (F12 → Console tab)

## Community

- Be respectful
- Be constructive
- Help others learn

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
