# Project style bible mode

Use this reference when the user asks for a project visual bible, art-direction guide, image-generation specification, series consistency system, reusable production standard, or a full upgrade from isolated style prompts.

## Contents

1. Scope and locks
2. Short style identity
3. Project identity
4. Color system
5. Lighting system
6. Space design system
7. Composition and lens system
8. Material bible
9. Character, background, and coexistence
10. Effects physics
11. Motion and temporal system
12. Conditional scene-family templates
13. Prompt architecture
14. Acceptance and calibration

## 1. Scope and locks

State what the bible governs and what it does not govern. Separate:

- medium: illustration, animation, live action, stylized CG, hybrid, or photographic AI imagery
- deliverables: concept images, clean plates, character sheets, keyframes, moving shots, or final frames
- confirmed production locks: aspect ratio, resolution, continuity, compositing, platform, or model constraints
- unknowns and pending decisions

Do not silently invent production specifications. If the user has not locked them, omit them or label them proposed.

## 2. Short style identity

Write one operational paragraph that explains the relationship among form, color, light, material, space, and motion. Genre words may summarize but must not carry the definition.

Then give three to seven project invariants. Each invariant must be:

- visible in the output
- reusable across substantially different scenes
- testable by another team member
- independent of a named character, prop, or location

## 3. Project identity

Define the visual rules whose loss would make the result feel like another project. Cover only supported dimensions such as:

- dominant scale relationship
- realism or abstraction level
- relationship between subject and environment
- material credibility
- density versus restraint
- contrast and saturation philosophy
- how extraordinary elements coexist with ordinary physics

For each identity rule, state its allowed variation. Avoid demanding identical color or brightness in every scene.

## 4. Color system

Build a functional palette rather than a list of attractive colors.

Define when supported:

- environment or field colors
- local and material colors
- complexion or character colors
- accent and narrative focal colors
- highlight, shadow, and black behavior
- saturation hierarchy
- warm/cool relationships
- bright, dark, interior, exterior, weather, or emotional variants
- colors that must remain distinct from one another
- common failure modes

Use exact ratios or swatches only when measured, supplied, or intentionally proposed for team communication. Say whether a number is observed, derived, or proposed.

## 5. Lighting system

Turn lighting into motivated spatial logic. For every recurring lighting family, answer:

1. What is the primary source?
2. Where is it relative to the subject and camera?
3. Is it hard, soft, broad, narrow, direct, bounced, or diffused?
4. What receives the brightest exposure?
5. Where do shadows fall and how much detail remains?
6. Which practical or environmental sources justify warm or colored light?
7. How does atmosphere reveal or suppress the beam?
8. Where can a subject plausibly stand or move?
9. How should the subject share direction, temperature, softness, and contrast with the background?
10. What changes in different time, weather, interior, exterior, or narrative conditions?

Separate the stable lighting philosophy from conditional setups. Never combine incompatible presets into one universal block. State exceptions such as environments where no warm practical is justified.

Describe highlight protection, black level, shadow readability, contrast, roll-off, and environmental reflections. Avoid empty phrases such as “cinematic lighting.”

## 6. Space design system

Analyze space as a place that supports narrative, staging, and image generation—not only as a flat composition.

Define when relevant:

- foreground, middle-ground, and background responsibilities
- scale references and relative size hierarchy
- open, enclosed, compressed, vertical, horizontal, or layered spatial tendencies
- perspective and depth compression or expansion
- occlusion, concealment, path curvature, and reveal rhythm
- visual entrances, exits, travel routes, and action zones
- how architecture or props connect rather than float independently
- atmosphere and detail density by depth
- negative space and breathing room
- clean-plate and compositing usability

Do not require three explicit depth layers for every close-up or deliberately flat style. Treat depth structure as conditional on shot function and medium.

## 7. Composition and lens system

Define a project grammar rather than one fixed framing recipe:

- dominant and exceptional shot sizes
- camera height, tilt, roll, and horizon behavior
- wide, normal, telephoto, macro, or mixed focal tendency
- perspective expansion or compression
- symmetry, asymmetry, centrality, and off-center balance
- foreground obstruction and frame-within-frame use
- negative space and off-screen space
- subject scale and focal placement
- leading lines and directional energy
- depth of field and focus behavior

