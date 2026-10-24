---
name: xxd-panel-166
description: "XXD Panel 166｜Sculptural Isometric Bas-relief Diorama: rebuilds the most recognisable subject of a photo as a sculptural isometric miniature — an architectural model, sculpted landscape or bas-relief installation seen from an isometric angle, with slightly flattened masses, stepped terrain, platforms, cut sections and relief layers rising from the surface — in a limited palette of 2–4 colours from the photo over a pale warm-neutral ground, no realistic CG, glossy materials, heavy shadows or game-asset look, set in plenty of whitespace with a few quiet words. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-166 or asks for isometric diorama, bas-relief model or sculptural miniature from a photo."
---

# XXD Panel 166

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

Translate the subject into an isometric sculptural miniature with compressed masses, stepped terrain, platforms, sections and bas-relief levels. Preserve recognisable spatial structure rather than photoreal 3D replication. Use 2–4 source-derived colours, light warm neutral surroundings and generous whitespace. Avoid game-asset styling, complex materials, heavy shadows and excessive gloss.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-166/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-166-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
