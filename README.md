# Body Journey 3D – anatomy models (modified)

3D anatomy models used by the Android app **Viaggio nel Corpo 3D / Body Journey 3D / Viaje al Cuerpo 3D** (Store Play Studio).
13 layers (skin, skeleton, muscles, arteries, veins, nerves, heart, respiratory, digestive, urinary, reproductive, endocrine, senses),
3,352 parts, glTF binary (.glb) compressed with meshoptimizer (EXT_meshopt_compression). `models/normale` ≈ 1.4 M triangles,
`models/alta` ≈ 4.8 M triangles. Y up, metres, feet at y = 0. Node/mesh name = part id (`FJxxxx` = BodyParts3D, `ZAxxxx` = Z-Anatomy);
`data/parts.json` maps each id to its FMA/TA id, English name, layer, side and group.

## Changes made
Converted to glTF, re-oriented and scaled, grouped into layers, simplified (meshoptimizer), Z-Anatomy parts aligned to BodyParts3D
(rigid + local fit + smooth warp) and merged, duplicates removed.

## Sources and licences
- **BodyParts3D**, © The Database Center for Life Science, licensed under CC Attribution-Share Alike 2.1 Japan
  (http://dbarchive.biosciencedbc.jp/en/bodyparts3d/lic.html).
- **Z-Anatomy – The libre 3D atlas of anatomy**, CC BY-SA 4.0 (https://github.com/Z-Anatomy/Models-of-human-anatomy), which itself credits
  "Cranial Nerves and Foramina – University of Dundee, CAHID – CC BY 4.0" among its references.
- Anatomical names: Terminologia Anatomica (TA2), via Z-Anatomy.

These modified models are released under **CC BY-SA 4.0** (see LICENSE). Attribution: "Body Journey 3D anatomy models, Store Play Studio,
derived from BodyParts3D (DBCLS, CC BY-SA 2.1 JP) and Z-Anatomy (CC BY-SA 4.0)".
