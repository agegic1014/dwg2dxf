| Lineweight (mm) | AutoCAD Color Name      | HEX       | ACI       | Visual Goal       |
| --------------- | ----------------------- | --------- | --------- | ----------------- |
| 0.00            | **Light Gray (ACI 8)**  | #BFBFBF | 8         | Construction only |
| 0.05            | **Dark Gray (ACI 9)**   | #808080 | 9         | Very light        |
| 0.09            | **Cyan (ACI 4)**        | #00FFFF | 4         | Thin              |
| 0.13            | **Yellow (ACI 2)**      | #FFFF00 | 2         | Clear & thin      |
| 0.15            | **Orange***             | #FF9900 | (ACI 30)  | Slightly thicker  |
| 0.18            | **Blue (ACI 5)**        | #0000FF | 5         | Normal thin       |
| 0.20            | **Royal Blue***         | #0033CC | (ACI 170) | Normal            |
| 0.25            | **White/Black (ACI 7)** | #000000 | 7         | Standard          |
| 0.30            | **Green (ACI 3)**       | #00FF00 | 3         | Partitions        |
| 0.35            | **Dark Green***         | #009933 | (ACI 94)  | Medium            |
| 0.40            | **Red-Orange***         | #FF3300 | (ACI 27)  | Medium thick      |
| 0.45            | **Red (ACI 1)**         | #FF0000 | 1         | Strong            |
| 0.50            | **Magenta (ACI 6)**     | #FF00FF | 6         | Structural        |
| 0.53            | **Dark Magenta***       | #990099 | (ACI 200) | Structural +      |
| 0.60            | **Purple***             | #6600CC | (ACI 222) | Heavy             |
| 0.65            | **Deep Purple***        | #4B0082 | (ACI 213) | Heavy +           |
| 0.70            | **Dark Red (ACI 12)**   | #800000 | 12        | Section           |
| 0.80            | **Brown (ACI 33)**      | #663300 | 33        | Section +         |
| 0.90            | **Dark Brown***         | #3D1F00 | 31        | Very heavy        |
| 1.00            | **Navy Blue (ACI 161)** | #000080 | 161       | Border            |
| 1.20            | **Dark Green (ACI 94)** | #003300 | 94        | Max border        |
| 1.40            | **Dark Teal (ACI 162)** | #003333 | 162       | Site border       |
| 1.58            | **Blue-Gray (ACI 163)** | #1A1A2A | 163       | Site border +     |
| 2.00–2.11       | **Black (ACI 7)**       | #000000 | 7         | Maximum           |


JSON file for geminiviewer
{
  "0.00": { "aci": 8,   "color": "#BFBFBF" },
  "0.05": { "aci": 9,   "color": "#808080" },
  "0.09": { "aci": 4,   "color": "#00FFFF" },
  "0.13": { "aci": 2,   "color": "#FFFF00" },
  "0.15": { "aci": 30,  "color": "#FF9900" },
  "0.18": { "aci": 5,   "color": "#0000FF" },
  "0.20": { "aci": 170, "color": "#0033CC" },
  "0.25": { "aci": 7,   "color": "#000000" },
  "0.30": { "aci": 3,   "color": "#00FF00" },
  "0.35": { "aci": 94,  "color": "#009933" },
  "0.40": { "aci": 27,  "color": "#FF3300" },
  "0.45": { "aci": 1,   "color": "#FF0000" },
  "0.50": { "aci": 6,   "color": "#FF00FF" },
  "0.53": { "aci": 200, "color": "#990099" },
  "0.60": { "aci": 222, "color": "#6600CC" },
  "0.65": { "aci": 213, "color": "#4B0082" },
  "0.70": { "aci": 12,  "color": "#800000" },
  "0.80": { "aci": 33,  "color": "#663300" },
  "0.90": { "aci": 31,  "color": "#3D1F00" },
  "1.00": { "aci": 161, "color": "#000080" },
  "1.20": { "aci": 94,  "color": "#003300" },
  "1.40": { "aci": 162, "color": "#003333" },
  "1.58": { "aci": 163, "color": "#1A1A2A" },
  "2.00": { "aci": 7,   "color": "#000000" }
}


Red   → 0.18mm        (1)
Yellow→ 0.25mm        (2)
Green → 0.35mm        (3)
Cyan  → 0.35mm        (4)
Blue  → 0.50mm        (5)
Magenta → 1.00mm      (6)
Black → 1.40mm        (7)
Dark Grey → 0.35mm    (8)
Light Grey → 2.00mm   (9)
Red → 0.18mm          (10)


{
  "0.00-0.15": { "color": "#FFFF99", "px": 1 },
  "0.18":      { "color": "#4FAFFF", "px": 2 },
  "0.20-0.25": { "color": "#005BFF", "px": 3 },
  "0.30-0.35": { "color": "#00CC44", "px": 4 },
  "0.40-0.50": { "color": "#FF4400", "px": 5 },
  "0.53-0.70": { "color": "#FF00FF", "px": 6 },
  "0.80-1.40": { "color": "#660099", "px": 7 },
  "1.58-2.11": { "color": "#000000", "px": 8 }
}
