# The Everyday Dock — Interactive 3D Concept

A browser-based Three.js concept model for a modular pram accessory featuring:

- universal flexible silicone strap
- circular magnetic phone dock
- one-handed release tab
- discreet side-mounted solar panel
- daylight trickle-charging animation
- exploded component view
- orbit, zoom and pan controls

## Run locally

```bash
npm install
npm run dev
```

Open the local URL shown by Vite.

## Build for deployment

```bash
npm run build
```

The production site will be created in `dist/`.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. Run `npm run build`.
3. Deploy the generated `dist` folder through GitHub Pages, or connect the repository to Vercel/Netlify.

For a repository hosted at `https://username.github.io/repository-name/`, add the following to `vite.config.js`:

```js
import { defineConfig } from "vite";

export default defineConfig({
  base: "/repository-name/"
});
```

## Where to reshape the design

Open `src/main.js`.

Useful sections:

- `FLEX STRAP` — changes strap shape, thickness and buckle.
- `MAIN MAGNETIC DOCK` — changes the round dock, ring and release tab.
- `PHONE` — changes device proportions and screen.
- `DISCREET SIDE SOLAR PANEL` — changes panel height, width, cells and side position.
- `COLORS` — changes charcoal, gold, silicone and solar finishes.

All geometry is procedural, so no `.glb`, `.obj` or texture files are required.

## Concept limitation

This is a visual product concept, not an engineering-ready CAD file. Before prototyping, the solar output, battery system, magnets, thermal management, ingress protection and wireless-charging compliance should be reviewed by qualified electrical and product engineers.
