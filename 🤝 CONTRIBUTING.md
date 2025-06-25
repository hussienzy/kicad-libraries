# 🤝 Contributing to KiCad Libraries

Thanks for your interest in contributing! Here’s how to help keep the library clean, useful, and consistent.

---

## 📁 Folder Structure

- `Symbols/` — `.kicad_sym` symbol files
- `Footprints/` — `.pretty` folders with `.kicad_mod` files
- `3DModels/` — STEP or WRL files used in 3D views

---

## 📏 Naming Conventions

- Use **UPPERCASE names** with underscores: `MODULE_XYZ.kicad_mod`, `XYZ123.kicad_sym`
- Match the **symbol and footprint names** to datasheets or MPNs
- Name 3D files exactly as the footprint (e.g., `XYZ123.step`)

---

## 🧪 Best Practices

- Test your footprint with a dummy layout before submitting
- Include the 3D model if available
- Make sure pins are correctly mapped
- Run `git pull` before pushing changes
- Write clear commit messages (e.g., "Added ABC123 SMD footprint")

---

## ✅ Submitting Changes

1. Fork this repo (if you're not a direct contributor)
2. Create a new branch (`git checkout -b feature/new-part`)
3. Commit your changes
4. Push to your fork
5. Open a Pull Request (PR) with a description of your changes

---

Thanks for helping improve this repo!
