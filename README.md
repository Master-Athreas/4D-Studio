# 4D Studio

A free, browser-based 3D animation studio. No installs, no subscriptions, no bloat — the entire studio is a single 64KB HTML file.

Built with [Three.js](https://threejs.org/).

## Features

**Scene Management** — Import GLB/GLTF models via drag & drop. Import AI-generated animation JSON. Export as GLB or JSON. Multi-model support.

**Posing & Animation** — Click bones in viewport or tree. Transform gizmo (Move/Rotate/Scale). Full keyframe timeline with draggable diamonds. Load existing clips for editing. Save new animations as clips. Channel locking to protect finished work.

**Visualization** — Outline highlighting on hover. Chain mode showing connected bone hierarchy. Skeleton visualization with bone dots. Hover labels with part names.

**Editing** — Undo/Redo (50 levels). Right-click rename. Snap mode. Collapsible panels. Resizable timeline.

## Getting Started

1. Download `index.html`
2. Open it in Chrome, Firefox, or Edge
3. Drag a `.glb` file onto the viewport
4. Click bones, press W/R/S to transform, K to keyframe, Space to play

No build step. No npm. No server. Just open the file.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| W / G | Move mode |
| R | Rotate mode |
| S | Scale mode |
| F | Focus camera |
| K | Add keyframe |
| Space | Play / Pause |
| H | Toggle highlight |
| C | Toggle chain mode |
| Del | Delete object |
| Ctrl+Z | Undo |
| Ctrl+Shift+Z | Redo |

## AI Animation (WIP)

Export bone data → describe the animation you want → AI generates keyframe JSON → import it as a playable clip. Work in progress.

## Why?

Blender is a 2GB download with millions of lines of code. Most devs use 5% of it. 4D Studio does what you actually need in 64KB.

## Roadmap

- [ ] Improved AI animation generation
- [ ] Rigging tool (add bones to unrigged models)
- [ ] Mesh splitting (jaw animation, etc.)
- [ ] Curve editor (ease in/out)
- [ ] Onion skinning
- [ ] Cloud sync & collaboration
- [ ] Animation marketplace

## Contributing

Contributions are welcome via Pull Requests. See [CONTRIBUTING.md](CONTRIBUTING.md).

By submitting a PR, you agree to the terms in [LICENSE](LICENSE).

## License

4D Studio is **source-available** — free to use, not free to redistribute or clone. See [LICENSE](LICENSE) for full terms.

**You CAN:** Use it, learn from the code, contribute, create content with it (your animations/exports are yours).

**You CANNOT:** Redistribute it, fork it into a competing product, remove the branding, or host it as a service.