# Output contract and verification

Always read this file before drafting. Use only the sections required by the user's request.

## 1. Evidence boundary

State briefly:

- number and type of samples inspected
- materially different conditions covered
- important gaps
- whether the result is provisional, tentative, or strongly supported

Place limitations next to affected claims. Do not lead with a long disclaimer.

## 2. Quick extraction output

Use for a focused request or a small number of references:

1. short style identity
2. stable core
3. important conditional variants
4. excluded scene content when a transferable prompt is requested
5. requested prompt or modules
6. concise confidence note

Do not force the full project-bible structure into a simple request.

## 3. Full transferable-system output

Use when the user asks for a complete style extraction:

### A. Evidence boundary

Report coverage and confidence.

### B. Style identity

Explain the visual system operationally without relying on a title, artist, studio, or genre label.

### C. Style architecture

Separate:

- stable core
- conditional variants
- scene-specific content or locks
- production locks

### D. Rendering and shape system

Cover medium, construction, line, edge, anatomy, shape grouping, and abstraction where relevant.

### E. Color system

Cover functional color roles, value, saturation, complexion, accents, black and highlight behavior, and conditionals.

### F. Lighting system

Cover source, direction, quality, exposure, shadow, motivation, atmosphere, subject landing zone, and conditionals.

### G. Space, composition, and lens system

Cover depth, scale, perspective, occlusion, path, negative space, camera position, focal tendency, and focus behavior.

### H. Material system

Cover important surface families, physical response, aging, material distinction, and failure substitutions.

### I. Character system

Cover silhouette, proportion, face and anatomy construction, identity variation, hair, clothing, local color, material, and texture.

### J. Background system

Cover geometry, shape grouping, depth, detail density, edge behavior, palette, lighting, atmosphere, texture, and environmental motion.

### K. Coexistence and compositing system

Cover relative sharpness, detail, edge contrast, value, saturation, shared light, shared texture, overlap, scale, contact, and usable subject zones.

### L. Effects physics

When relevant, cover source, attachment, propagation, falloff, environmental response, and temporal behavior.

### M. Motion and temporal system

When relevant, cover camera and subject motion, cadence, focus, blur, secondary motion, texture stability, and editing rhythm.

### N. Prompt modules

Provide only requested modules, followed by a merged prompt when requested.

### O. Confidence table

Use only when it improves clarity:

| Rule | Evidence | Layer | Status | Confidence |
|---|---|---|---|---|
| operational rule | sample coverage | core/conditional/scene/production | observed/inferred/proposed/unknown | high/medium/low |

Do not invent numerical confidence scores.

## 4. Project-style-bible output

Use the order in [project-style-bible.md](project-style-bible.md). Include only applicable systems, but always include:

- scope and locks
- short style identity
- project identity
- stable core and conditional variants
- the systems required by the references
- prompt architecture when prompts are requested
- acceptance and calibration method

Keep project-specific scene locks out of universal rules. Put them in a separate appendix or scene module only when the user requests them.

## 5. Prompt modules

Use replaceable blocks:

1. global style core
2. color
3. lighting preset
4. space, composition, and lens
5. material
6. character
7. background
8. coexistence and compositing
9. effects physics
10. video motion
11. production locks
12. scene locks
13. negative constraints

For content-free prompts, start with `【在这里填写人物或场景内容】` and remove identities, objects, settings, actions, plot details, logos, and text from the style modules.

## 6. Conflict check

Before delivery, test:

1. Is a scene rule presented as a global invariant?
2. Is a production recommendation presented as observed fact?
3. Does one conditional lighting preset contradict another inside the same prompt?
4. Does grading overwrite material or production-design color?
5. Does fog or blur destroy subject, scale, or spatial readability?
6. Do character and background use incompatible light direction, temperature, grain, or perspective?
7. Does an effect emit light without affecting nearby surfaces?
8. Does a negative constraint suppress a desired material, motion, or effect?
9. Did concrete content leak into a content-free prompt?
10. Did the prompt add a prohibited field such as aspect ratio, artist name, or story content?
11. Are exact numbers supported, supplied, measured, or clearly labeled proposed?
12. Are observed motion claims based on actual sequential evidence?

## 7. Generation-result calibration

When the user returns with results, report:

- visible mismatch
- owning visual system
- likely ambiguous, missing, or conflicting rule
- replacement rule
- affected layer: stable, conditional, production, or scene
- obsolete instruction to remove

Then provide the revised module and a merged prompt when requested. Do not solve every failure by appending negatives.

## 8. Completion criteria

The deliverable is complete when:

- another person can apply it to new content without seeing the references
- project identity remains recognizable across materially different conditions
- conditionals are explicit rather than mixed into the global core
- characters preserve identity variation
- backgrounds support rather than compete with subjects
- lighting, color, space, materials, effects, and motion form one coherent system
- uncertain facts and proposed production choices are labeled honestly
- prompts are modular and copy-ready
- the acceptance method can identify whether to repair locally or regenerate
