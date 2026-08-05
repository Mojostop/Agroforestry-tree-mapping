# Agroforestry-tree-mapping
2D/3D spatial visualization and solar shading analysis of a agroforestry plot 

## Features
- **2D map** (`src/viz_2d.py`): tree positions, DAP-scaled crown circles,
  species coloring, thinning candidates highlighted.
- **3D model** (`src/viz_3d.py`): interactive Plotly scene with tree trunks/crowns,
  plantation guide lines, and sun path for winter/summer solstices using `pysolar`.

## Data
`data/python_leucenas.csv` — semicolon-separated tree inventory with columns:
`Plant, Specie, X, Y, CBH, DBH, Height`

## Setup
```bash
pip install -r requirements.txt
python src/viz_2d.py
python src/viz_3d.py
