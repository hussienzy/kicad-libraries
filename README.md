# 🧰 KiCad Custom Libraries ![KiCad](https://img.shields.io/badge/Made%20with-KiCad-blue?logo=kicad) ![License](https://img.shields.io/badge/license-MIT-green)

This repository contains a collection of **custom and third-party KiCad libraries** organized for easy reuse in PCB design projects. It includes **symbols**, **footprints**, and **3D models**, including curated content from SparkFun and other sources.

---

## 📁 Folder Structure
kicad-libraries/
├── Symbols/ # KiCad symbol libraries (.kicad_sym)
├── Footprints/ # KiCad footprint libraries (.pretty)
├── 3DModels/ # STEP/WRL files for 3D model rendering
└── README.md # Project documentation

---

## 📦 Included Libraries

| Library File                          | Type       | Source   | Description                                   |
|---------------------------------------|------------|----------|-----------------------------------------------|
| ABX00027.kicad_sym                    | Symbol     | Custom   | Symbol for Arduino Nano 33 IoT                |
| MODULE_ABX00027.kicad_mod             | Footprint  | Custom   | Footprint matching Nano 33 IoT module         |
| ABX00027.step                         | 3D Model   | Custom   | High-detail STEP model for Nano 33 IoT board  |
| *(More coming soon...)*              | -          | -        | -                                             |

---

## 🧪 How to Use These Libraries

1. **Clone this repo** or click **Code → Download ZIP**  
2. Open **KiCad** and go to:
   - `Preferences > Manage Symbol Libraries`
   - `Preferences > Manage Footprint Libraries`
3. **Add the symbol and footprint libraries** from their respective folders
4. **Assign 3D models** in the footprint properties (use relative paths if possible)

---

## 📷 Library Usage Preview in KiCad

> _Below is an example screenshot showing the Arduino Nano 33 IoT symbol and footprint used in a schematic and PCB layout._

![KiCad Preview](docs/nano33iot-example.png)

*(Replace with your actual image file)*

---

## 🤝 Contributing

If you'd like to contribute:
- Follow KiCad naming conventions
- Use `.pretty` folders for footprints
- Use `.kicad_sym` for symbols
- Submit a pull request with a description

---

## 📜 License

All custom libraries in this repository are shared under the **MIT License**.  
Third-party libraries retain their original licenses (e.g., SparkFun content).

---

## 🙌 Credits

- Maintained by [Hussien](https://github.com/hussienzy)
- Based on components and footprints built in-house or curated from trusted sources
