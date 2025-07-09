# 🧲 Hall Field Structure Analysis – MMS

This repository contains data and code supporting the study:  
**"Magnetospheric Hall Effects at Earth’s Dayside Magnetopause and the Shifted Hall Field Perturbations"**, submitted to *Geophysical Research Letters (GRL)*.

---

## 📦 Contents

- ⚡ **Particle and field data** from the 2015 October 16 MMS reconnection event  
- 📊 **Jupyter notebooks** for Hall field structure analysis, including field and particle visualization  
- 🖼️ **LaTeX code** to generate Figure 1 of the manuscript

---

📁 HallField-MMS-Analysis/
├── Analysis_20151016105454.ipynb   # Jupyter analysis notebook
├── CITATIONH.cff                   # Probably should be renamed to CITATION.cff
├── README.md                       # Nicely formatted, now updated
├── citation.bib                    # BibTeX citation entry
├── diagram1a.tex                   # LaTeX source for Figure 1a
└── diagram1b.tex                   # LaTeX source for Figure 1b

------

## 🗂 Folder Structure

```
HallField-MMS-Analysis/
│
├── data/           # NASA MMS CDF files (Level 2)
├── code/           # Jupyter notebooks for analysis
│                   # LaTeX source code for Figure 1
├── figures/        # Exported figures used in the paper
├── citation.bib    # BibTeX entry for citation
└── CITATION.cff    # GitHub-supported citation metadata
```

---

## 📖 Usage

This repository is best used with:
- Python ≥ 3.8  
- Libraries: `xarray`, `spacepy`, `matplotlib`, `numpy`, `scipy`, `cdflib`, `tqdm`  
- Jupyter Notebook or JupyterLab environment

If using LaTeX for figures, make sure to have `pgfplots`, `tikz`, and `xcolor` installed.

---

## 📑 Citation

If you use this data or code in your own work, please cite the following:

**Budhathoki, D., & Qiu, S. (2025)**. *Hall field structure data and code*. Zenodo. https://doi.org/10.5281/zenodo.15849755

📖 [Download BibTeX citation](citation.bib)

Also available in multiple formats via the **“Cite this repository”** button on GitHub (if enabled).

---

## 🛰 Data Source

Original MMS Level 2 data were obtained from the [MMS Science Data Center (SDC)](https://lasp.colorado.edu/mms/sdc/public/).

All processed data, plots, and derived analysis files in this repo were generated from these publicly available datasets.

---

## 📫 Contact

For questions, please contact:

- **Dipesh Budhathoki** (dipsbc@chd.edu.cn)  
- **Shican Qiu** (scq@ustc.edu.cn)

---

## 📜 License

This project is shared under the **MIT License**. See [`LICENSE`](LICENSE) for details.

---

## 🚀 Acknowledgements

- MMS team for providing high-resolution particle and field measurements  
- AGU and GRL editors and reviewers for their feedback  
- Chang’an University and USTC for supporting this research
