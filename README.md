# Country Life Expectancy vs. GDP-per-Capita 🌍📈

## Overview
This project explores the relationship between **economic growth (GDP per capita)** and **human well-being (life expectancy)** across countries and over time. Using interactive visualizations and multivariate analytics, the project recreates **Hans Rosling’s Gapminder-style visualization** and extends it with **connected scatterplots, multidimensional scaling (MDS), and clustering** to uncover global development patterns.

The goal is to:
- Analyze how countries evolve along **wealth–health trajectories**
- Identify similarities across continents
- Detect outliers in development paths
- Group countries into meaningful clusters based on long-term trends

---

## Data Source
The dataset was provided via **Canvas → Homework 3** and is based on historical country-level indicators commonly used in Gapminder-style analyses.

### Variables Included
- **Country**
- **Year**
- **GDP per Capita** (inflation-adjusted)
- **Life Expectancy**
- **Continent / Subcontinent**

The data was reshaped, standardized, and exported for use in **Orange** and **Tableau**.

---

## About the Data
Each country contains **repeated yearly observations**, enabling **temporal trajectory analysis** rather than static, single-year comparisons.

**Key Attributes**
- `Country` – Individual nation states  
- `Year` – Time dimension used for animation and connected paths  
- `GDP per Capita` – Economic output per person  
- `Life Expectancy` – Average life expectancy at birth  
- `Continent / Subcontinent` – Geographic grouping variables  

---

## Assignment Requirements Addressed

### Part A – Visualization

#### Hans Rosling (Gapminder) Visualization
- Interactive and animated scatterplot in **Tableau**
- X-axis: GDP per Capita  
- Y-axis: Life Expectancy  
- Time animation by year  
- Tooltips with country details  

#### Connected Scatterplot
- Each country represented as a **connected path over time**
- Filters for:
  - Country
  - Continent
  - Subcontinent
- Highlights differences in development trajectories across regions

#### Graphics & Text Integration
- Selected representative countries
- Written explanations linking visuals to historical and economic context

---

### Part B – Analytics

#### Feature Set Construction
- Data reshaped from **long → wide format**
- Standardization applied prior to distance-based methods

#### 2-D Projection (MDS)
- **Multidimensional Scaling (MDS)** used to project countries into a 2-D similarity space
- Results exported and visualized in Tableau

#### Cross-Continental Similarities
- Identification of countries clustering together despite geographic separation
- Explanations supported by connected scatterplots and historical context

#### Outlier Detection
- Countries with unusual wealth–health trajectories identified and analyzed

#### Clustering
- **K-means clustering (k = 6)**
- Countries grouped based on long-term GDP and life expectancy patterns

#### Cluster Visualization
- Clusters displayed on the MDS map
- Summary statistics computed for:
  - Average GDP per capita per year
  - Average life expectancy per year

---

## Key Findings
- Countries cluster primarily by **development trajectory**, not geography
- High-income countries follow steady **diagonal paths** (simultaneous GDP & life expectancy growth)
- Resource-rich economies often show rapid GDP growth with delayed health improvements
- Some wealthy nations (e.g., the **U.S.**) show **flattening life expectancy** despite continued economic growth
- Low-income countries improve at varying speeds depending on conflict, policy, and health infrastructure
- Shared historical paths explain similarity better than continent alone

---

## Running the Project

### Tableau Visualization
1. Open `HW3.twbx` in **Tableau Desktop**
2. Use filters to explore:
   - Countries
   - Continents
   - Subcontinents
3. Play the animation to observe development over time

### Data Files
- `data prep clusters.csv` – Used for clustering analysis  
- `MDS + clusters.csv` – Used to visualize similarity space and cluster membership  

---

## Tech Stack
- **Tableau** – Interactive and animated visualizations  
- **Orange** – Data preparation, MDS, and clustering  

---

## Author
Developed as part of **Homework 3** for exploratory data visualization and multivariate analytics.

---

✨ *Inspired by Hans Rosling’s Gapminder visualizations*  
