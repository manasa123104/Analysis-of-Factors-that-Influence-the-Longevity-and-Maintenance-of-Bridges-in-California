## Analysis of Factors that Influence the Longevity and Maintenance of Bridges in California

This repository contains a project analyzing which factors most strongly influence the **condition, longevity, and maintenance needs of bridges in California**.  
It was developed as an academic / course project and is accompanied by the presentation `AIT614-002 _Team8_Final.pptx`.

---

### Project Objectives

- **Identify key factors** affecting bridge longevity and maintenance in California.
- **Quantify relationships** between bridge attributes (e.g., age, material, traffic, location) and condition/maintenance indicators.
- **Provide insights and recommendations** for infrastructure planning and maintenance prioritization.

---

### Repository Contents

- **`AIT614-002 _Team8_Final.pptx`**: Final project presentation summarizing:
  - Problem statement and motivation.
  - Data sources and preprocessing.
  - Exploratory analysis and modeling approach.
  - Key findings, visualizations, and recommendations.
- **`README.md`**: Project overview and instructions (this file).

> If you add code, notebooks, or data files later (e.g., `.ipynb` or `.py` files), you can update this section to briefly describe each component.

---

### Data (Expected / Typical Sources)

Although raw data is not stored in this repository, this type of project typically uses:

- **National Bridge Inventory (NBI)** data for California.
- **Caltrans / state DOT data** on inspections, maintenance history, and traffic.
- **Geospatial / environmental data**, such as:
  - Seismic zones.
  - Climate / weather exposure.
  - Proximity to coasts, rivers, or corrosive environments.

Common variables include:

- **Structural attributes**: bridge type, material, span length, number of spans.
- **Usage metrics**: average daily traffic, truck percentage.
- **Age and condition**: year built, last rehab, condition ratings.
- **Location & environment**: county, seismic risk, environmental exposure.

---

### Methodology (Typical Workflow)

The analytical workflow for this project generally follows these steps:

1. **Data Collection & Integration**
   - Gather NBI and related datasets for California bridges.
   - Merge multiple sources on common identifiers (e.g., bridge ID).

2. **Data Cleaning & Preparation**
   - Handle missing values, outliers, and inconsistent categories.
   - Create derived features (e.g., bridge age, time since last rehab).

3. **Exploratory Data Analysis (EDA)**
   - Summary statistics and distributions.
   - Visualizations (histograms, boxplots, correlation heatmaps).
   - Comparisons across regions, materials, and age groups.

4. **Modeling / Statistical Analysis**
   - Correlation analysis between features and condition/maintenance indicators.
   - Regression or classification models to predict:
     - Condition ratings, or
     - Probability of needing maintenance/rehabilitation.

5. **Insights & Recommendations**
   - Identify the **most influential factors**.
   - Suggest **prioritization strategies** for maintenance.
   - Discuss **policy and planning implications**.

The details of this workflow are summarized in the PowerPoint presentation.

---

### How to Use This Repository

- **For reviewers / instructors**
  - Start with the presentation `AIT614-002 _Team8_Final.pptx` to understand the motivation, methods, and conclusions.
  - Use this `README.md` as a quick textual overview.

- **For collaborators / future work**
  - Add analysis scripts (e.g., `analysis.ipynb`, `models.py`) and update this README with:
    - Setup instructions (Python version, libraries).
    - How to run the analysis (commands, notebook order).
    - Any data access instructions (e.g., links to external data).

---

### Possible Future Extensions

- **Include code and notebooks** used for data cleaning, EDA, and modeling.
- **Automate data download and preprocessing** from public sources (NBI, Caltrans).
- **Add interactive visualizations** (e.g., dashboards showing bridge risks by region).
- **Extend the analysis** to compare California with other states or to simulate maintenance scenarios.

---
