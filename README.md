### ADHD / Dyslexia Accessible Text  

[Bionic‑Style](https://bionic-reading.com/) Emphasis System for Unity (with Dynamic Child‑Object Support)

**Th**is **comp**onent **app**lies **a** **bio**nic‑**rea**ding‑**st**yle **trans**formation **t**o **a**ll **Text**MeshProUGUI **ele**ments **un**der **a** **Game**Object. **I**t **bo**lds **t**he **fi**rst **por**tion **o**f **e**ach **w**ord **us**ing **Text**MeshPro **ric**h‑text **ta**gs **a**nd **auto**matically **up**dates **w**hen **n**ew **ch**ild **obj**ects **a**re **ad**ded **t**o **t**he **hie**rarchy.

---

### Features

- Automatically discovers all nested `TextMeshProUGUI` components
- Applies bold emphasis to the first segment of every word
- Uses safe substring operations to avoid out‑of‑range errors
- Rebuilds text using `StringBuilder`
- Reacts to hierarchy changes through Unity’s built‑in `OnTransformChildrenChanged`
- Supports hierarchy complexity for inactive and nested UI elements 
- Avoids duplicate component references

---

### How to Use

- Place on the parent `GameObject` where `TextMeshProUGUI` child components are (`Canvas` is best).
- That's it. The text will change during runtime and adapts to inactive and newly added `TextMeshProUGUI` child objects.


