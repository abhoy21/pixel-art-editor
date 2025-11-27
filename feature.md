## Pixel Studio Feature Proposals

- **Guided onboarding tour**  
  Short overlay that highlights the layer panel, tools dock, color palette and export controls the first time someone lands (persist dismissal with `localStorage`).

- **Template & preset gallery**  
  Curated collection of starting canvases (emoji pack, RPG sprites, UI icons). Users can preview a preset, click “Use template” and it loads directly into the current session without needing server storage.

- **Palette manager & history stack**  
  Side drawer that shows the active palette, recently sampled colors, and lets the user create/save named palettes in the browser. Expose import/export via `.json` download/upload for easy sharing.

- **Smart symmetries**  
  Toggleable horizontal/vertical/quad symmetry modes that mirror strokes across axes, ideal for icons or characters. Mirror logic stays entirely on the client.

- **Reference image overlay**  
  Allow dropping or uploading an image that appears ghosted behind the canvas with opacity slider; the file is held in memory only and discarded on refresh.

- **Animation preview (onion skin)**  
  Frame strip UI where each frame is a separate layer stack snapshot. Provide onion-skin toggle to show previous/next frame translucently to support sprite animation without persisting data remotely.

- **Snap-to-grid export settings**  
  New export dialog that supports transparent background, upscale factor selection, and downloading as PNG or GIF—all composed client-side.

- **Keyboard shortcuts panel**  
  Floating `?` button that reveals shortcuts (e.g., `B` pencil, `E` eraser, `[` / `]` zoom) with the option to customize and store bindings locally.

- **Session autosave & restore**  
  Periodically serialize the full project (layers, settings) into `localStorage`. On returning, prompt “Restore last session?” so progress isn’t lost without any backend involvement.

- **Shareable preview mode**  
  “Presentation” view that hides UI chrome and renders artwork centered on a neutral background. Include one-click copy-to-clipboard (SVG/PNG data URL) for quickly sharing results in chats.

