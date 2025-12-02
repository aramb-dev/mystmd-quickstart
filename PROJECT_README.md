# MystMD Math Project: A.P. vs G.P.

## Project Structure

```
├── myst.yml                    # Main configuration file
├── data/                       # CSV data files
│   ├── arithmetic_savings.csv # A.P. data (MacBook savings)
│   └── geometric_example.csv  # G.P. data (your scenario)
├── notebooks/                  # Jupyter notebooks for visualization
│   └── [your plotting notebooks]
├── report/                     # Markdown report files
│   ├── 01-arithmetic.md       # A.P. analysis (MacBook savings)
│   └── 02-geometric.md        # G.P. analysis (your scenario)
└── images/                     # Generated plots and figures
```

## Configuration Overview

The `myst.yml` file is configured with:
- Project metadata (title, description, keywords)
- **Table of Contents** in order: Arithmetic → Geometric
- **Export formats**: PDF and DOCX

## Building Your Report

### 1. Build the HTML site:
```bash
myst start
```

### 2. Export to PDF:
```bash
myst build --pdf
```

### 3. Export to DOCX:
```bash
myst build --docx
```

## Next Steps

1. **Complete the G.P. scenario** in `report/02-geometric.md`:
   - Choose a real-life scenario (e.g., bacterial growth, viral sharing, investment)
   - Fill in the values for initial term `a` and common ratio `r`
   - Update the table with calculated values

2. **Create visualization notebooks** in `notebooks/`:
   - Generate linear plot for A.P. → save as `arithmetic_plot.png`
   - Generate exponential plot for G.P. → save as `geometric_plot.png`

3. **Update CSV data** if needed for your specific scenarios

## Tips for PDF/DOCX Export

- The `contents` list in `myst.yml` defines the chapter order
- All files will be combined into a single document
- Cross-references between sections will work seamlessly
- Math equations will render properly in both formats
