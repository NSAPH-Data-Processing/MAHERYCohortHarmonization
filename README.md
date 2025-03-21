
<!-- README.md is generated from README.Rmd. Please edit that file -->

# MAHERYCohortHarmonization

<!-- badges: start -->

<!-- badges: end -->

The Madagascar Health and Environmental Research (MAHERY) cohort
datasets provide a detailed and interdisciplinary understanding of the
relationships between environmental changes, resource use, and human
health in Madagascar. These datasets encompass multiple research
initiatives, including the Northeast, Antongil, HIARA, and
cross-sectional studies, each addressing unique aspects of health and
environmental interactions.

- **Northeast Dataset**: This dataset focuses on communities near
  Maroantsetra in northeastern Madagascar, where local populations
  heavily rely on wild foods for nutrition. The study examines the
  impact of deforestation, biodiversity loss, and hunting on dietary
  intake, nutritional status, and health outcomes. It includes data on
  dietary diversity, disease metrics, and environmental resource
  use\[2\]\[3\].

- **Antongil Dataset**: Established in 2015 along Antongil Bay, this
  dataset evaluates the nutritional value of seafood and the effects of
  different fisheries governance models—traditional management,
  co-management, and marine national parks—on fish catch, seafood
  consumption, and nutritional outcomes. It includes data from 225
  households across five communities\[4\].

- **HIARA Dataset**: Initiated in 2022 in southwestern Madagascar’s Bay
  of Ranobe, this study investigates the impacts of artificial coral
  reef development on fish biomass, fisher livelihoods, nutrition, and
  mental health. It involves longitudinal monitoring of ecological and
  social systems across 14 communities\[1\].

- **Cross-Sectional Studies**: These studies provide snapshots of
  dietary patterns, nutritional status, and socio-economic indicators
  across various regions. They complement the longitudinal datasets by
  offering broader demographic insights\[2\]\[5\].

Together, these datasets form a comprehensive resource for understanding
how environmental changes influence health outcomes in vulnerable
populations.

Sources \[1\] HIARA study protocol: impacts of artificial coral reef
development on …
<https://www.frontiersin.org/journals/public-health/articles/10.3389/fpubh.2024.1366110/full>
\[2\] Cohort Profile: The Madagascar Health and Environmental …
<https://pmc.ncbi.nlm.nih.gov/articles/PMC5837654/> \[3\] Seasonal
trends of nutrient intake in rainforest communities of north …
<https://pmc.ncbi.nlm.nih.gov/articles/PMC10260550/> \[4\] Cohort
Description of the Madagascar Health and Environmental …
<https://www.frontiersin.org/journals/nutrition/articles/10.3389/fnut.2019.00109/full>
\[5\] Cohort Profile: The Madagascar Health and Environmental …
<https://academic.oup.com/ije/article/46/6/1747/3868352> \[6\] The
Madagascar Health and Environmental Research (MAHERY …
<https://pubmed.ncbi.nlm.nih.gov/29040632/> \[7\] Integrating approaches
to study land use change and hotspots of …
<https://www.thelancet.com/journals/lanplh/article/PIIS2542-5196(18)30104-9/fulltext>
\[8\] Madagascar - MAHAY Study 2016, Endline - Microdata Library
<https://microdata.worldbank.org/index.php/catalog/study/MDG_2016_MAHAY-EL_v01_M>
\[9\] Summary of the PERMANOVA to examine the influence … - Figshare
<https://figshare.com/articles/dataset/Summary_of_the_PERMANOVA_to_examine_the_influence_of_explanatory_variables_in_the_variation_of_composition_of_coral_assemblages_/21375118>

This package establishes a pipeline that harmonizes the MAHERY cohort
data across disparate sources and produces a dataset that defines the
MAHERY Cohort for future studies.

## Approach

We will use the following steps to harmonize the MAHERY cohort data:

1.  A comprehensive review of the MAHERY cohort datasets to identify
    common variables and data structures.
2.  Secure identification and procurement of google drive credentials
    and locations (URLS) of each dataset.
3.  Data extraction and cleaning to ensure consistency and compatibility
    across datasets.
4.  Data integration to merge the datasets into a single, harmonized
    dataset.
5.  Data validation to ensure the harmonized dataset is accurate and
    reliable.
6.  Data export to save the harmonized dataset for future studies.

## Installation

You can install the development version of MAHERYCohortHarmonization
like so:

``` r
# FILL THIS IN! HOW CAN PEOPLE INSTALL YOUR DEV PACKAGE?
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(MAHERYCohortHarmonization)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
