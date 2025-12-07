# Biodiversity Intactness Index Change in Phoenix, AZ

## Description 
Maricopa County, the fourth most populous county in the United States, is home to more than half of Arizona's residents and contains the state capital, Phoenix. As of 2022, the county had a population of 4.5 million people and was listed as the fastest-growing county in the U.S., adding nearly 56,000 residents between July 2021 and 2022 (Maricopa County, n.d.). This rapid population growth has contributed to the most significant increase in developed land in the county since at least 2001 (Levitt & Eng, 2021). Consequently, expanding urban sprawl has raised concerns about impacts on biodiversity and ecosystem health in the surrounding areas.

This repository contains the data, code, and figures for a geospatial analysis project using Python based spatial libraries (ex. `geopandas` and `rioxarray`) and open access geospatial datasets. This assignment investigates the impacts of urban sprawl on biodiversity by analyzing Biodiversity Intactness Index (BII) values in the Phoenix county subdivision area for 2017 and 2020. The analysis highlights how urban growth corresponds with changes in biodiversity over time, providing insight into the ecological consequences of expanding urban landscapes. The final output consists of a map illustrating changes in BII across the Phoenix metropolitan area, with an emphasis on areas experiencing biodiversity loss.  


## Contents
This repository is organized as follows and contains: 
- `README.md`: Markdown file detailing repository description, content, structure, data access, and references.

- `.gitignore`: File alerting Git to avoid "unnecessary" files from being committed to the repository. The data folder containing the 2025 TIGER/Line Shapefiles for the County Subdivisions were added to the `.gitignore` to prevent large datasets from being pushed to GitHub. 

- `biodiversty-analysis.ipynb`: Notebook containing the 

```
Biodiversity Intactness Index Change in Phoenix, AZ
├── README.md
├── biodiversty-analysis.ipynb
├── .gitignore
```
    
    
## Data Access
The data utilized in this analysis is not housed in this repository. [In Progress]

## Contributors
This repository is maintained by Vedika Shirtekar as part of the Master of Environmental Data Science program at UC Santa Barbara. This work was completed for the **EDS 220: Working with Environmental Datasets** course at the Bren School of Environmental Science and Management, which provided data access and documentation practices, as well as assignment instructions.



## References

Levitt, Z. and Eng J., (2021, August 11). Where America’s developed areas are growing. The Washington Post. https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/

Maricopa county quick facts. (n.d.). Maricopa County, AZ. Retrieved December 7, 2025, from https://www.maricopa.gov/3598/County-Quick-Facts
