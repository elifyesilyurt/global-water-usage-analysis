# Global Water Usage Analysis

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)](https://plotly.com/)
[![FAO Data](https://img.shields.io/badge/Data-FAO%20AQUASTAT-green)](https://www.fao.org/aquastat/en/)
[![Award](https://img.shields.io/badge/W--code%202.0-Selected%20Project-gold)](https://kodluyoruz.org/)
[![License](https://img.shields.io/badge/license-MIT-blue)]()

> Comprehensive data analysis on global freshwater withdrawal patterns across regions and economic sectors, built on official FAO AQUASTAT data.

This project was developed as the graduation capstone for the **W-code 2.0** program — a collaboration between Ford Otosan "Gelecek Hayalim" and Kodluyoruz. Built by team **Coda Nova**, the analysis surfaces actionable sustainability insights from global water usage trends between 2019 and 2022.

🏆 **Selected Project** at the W-code 2.0 closing ceremony.

---

## Table of Contents

- [Key Findings](#key-findings)
- [Visualizations](#visualizations)
- [Tech Stack](#tech-stack)
- [Data Source](#data-source)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Team](#team)
- [License](#license)

---

## Key Findings

- **Agriculture dominates globally:** Agricultural withdrawal accounts for the largest share of freshwater use worldwide, with significant regional variation in sectoral distribution.
- **Turkey breakdown:** Comparative analysis of agricultural, municipal, and industrial usage ratios within Türkiye reveals a pattern consistent with developing economies.
- **Regional contrasts:** East Asia is agriculture-heavy; North America is industry-heavy; Europe shows a more balanced distribution across sectors.
- **Per capita drivers:** Population density and industrialization level are the primary factors explaining per-capita consumption differences across countries.
- **2019–2022 trends:** Temporal analysis highlights emerging stress points in water-scarce regions during this period.

---

## Visualizations

> The notebook includes the following interactive and static charts:

| Chart Type | Library | Description |
|------------|---------|-------------|
| Sunburst chart | Plotly | Hierarchical breakdown by continent → country → sector |
| Treemap | Plotly | Regional water withdrawal share comparison |
| Bar charts | Matplotlib / Seaborn | Sectoral usage by region |
| Time series | Matplotlib | Withdrawal trends 2019–2022 |
| Heatmap | Seaborn | Country-level per capita usage patterns |

To see all visualizations, open the notebook:
👉 [`Global_Water_Usage_Analysis.ipynb`](Global_Water_Usage_Analysis.ipynb)

---

## Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.x |
| Data manipulation | Pandas, NumPy |
| Static visualization | Matplotlib, Seaborn |
| Interactive charts | Plotly (Sunburst, Treemap) |
| Notebook | Jupyter |

---

## Data Source

All data originates from official **FAO AQUASTAT** statistics, covering global water usage between 2019 and 2022.

- **Official database:** [FAO AQUASTAT Main Database](https://www.fao.org/aquastat/en/databases/maindatabase)
- **Processed dataset:** [`AQUASTAT Dissemination System.csv`](AQUASTAT%20Dissemination%20System.csv)

---

## Project Structure

```
global-water-usage-analysis/
├── AQUASTAT Dissemination System.csv   # Raw dataset from FAO
├── Global_Water_Usage_Analysis.ipynb   # Main analysis notebook
├── requirements.txt                    # Python dependencies
└── README.md
```

---

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation

```bash
# Clone the repository
git clone https://github.com/elifyesilyurt/global-water-usage-analysis
cd global-water-usage-analysis

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook Global_Water_Usage_Analysis.ipynb
```

### Dependencies

```
pandas
numpy
matplotlib
seaborn
plotly
jupyter
```

---

## Team

| Name | Role | LinkedIn |
|------|------|----------|
| Elif Yeşilyurt | Data Analyst | [linkedin.com/in/elifyesilyurtt](https://www.linkedin.com/in/elifyesilyurtt/) |
| Ahsen Öztürk | Data Analyst | [linkedin.com/in/ahsen-ozturk](https://www.linkedin.com/in/ahsen-ozturk/) |
| Esmahan Didinir | Data Analyst | [linkedin.com/in/esmahan-didinir](https://www.linkedin.com/in/esmahan-didinir/) |
| Sedef Çakmak | Data Analyst | [linkedin.com/in/sedef-cakmak](https://www.linkedin.com/in/sedef-cakmak/) |

Special thanks to our instructor **[Müşerref Özkan](https://www.linkedin.com/in/muserrefozkan/)** for her mentorship throughout the program.

*W-code 2.0 · Ford Otosan Gelecek Hayalim × Kodluyoruz · Team Coda Nova*

---

## License

MIT © 2026 Coda Nova — Elif Yeşilyurt, Ahsen Öztürk, Esmahan Didinir, Sedef Çakmak

---

> 🇹🇷 [Türkçe Dokümantasyon](docs/README_TR.md)
