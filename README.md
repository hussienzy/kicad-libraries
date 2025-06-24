# 🧰 KiCad Custom Libraries

This repository contains a collection of custom and third-party KiCad libraries organized for easy reuse in PCB design projects. It includes **symbols**, **footprints**, and **3D models**, including curated content from SparkFun and other sources.

---

## 📁 Folder Structure

kicad-libraries/
├── symbols/ # KiCad symbol libraries (.kicad_sym)
├── footprints/ # KiCad footprint libraries (.pretty)
├── 3dmodels/ # STEP/WRL files for 3D model rendering
└── README.md # This documentation file


---

## 📦 Included Libraries

| Library Name               | Type        | Source       | Notes                          |
|----------------------------|-------------|--------------|--------------------------------|
| `my_symbols.kicad_sym`     | Symbols     | Custom       | Personal symbols for ICs, headers, etc. |
| `my_footprints.pretty/`    | Footprints  | Custom       | Common SMD, THT footprints     |
| `SparkFun-Footprints.pretty/` | Footprints  | SparkFun     | Imported from SparkFun repo    |
| `SparkFun-Symbols.kicad_sym` | Symbols     | SparkFun     | Popular sensors, connectors    |
| `3dmodels/`                | 3D Models   | Mixed        | Custom and vendor STEP files   |

---

## 🛠 How to Use in KiCad

### 🔗 Add Symbol Libraries
1. Open KiCad > Preferences > Manage Symbol Libraries
2. Click **Add existing library to table**
3. Browse to `symbols/` folder and add `.kicad_sym` files

### 🔗 Add Footprint Libraries
1. Go to Preferences > Manage Footprint Libraries
2. Click **Add existing library to table**
3. Select `.pretty` folder inside `footprints/`

### 🌐 Optional: Add Environment Variables
You can define `${MY_LIBS}` to point to this repo folder and use it in projects for portability.

---


🤝 Contributing
If you'd like to contribute:

Keep footprints in .pretty/ format

Use proper naming conventions

Submit a pull request with a clear description

📜 License
Unless otherwise stated, custom libraries in this repository are shared under the MIT License. Third-party libraries (e.g., SparkFun) retain their original licenses.

🙌 Credits
Custom libraries by Hussien

SparkFun libraries by SparkFun Electronics


---

### 💡 To Use It:
1. Save the content as `README.md` in your root `kicad-libraries/` folder.
2. Push it to GitHub:
```bash
git add README.md
git commit -m "Added README documentation"
git push
