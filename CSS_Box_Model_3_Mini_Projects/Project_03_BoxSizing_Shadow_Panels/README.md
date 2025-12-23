# Panels Studio — box-sizing & box-shadow

## Box Model (super simple)
Every element is a box with 4 layers:
1) **Content** (text/image)
2) **Padding** (space inside the box)
3) **Border** (outline around padding)
4) **Margin** (space outside the box)

### Why box-sizing matters
Default is `content-box` → padding + border increase the final visible size.
`border-box` → padding + border stay inside the width you set.

---

## Goal
Compare default content-box sizing vs border-box, then add box-shadow for depth.

---

## Checklist
- [ ] Used width and/or height
- [ ] Used padding
- [ ] Used border
- [ ] Used margin
- [ ] Tested box-sizing: border-box
- [ ] Used box-shadow
