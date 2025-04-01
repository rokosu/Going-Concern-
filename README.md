# Going-Concern-
This study examines the impact of the uncertainty of the going concern on the quality of the financial statements and compares the perspectives of management and auditors. Based on theories of agency, signaling, and stakeholders, the research examines how corporate governance, materiality, and financial distress indicators 
```markdown
# Impact of Going Concern Uncertainties on Financial Statement Quality

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

This repository contains code, data, and visualizations for the research paper:  
**"The Impact of Going Concern Uncertainties on Financial Statement Quality: A Comparative Analysis of Management's and Auditors' Perspectives"**  
*Accepted for publication in [Journal Name]*.

---

## 📜 Study Overview  
This study investigates how management and auditors respond to going concern uncertainties and their impact on financial statement quality. Using **panel data analysis**, **instrumental variable (IV) regression**, **generalized method of moments (GMM) estimation**, and **Python-based visualizations**, we test five hypotheses (H1–H5) grounded in agency theory, signaling theory, and stakeholder theory.

### Key Contributions:
1. Quantifies management’s systematic understatement of risks (H1) and auditors’ conservative bias (H4).
2. Identifies governance mechanisms (e.g., audit committee independence) that enhance disclosure quality (H2).
3. Proposes reforms for materiality standardization (H3) and dynamic risk modeling (H5).

---

## 📂 Repository Structure  
```
Going-Concern-Financial-Statement-Quality-Analysis  
│  
├── data/  
│   ├── financial_data.csv          # Financial metrics (ROA, leverage, disclosures)  
│   ├── survey_responses.csv        # Management/auditor perception data  
│   └── governance_metrics.csv      # Board independence, CEO duality  
│  
├── scripts/  
│   ├── 01_data_preprocessing.py   # Data cleaning and imputation  
│   ├── 02_panel_analysis.py       # Fixed/Random effects models (Table 2)  
│   ├── 03_iv_gmm_estimation.py    # IV and GMM regression (Tables 3–4)  
│   └── 04_visualization.py        # Generates Figures 1–5  
│  
├── results/  
│   ├── tables/                     # Exported regression results (LaTeX/CSV)  
│   └── figures/                    # Visualization outputs (PNG/PDF)  
│  
├── README.md                       # This file  
└── requirements.txt                # Python dependencies  
```

---

## ⚙️ Installation  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/rokosu/Going-Concern.git
   cd Going-Concern
   ```

2. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage  
### Replicate the Analysis:  
1. **Preprocess data**:  
   ```bash
   python scripts/01_data_preprocessing.py
   ```

2. **Run panel data analysis**:  
   ```bash
   python scripts/02_panel_analysis.py
   ```

3. **Estimate IV/GMM models**:  
   ```bash
   python scripts/03_iv_gmm_estimation.py
   ```

4. **Generate visualizations**:  
   ```bash
   python scripts/04_visualization.py
   ```

### Outputs:  
- **Tables**: Regression results in `results/tables/`  
- **Figures**: Visualizations in `results/figures/`  
  - `perception_gap.png` (H4)  
  - `governance_trends.png` (H2)  
  - `scatter_h1.png` (H1)  
  - `boxplot_h3.png` (H3)  
  - `heatmap_h5.png` (H5)  

---

## 📊 Results Preview  
### Figure 1: Perception Gap (H4)  
![Perception Gap](results/figures/perception_gap.png)  
*Management vs. auditors’ severity ratings (t = 4.25, p < 0.01).*

### Figure 2: Governance Trends (H2)  
![Governance Trends](results/figures/governance_trends.png)  
*Improvement in governance quality driven by audit committee independence.*

---

## 🤝 Contributing  
Contributions are welcome! To improve this project:  
1. Fork the repository.  
2. Create a branch: `git checkout -b feature/your-idea`.  
3. Commit changes: `git commit -m 'Add your feature'`.  
4. Push to the branch: `git push origin feature/your-idea`.  
5. Submit a **pull request**.

---

## 📄 License  
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 📧 Contact  
For questions or collaborations:  
- **Author**: Rokosu  
- **Email**: rokosu@live.com  
- **GitHub**: [@rokosu](https://github.com/rokosu)  

---

**Keywords**: Going concern uncertainties, financial statement quality, corporate governance, materiality, agency theory.  
``` 

---

This README provides a comprehensive guide to replicating the study and understanding its contributions. Customize the `DOI`, contact details, and license as needed.
