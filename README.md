# Dance Coach

Prototype of a camera coach that teaches dance moves. A reference dancer shows an 8-count move; your camera tracks your body and scores how closely each limb matches.

- Single static page (`index.html`), no build step.
- Pose tracking runs in the browser with MediaPipe Pose Landmarker; video never leaves the device.
- The camera needs https or localhost: deploy on Vercel, or run `npx serve` locally.
