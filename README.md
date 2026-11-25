# Urban Garden Soil Ecology

### Multi-scale Drivers of Soil Arthropod Communities and Soil Health in Urban Gardens

STAT 204 - Fall 2026 \| Carmen Marshall and Jocelyn Rojas

------------------------------------------------------------------------

## 🪏 Project Overview

Urban community gardens are important agroecological spaces that contribute to local food production, urban biodiversity, and carbon storage through soil stewardship. However, relatively little is understood about how variation in garden characteristics and surrounding landscapes influences below-ground biodiversity and soil health.

This project investigates how **local- and landscape-level variation shapes soil arthropod communities and soil properties** across 15 urban community gardens in the San Francisco Bay Area and Central Coast regions of California.

Soil arthropods, including millipedes, beetles, and ants, contribute to important below-ground processes such as organic matter decomposition, nutrient cycling, and soil structure formation. Understanding the ecological factors that influence these communities can provide insight into the relationships between urban agricultural management, biodiversity, and soil health.

We integrate four data sets to examine how variation in surrounding land cover, garden characteristics, micro-habitats (e.g. garden beds and pathways), and soil properties influences soil arthropod abundance, richness, and functional diversity.\

------------------------------------------------------------------------

## 🐜 Research Questions

Our research examines how local garden characteristics and broader landscape contexts influence below-ground biodiversity and soil health indicators.

**RQ1. Landscape-level influences**

How do different land cover classes surrounding urban gardens influence observed soil arthropod abundance?

**RQ2. Garden-level influences**

How do garden characteristics and micro-habitats influence soil arthropod abundance and richness?

**RQ3. Soil ecological relationships**

How is soil arthropod functional diversity associated with soil properties, including inorganic nitrogen availability and soil density?

------------------------------------------------------------------------

## 📊 Data Set Overview

This project integrates four data sets capturing ecological variation within and across 15 urban community gardens.

| Data Set | Description | Key Variables |
|------------------------|------------------------|------------------------|
| `arthropod` | Soil arthropod taxonomy | Taxonomic groups: class, order, family |
| `soil` | Physical and chemical soil health properties | Inorganic N, bulk density, CBH enzyme |
| `landscape` | Land cover composition within a 250-m buffer surrounding each garden | Open, urban, natural, agricultural land cover |
| `garden` | Local garden characteristics and vegetation complexity | Plant diversity, ground cover, canopy cover, vegetation structure |

------------------------------------------------------------------------

## 🫜 Experimental Design

### Sampling Structure

-   **15 urban community gardens** across three counties in California (Santa Cruz, Santa Clara, and Monterey Counties)
-   Multiple micro-habitats sampled within individual gardens. (3 replicates per micro-habitat per garden)
-   Micro-habitats include garden beds and pathways.
-   Landscape characteristics quantified within a 250-m radius of each garden using data from the National Land Cover Data Base

## 💻 Repository Structure

``` text
STAT204_Final/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── scripts/
│   ├── 01_data_cleaning.R
│   ├── 02_exploratory_analysis.R
│   ├── 02a_eda_carmen.R
│   ├── 02b_eda_jocelyn.R
│   ├── 03_soil_arthropod_models.R
│   ├── 04_soil_health_models.R
│   └── 05_soil_ecology_models.R
│
├── figures/
│
├── outputs/
│
└── STAT204_FINAL.Rproj
```

## 🛠️ Tools & Packages

Analyses are conducted in R using packages for data manipulation, visualization, and statistical modeling.

-   [R](https://www.r-project.org/)
-   [tidyverse](https://www.tidyverse.org/)
-   [ggplot2](https://ggplot2.tidyverse.org/)
-   [lme4](https://cran.r-project.org/package=lme4)
-   [glmmTMB](https://cran.r-project.org/package=glmmTMB)
-   [DHARMa](https://cran.r-project.org/package=DHARMa)
