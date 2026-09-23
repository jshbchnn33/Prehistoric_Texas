# Acrocanthosaurus Reference Assets

This directory contains the canonical visual references for **Acrocanthosaurus atokensis** used across the Prehistoric Texas project.

These files are intended to support consistent image and video generation across multiple Acrocanthosaurus videos. They should be treated as shared production references rather than assets belonging to any one individual video.

## Files

### `acro_character_sheet_reference.png`

**Purpose:** Primary canonical character reference.

Use this image to preserve:
- skull shape and proportions
- body proportions
- dorsal ridge / elongated neural spine appearance
- forelimb structure
- hind limb build
- tail proportions
- coloration and patterning
- skin texture
- overall realistic anatomy

When visual references conflict, this file should take priority for the appearance of Acrocanthosaurus.

---

### `acro_environment_plate_reference.png`

**Purpose:** Clean environmental reference for the recurring Early Cretaceous Texas riverbank / floodplain setting.

Use this image to preserve:
- overall landscape character
- vegetation style
- river and floodplain appearance
- conifer distribution
- ground cover
- sky and atmospheric look
- natural daylight
- general color palette

Individual scenes may add denser ferns, cycads, bushes, or other foreground vegetation when required by the shot.

---

### `acro_environment_with_acro_reference.png`

**Purpose:** Combined look-development reference showing Acrocanthosaurus integrated into the standard environment.

Use this image to guide:
- apparent scale of the animal within the landscape
- lighting interaction on the animal
- overall photorealistic rendering style
- visual integration between animal and environment
- camera-height and documentary-style presentation

This image is a secondary reference. The character sheet remains authoritative for anatomy and proportions, while the clean environment plate remains authoritative for the base landscape.

---

## Reference Priority

For image generation involving Acrocanthosaurus, use the references in this order:

1. **`acro_character_sheet_reference.png`** — anatomy, proportions, coloration, and character identity
2. **`acro_environment_plate_reference.png`** — environment, lighting, and landscape identity
3. **`acro_environment_with_acro_reference.png`** — integration, scale, and overall visual style

## Production Rule

Do not modify these reference files simply to match a single video shot.

Shot-specific start frames, end frames, intermediate images, and Kling renders should be stored inside the relevant individual video directory.

Example:

```text
Acrocanthosaurus/
├── references/
│   ├── README.md
│   ├── acro_character_sheet_reference.png
│   ├── acro_environment_plate_reference.png
│   └── acro_environment_with_acro_reference.png
│
└── Hunting_Sauropods/
    ├── production.md
    └── frames/
        ├── scene_01_start.png
        ├── scene_01_end.png
        └── ...
```

## Continuity Principle

The purpose of this directory is to give every future Acrocanthosaurus production the same visual foundation. New canonical references should only be added when they represent a deliberate project-wide change or expansion to the approved Acrocanthosaurus design.
