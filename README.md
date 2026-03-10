# Matplotlib Visualization Gallery 📊

A diverse collection of Python scripts demonstrating the expansive plotting capabilities of the **Matplotlib** library. This repository serves as a practical cookbook for creating a wide variety of static, animated, and interactive visualizations in Python.

## 🚀 Plot Types Included

The repository contains numerous individual scripts, each dedicated to showcasing a specific type of plot or customization technique.

### 1. Fundamental Plots
Basic visualizations for everyday data analysis:
- **Line Plots:** `lineplot.py`, `mat.py`
- **Bar Plots:** `barplot.py`, `mat.py`
- **Scatter Plots:** `scatter.py`, `mat.py`
- **Histograms:** `histogram.py`, `mat.py`
- **Pie Charts:** `pie.py`, `mat.py`
- **Area/Stack Plots:** `area.py`, `stack.py`

### 2. Statistical & Categorical Plots
Visualizing data distributions and statistical summaries:
- **Box Plots:** `box.py`, `mat.py`
- **Violin Plots:** `violin.py`
- **Error Bars:** `errorbar.py`
- **Stem Plots:** `stem.py`
- **Step Plots:** `step.py`

### 3. Advanced & Specialty Plots
Exploring multidimensional and specialized data representations:
- **3D Plotting:** `3d.py` (surface/scatter), `3dwireframe.py` (wireframes)
- **Heatmaps & Hexbins:** `heatmap.py`, `hexbin.py`
- **Contour Plots:** `contour.py`
- **Vector Fields:** `quiver.py`
- **Polar & Radar Charts:** `polar.py`, `radar.py`
- **Time Series / Signal Processing:** `Autocorrelation.py`, `lag.py`, `event.py`
- **Specialized Analytics:** `andrews.py` (Andrews Curves)

### 4. Comprehensive Layout Demonstration
- **`mat.py`**: A master script demonstrating how to combine multiple facets of Matplotlib. It covers basic plotting, styling (colors, markers, line styles), creating complex subplots (`plt.subplots`), and saving figures directly to disk as PNG files.

## 🛠 Prerequisites

To run these scripts, you need Python installed, along with the `matplotlib` and `numpy` (often used to generate the sample data) libraries.

```bash
pip install matplotlib numpy
```

## 📝 Running the Scripts

Execute any of the `.py` files in your terminal to render the specific plot in a new window:

```bash
python scatter.py
```
*(Note: Running `mat.py` will systematically generate and display multiple plots while sequentially saving them as PNG image files in the current directory).*