Be sure to update this log with
1. Who you are
2. What your prompt was
3. What you changed
This is the initial prompt:

Let's write a boids simulation using webgl as a single page in html, css, and JavaScript.

Let's use a dark theme, and let's take an optional URL parameter "hue" that we use to generate a color scheme. I want the page to be able to take any number of optional "header" and "subheader" parameters for displaying as text on the canvas. I want the canvas to be the full screen, with all controls and stats behind toggle-able overlays.  I want lots of slick animations, and I want the action to begin as soon as the page loads. I also want it to work well on mobile. I want it to display the frame rate.

I want all configuration to be available as optional URL parameters. If a configuration value is set in the URL, it should be updated in the URL when it changes on the page. 

I want an optional URL parameter "debug".  When debug is set, the URL should be updated to show all the configuration values as they change. Debug should also enable additional console logging.

---

### Update by Codex
- **Prompt:** "Let's add controls for selecting the number of types of boids, each with their own characteristics. Let's have global modifiers that affect all boids"
- Added a new `Boid Types` control and configuration parameter.
- Boids now store a type index with per-type speed factors and color offsets.
- WebGL shaders and buffers updated to handle type-based attributes.

