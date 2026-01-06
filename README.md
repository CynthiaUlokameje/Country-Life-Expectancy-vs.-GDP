# Country Life Expectancy vs. GDP-per-Capita

## Intro

This project explores the relationship between **economic growth (GDP per capita)** and **human well-being (life expectancy)** across countries and over time. Using interactive visualizations and multivariate analytics, the project recreates **Hans Rosling’s Gapminder-style visualization** and extends it with **connected scatterplots, multidimensional scaling (MDS), and clustering** to uncover global development patterns.

The goal of this analysis is to demonstrate how countries evolve along wealth–health trajectories, identify similarities across continents, detect outliers, and group countries into meaningful clusters based on long-term trends.

---

## Data Source

The dataset for this project was provided through **Canvas → Homework 3** and is based on historical country-level indicators commonly used in **Gapminder-style analyses**, including:

- GDP per capita  
- Life expectancy  
- Country  
- Year  
- Continent / Subcontinent  

The data was reshaped, standardized, and exported for use in both **Orange** and **Tableau**.

---

## About the Data

The dataset includes the following key attributes:

- **Country** – Individual nation states  
- **Year** – Time dimension used for animation and connected paths  
- **GDP per Capita** – Economic output per person (inflation-adjusted)  
- **Life Expectancy** – Average life expectancy at birth  
- **Continent / Subcontinent** – Geographic grouping variables  

Each country has repeated yearly observations, allowing for **temporal trajectory analysis** rather than single-point comparisons.

---

## Assignment Requirements Addressed

### Part A – Visualization

#### Hans Rosling (Gapminder) Visualization
- Interactive and animated scatterplot in Tableau  
- X-axis: GDP per Capita  
- Y-axis: Life Expectancy  
- Time animation by year  
- Tooltips with country details  

#### Connected Scatterplot
- Each country represented as a connected path over time  
- Filters for **Country**, **Continent**, and **Subcontinent**  
- Highlights how development trajectories differ across regions  

#### Graphics and Text Integration
- Selected representative countries  
- Written explanations connecting visuals to historical and economic context  

---

### Part B – Analytics

#### Feature Set Construction
- Data reshaped from long to wide format  
- Standardization applied prior to distance-based methods  

#### 2-D Projection (MDS)
- Multidimensional Scaling used to project countries into a 2-D similarity space  
- Results exported and visualized in Tableau  

#### Cross-Continental Similarities
- Identification of countries that cluster together despite geographic separation  
- Explanation using connected scatterplots and historical trends  

#### Outlier Detection
- Countries with unusual wealth–health trajectories identified and explained  

#### Clustering
- K-means clustering applied (**k = 6**)  
- Countries grouped based on long-term GDP and life expectancy patterns  

#### Cluster Visualization
- Clusters visualized on the MDS map  
- Summary statistics computed for:
  - Average GDP per capita per year  
  - Average life expectancy per year  

---

## Key Findings

- Countries cluster primarily by **development trajectory**, not geography.  
- High-income countries show steady diagonal paths (simultaneous GDP and life expectancy growth).  
- Resource-rich economies often exhibit **horizontal GDP surges** followed by delayed health improvements.  
- Some wealthy nations (e.g., the U.S.) show **flattening life expectancy** despite continued economic growth.  
- Low-income countries improve at varying speeds depending on conflict, policy, and health infrastructure.  

Overall, the analysis demonstrates that **shared historical paths** explain similarity better than continent alone.

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
- **Orange** – Data preparation, MDS, clustering  