Phrase focal length as a tendency unless verified or deliberately specified as production guidance. Keep aspect ratio as a production lock, not a universal style fact.

## 8. Material bible

Create entries for recurring material families rather than naming every object. For each important material, define:

- base hue and variation
- macro shape and micro texture
- roughness, gloss, reflectance, translucency, or subsurface behavior
- edge wear, scratches, dents, stains, patina, repair, and age
- wet, dry, dusty, oily, polished, or weathered condition
- response to key light, grazing light, backlight, and colored effects
- scale-dependent detail for wide, medium, and close views
- distinction from nearby materials
- prohibited AI substitutions such as plastic, mirror metal, generic stone, or synthetic fabric

Separate material design from color grading. A surface remains physically credible under different lighting variants.

## 9. Character, background, and coexistence

Keep three linked systems:

### Character

Define silhouette, proportion, anatomy or shape abstraction, face construction, identity variation, hair, costume structure, local color, material, texture, and conditional age or role differences.

### Background

Define geometry, large shape grouping, perspective, depth, edge softness, detail density, palette, lighting, atmosphere, material, and environmental motion.

### Coexistence and compositing

Define relative sharpness, detail, edge contrast, value, saturation, grain or texture, overlap, shared light direction, shared color temperature, contact shadow, scale, and depth cues.

For clean plates or later compositing, also define:

- usable subject zone
- stable and motivated light zone
- unobstructed action or face area
- contact surface and shadow logic
- foreground elements reserved for final integration
- whether a clean plate and integrated reference frame are both needed

## 10. Effects physics

Use this module only when the visual world contains magic, energy, holograms, supernatural light, stylized particles, environmental anomalies, or other active effects.

For every effects family, define:

1. source
2. physical or graphical attachment
3. propagation path
4. intensity hierarchy
5. color and spectral character
6. falloff and dissipation
7. illumination or deformation of nearby surfaces
8. interaction with fog, water, dust, skin, fabric, or metal
9. temporal onset, growth, pulse, travel, decay, and residue
10. coverage limit or restraint principle

Avoid detached decoration, uniform glow, arbitrary particles, effects without environmental response, or identical behavior across unrelated powers.

## 11. Motion and temporal system

When clips or sequential frames exist, define:

- shot duration and cutting rhythm
- camera movement family
- acceleration, deceleration, drift, correction, and settling
- handheld amplitude and frequency
- subject motion relative to camera
- focus timing and depth changes
- shutter feel and motion smear
- environmental secondary motion
- effects timing
- temporal grain, exposure, and color stability

When only stills exist, label any motion extension as proposed or inferred.

## 12. Conditional scene-family templates

Create templates by visual condition, not by named story location. Include only families supported by the references or requested production needs, such as:

- bright exterior
- overcast or fog exterior
- night exterior
- day interior
- night interior
- high-contrast or silhouette setup
- storm, smoke, dust, rain, or underwater condition
- intimate close-up
- wide establishing view
- high-speed action

Each template should specify only what changes from the stable core: palette, source, exposure, space, material response, motion, and exceptions. Do not repeat the whole global style in every template.

## 13. Prompt architecture

Write prompts in replaceable modules:

1. medium and global style core
2. project identity invariants
3. selected color preset
4. selected lighting preset
5. space, composition, and lens
6. material behavior
7. character or background module
8. coexistence and compositing
9. effects physics
10. motion and temporal behavior
11. production locks
12. scene locks
13. failure-specific negatives

Then provide one merged copy-ready prompt when the user asks for a complete prompt.

## 14. Acceptance and calibration

Build a compact checklist around the systems actually used. Check:

- project identity survives
- conditional preset matches the scene condition
- light is motivated and internally consistent
- color roles remain distinct
- scale, path, and depth are readable
- materials remain physically differentiated
- characters and backgrounds share one visual world
- effects have source, attachment, falloff, and environmental response
- composition supports the requested shot function
- production and scene locks are satisfied
- no prohibited content leaked into a content-free prompt

Do not use a fixed count of failed checks as a universal regeneration threshold. Recommend local repair when the governing system is correct and the failure is isolated. Recommend regeneration when identity, geometry, lighting logic, or several dependent systems are wrong.

When revising, replace the faulty rule and remove superseded instructions. Record whether the change affects the stable core, one conditional family, a production lock, or a scene lock.
