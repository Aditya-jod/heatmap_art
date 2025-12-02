# Art with heatmap and data science
A small project that generates artistic heatmaps from structured data. Use it to explore patterns, create visual art from numeric matrices, or learn how heatmap visualizations are constructed. This repository is intended for entertainment and educational purposes.

## Features
- Convert numerical data into visually appealing heatmaps
- Multiple color palettes and styling options
- Save high-resolution images for prints or sharing

## Requirements
- Python 3.8+
- numpy, pandas, matplotlib, seaborn

## Quick start
1. Install dependencies:
```bash
pip install numpy pandas matplotlib seaborn
```
2. Generate a simple heatmap:
```python
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

data = np.random.randn(100, 100)  # replace with your dataset
plt.figure(figsize=(8, 8))
sns.heatmap(data, cmap="magma", cbar=False)
plt.axis('off')
plt.savefig("heatmap_art.png", dpi=300, bbox_inches='tight', pad_inches=0)
```

## Tips
- Experiment with different colormaps (e.g., "viridis", "magma", "coolwarm")
- Try smoothing or resizing your matrix for different textures
- Combine multiple heatmaps or overlay shapes for mixed-media effects

## License
MIT — feel free to adapt and share with attribution.
This is only for entertainment purper 