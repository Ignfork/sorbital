# Sorbital ($SORE)

The whole site is one file, `index.html`. Upload it to any static host (Netlify, Vercel, GitHub Pages, cPanel). You don't need a build step.

## Settings to edit
These are at the top of the `<script>` in `index.html`:

```js
var CONFIG = {
  xUrl: 'https://x.com/SorbitalSol',
  xHandle: '@SorbitalSol',
  mint: '',      // $SORE mint after launch; a connected wallet's real balance then sets crew bunks
  rpcUrl: 'https://api.mainnet-beta.solana.com'
};
```

The crew ranks are in the `TIERS` list, and the alien stats and pod odds are in `SPECIES`. Edit either one to match your final numbers.

## Features
- **Hero: a full-screen, high-detail megastation, drawn in 3D at your screen's full resolution.** It's built once when the page loads, then animated.
  - **Main disc:** a multi-tier disc city with hundreds of lit buildings that cast shadows, landing pads, a light-ringed trench, glowing tier bands and a tall central spire ringed by towers and comms dishes.
  - **Arms and hangars:** docking arms with moving traffic lights lead out to four large hangar modules with glowing bay doors.
  - **Lighting:** window glow (bloom), blinking beacons and a holo ring above the spire.
  - **Traffic:** ships fly in to dock at the hangars and pass by in the background.
  - **Backdrop:** an alien ocean planet below with clouds, night-side city lights and an atmosphere glow; a sun, nebulae and stars; and parallax when you move the mouse.
- **Modes:** Deep space, Meteors (a meteor shower) or Red alert (red lights and a siren).
- **Sections:** How it works, the crew (six alien rarities with animated cards), the greenhouse (six space crops), $SORE with a holdings calculator and rank table, and a roadmap.
- **Playable base preview:** aliens fly out to the Asteroid Belt, Ice Comet, Plasma Cloud and Crystal Moon, then haul back to the Docking Hall.
  - Collect, open recruit pods, fuse aliens, and grow crops in the greenhouse pods.
  - A Phone/Tablet toggle changes the device frame.
  - A holdings slider sets your crew bunks.
  - Progress is saved on the device, and the crew keeps working while the tab is closed (capped at 12 hours).

Preview credits are not tokens. The site shows no contract address; the launch is posted on X.
