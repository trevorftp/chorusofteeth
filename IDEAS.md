# Ideas & Roadmap

Brain dump. Unfiltered. Some of this will happen, some won't. The engine tells us what it wants.

---

## Near-term (the bones)

- [ ] **HUD crosshair** — simple dot or custom reticle, toggleable
- [ ] **Interaction prompt** — "Press E" appears when looking at a usable entity
- [ ] **Sound effects** — door open/close, footsteps, ambient drones
- [ ] **Ambient sound entities** — place looping sounds in the map (dripping, humming, breathing)
- [ ] **Music system** — layered tracks that shift based on danger/area
- [ ] **Elevators / lifts** — func_plat, vertical func_door
- [ ] **Buttons / switches** — func_button that activates targets on press
- [ ] **Key & lock system** — colored keys unlock matching doors

## Visual (the skin)

- [ ] **Post-processing pass** — chromatic aberration, film grain, vignette
- [ ] **Decal system** — blood splatters, scratches, scorch marks on walls
- [ ] **Sprite entities** — billboard sprites for items, decorations, enemies
- [ ] **Sprite animation** — frame-based with directional facing (8-angle)
- [ ] **Particle system** — dust, sparks, flies, dripping water, fog wisps
- [ ] **Dynamic shadows** — shadow volumes or shadow maps from point lights
- [ ] **Light flicker patterns** — Quake-style configurable flicker strings
- [ ] **Skybox / sky entity** — scrolling void texture or solid color sky

## Gameplay (the meat)

- [ ] **Weapon system** — viewmodel rendering
- [ ] **Inventory** — keys, items, notes, limited slots
- [ ] **Health system** — damage, healing items, death state
- [ ] **Enemy AI** — pathfinding, patrol, chase, attack states
- [ ] **Nav mesh or waypoint system** — AI navigation through map geometry
- [ ] **Pickup entities** — health, ammo, keys, notes
- [ ] **Note / readable system** — examine items that show text (found notes, scrawled warnings)
- [ ] **Save / load** — serialize player state + world state to file
- [ ] **Checkpoints** — auto-save at certain trigger volumes
- [ ] **Death / restart** — respawn at last checkpoint or map start

## Audio (the voice)

- [ ] **Positional audio** — 3D falloff, stereo panning (partially done)
- [ ] **Room reverb** — reverb amount based on room volume / surface area
- [ ] **Audio occlusion** — sounds muffled by walls between player and source
- [ ] **Footstep materials** — different sounds for stone, metal, wood, water
- [ ] **Ambient zones** — trigger volumes that change ambient sound/music

## World (the architecture)

- [ ] **Moving platforms** — func_train, path entities for patrol routes
- [ ] **Water volumes** — func_water with surface rendering, swimming movement
- [ ] **Breakable brushes** — func_breakable that shatters into debris
- [ ] **Ladders** — func_ladder or textured surface climb
- [ ] **Rotating entities** — func_rotating for fans, gears, spinning things
- [ ] **Map transitions** — trigger_changelevel to load a new .map
- [ ] **Multiple maps** — hub system or linear progression

## Engine (the guts)

- [ ] **Console / dev terminal** — in-game command input for debugging
- [ ] **Config file** — keybinds, graphics settings, mouse sensitivity
- [ ] **Resolution options** — render at lower resolution, upscale (retro crisp)
- [ ] **Fullscreen toggle** — borderless / exclusive fullscreen
- [ ] **Map hot reload** — detect .map file changes and reload without restart
- [ ] **Performance stats** — draw call count, triangle count, frame time graph
- [ ] **Entity scripting** — simple scripting for map events (trigger chains, delays, sequences)

## Random potentials?

- [ ] **Sanity / paranoia system** — visual distortion, audio hallucinations based on exposure
- [ ] **Procedural disturbances** — lights flicker when something is near, doors creak open on their own
- [ ] **Text corruption** — HUD messages that glitch, stutter, or say things the trigger didn't specify
- [ ] **Unreliable narrator** — the engine lies to you sometimes. save files that change. maps that shift.
- [ ] **Teeth** — there should always be more teeth than you expect

---

*this document is alive. it grows teeth.*
