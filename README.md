# Visualisasi-Data_World-Happiness
# 🌍 World Happiness Interactive Visualization

An interactive and animated data visualization that explores global happiness levels across countries and over time, based on the **World Happiness Report** dataset from the United Nations Sustainable Development Solutions Network (UNSDSN).

---

## 🧠 Project Overview

This visualization enables users to **explore global happiness trends** and understand how economic, social, and health factors contribute to overall well-being in different countries from year to year.

Using interactive and animated visual techniques, users can:
- Compare happiness scores between countries on an **interactive choropleth map**
- Observe trends over time through an **animated line chart**
- Explore details for each country via **hover tooltips and click events**
- Navigate across years using a **slider with smooth transitions**

---

## 🎯 Goals

- Help users understand **global disparities in happiness**
- Visualize **temporal and spatial patterns** in happiness data
- Encourage exploration of how **factors like GDP, life expectancy, and social support** affect happiness

---

## 🗂 Dataset Information

**Dataset:** [World Happiness Report – Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness)  
**Source:** United Nations Sustainable Development Solutions Network (UNSDSN)  
**File Used:** `data/world_happiness.csv`

**Main Columns:**
- `Country` — Country name  
- `Year` — Observation year  
- `Happiness Score` — Overall well-being index  
- `GDP per capita` — Economic indicator  
- `Social Support` — Strength of social connections  
- `Healthy life expectancy` — Health indicator  
- `Freedom` — Freedom to make life choices  
- `Generosity` — Charitable giving  
- `Corruption` — Perceived corruption levels

---

## 🧩 Key Features

| Feature | Description |
|----------|--------------|
| 🌍 **Interactive Map (Choropleth)** | Color-coded world map showing happiness scores per country |
| 🧭 **Hover Tooltips** | Show details such as GDP, social support, and corruption index |
| 📈 **Animated Line Chart** | Displays happiness trends of a selected country across years |
| 🎚 **Year Slider** | Dynamically updates the map and chart for different years |
| 🧮 **Smooth Transitions & Zoom** | Provides an engaging and intuitive data exploration experience |

---

## 🧠 Design Rationale

We chose a **choropleth map** because geographic distribution provides a natural, intuitive understanding of global patterns.  
A **line chart** complements this by revealing **temporal changes** per country.

**Design Choices:**
- **Color Scale:** Sequential from red (low) → yellow (medium) → blue (high) for emotional intuitiveness  
- **Tooltips:** Support *details-on-demand* without visual clutter  
- **Slider & Animation:** Reinforce understanding of changes over time  

**Alternatives Considered:**
- Scatter plot (GDP vs. Happiness) — informative but less spatially meaningful  
- Bar chart comparison — less engaging for temporal exploration  

---

## 🧭 Interactivity & Animation Techniques

- **Dynamic Query Filters:** Adjust year using the slider to dynamically update visuals  
- **Details on Demand:** Hover over countries to see their details  
- **Coordinated Views:** Clicking a country updates the linked line chart  
- **Smooth Transitions:** Animated color changes and chart updates maintain visual continuity  

---

## 👥 Team Members & Responsibilities

| Name | Role | Responsibilities |
|------|------|------------------|
| **Haifan Rahmah** | 🧩 Team Leader & Developer | Data cleaning, D3 integration, animation synchronization |
| **Nur Fitriana Shalihah** | 🎨 UI/UX Designer | Visual design, layout, color scheme, and tooltips |
| **Berliana Mahadewi** | ⚙️ Interaction Developer | Slider, zoom/pan, and map interactivity |
| **Siti Rhofiah** | 📊 Data Analyst & Chart Developer | Line chart implementation, trend analysis |
| **Mirza Helga Prabatanadi** | 🗒️ Documentation & Presentation | Write-up, README, video narration, peer review |

---

## 🛠 Development Process

1. **Data Cleaning & Preparation**  
   Removed missing values and standardized country names across years.  
2. **Base Map Setup**  
   Used [TopoJSON World Atlas](https://github.com/topojson/world-atlas) for the geographic layout.  
3. **D3 Visualization**  
   Implemented choropleth map, line chart, and interactivity.  
4. **Animations**  
   Added smooth transitions when switching years or countries.  
5. **Styling & UI**  
   Applied clean, modern visuals using soft colors and typography.  


---

## 🧾 Development Notes

- **Frameworks:** D3.js v7, TopoJSON v3    
- **Data Loading:** Local CSV file (`data/world_happiness.csv`)  
- **Browser Support:** Chrome, Edge, Firefox  

---

## 🎥 Presentation Video Outline (5 Minutes)

| Section | Duration | Presenter | Content |
|----------|-----------|------------|----------|
| Introduction | 1 min | Haifan | Dataset, project goals, and importance of happiness data |
| Demonstration | 2 min | Member 2 & 3 | Show interactive features (map, slider, animation) |
| Design Decisions | 1.5 min | Member 4 | Visual encoding rationale and findings |
| Reflection & Questions | 0.5 min | Member 5 | Challenges faced and feedback questions |

**Peer Critique Questions:**
1. Are the map interactions and animations intuitive?
2. Does the visualization effectively communicate changes over time?
3. Is the tooltip information clear and helpful?

---

## 📚 References & Credits

- **Dataset:** [World Happiness Report – Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness)
- **Base Map:** [Natural Earth + TopoJSON](https://github.com/topojson/world-atlas)
- **Libraries:** [D3.js](https://d3js.org/), [TopoJSON](https://github.com/topojson/topojson)
- **Inspiration:** NameGrapher & HomeFinder dynamic query interactions

---

## 🧩 Repository Structure

