# Contributing to 4D Studio

Thanks for your interest in contributing!

## How to Contribute

1. **Fork** this repo
2. **Create a branch** (`git checkout -b fix/my-thing`)
3. **Make your changes** — test by opening `index.html` in a browser
4. **Commit** with a clear message
5. **Open a Pull Request**

All PRs are reviewed before merging. Nothing goes in without approval.

## By Submitting a PR

You agree that your contribution becomes part of 4D Studio under the project's license. You retain credit for your work. See [LICENSE](LICENSE) for full terms.

## Good Contributions

- Bug fixes
- UI/UX improvements
- Performance optimizations
- New export formats
- Documentation and tutorials
- AI animation improvements

For large features, open an Issue first to discuss.

## Testing

Open `index.html` in Chrome and verify:
- Import a GLB model
- Click bones, transform them
- Add keyframes, play timeline
- Export and import JSON
- Undo/redo works
- Highlight/chain/bones toggles work

## Reporting Bugs

Open an Issue with: what happened, what you expected, browser + OS, screenshot, console errors.

## Code Style

- Single HTML file for now
- `const`/`let` only
- CSS variables in `:root`
- Three.js from CDN via import maps