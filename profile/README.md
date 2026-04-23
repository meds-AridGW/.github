# Quantifying Relationships Between Agriculture and Groundwater Decline in Arid Areas

<p align="center">
  <img src="https://github.com/user-attachments/assets/5b83b9bf-3910-4a2a-995f-b9a6a029d251" width="123" height="123">
</p>


### Project summary:
Groundwater is the primary water source for irrigated agriculture in many arid regions. Due to limited precipitation, water withdrawals in these regions often outpace groundwater recharge, leaving them vulnerable to accelerating groundwater-level declines. This project aims to understand how the expansion of cultivated land and irrigation intensity relate to groundwater-level changes in arid regions of the United States. Satellite imagery offers a way to track agricultural practices and model their relationship to groundwater trends; however, accessing and analyzing data requires specialized software and coding experience, creating a technical barrier that prevents many users. To address this challenge, we develop a reproducible workflow that integrates groundwater-level records with remotely sensed evapotranspiration (ET) and precipitation data. Using ET: Precipitation ratios as a proxy for irrigation intensity, we analyze relationships between water use, seasonality, crop type, and groundwater decline across multiple sites. Statistical analyses, including Spearman’s rank correlation, and visualizations of annual trends are used to quantify these relationships. This project improves understanding of the drivers of groundwater depletion in arid regions while reducing technical barriers to groundwater–agriculture research. The resulting workflow can support organizations such as the Food and Agriculture Organization (FAO), Sustainable Development Goal 6 (SDG 6), and regional groundwater agencies in advancing sustainable water management.

This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/projects/land-use-changes-hyper-arid-areas-experiencing-groundwater-decline) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu), University of California, Santa Barbara

### Repositories in this Organization
-    [ET_GW_analysis_workflow](https://github.com/meds-AridGW/GW-depth-data-exploration): This repository is used to create a reproducible workflow that integrates open-source evapotranspiration (ET), groundwater, precipitation, aridity index, National agricultural (cultivated and non-cultivated), and Spearman’s rank correlation. The purpose of this is to find the relationship between agriculture (arid and humid sites) and groundwater decline using ET: Precipitation ratio and groundwater trend (mm/yr).

### Authors
-  Austin Martinez {Github, Website, LinkedIn}
-  Henry Oliver {Github, Website, LinkedIn}
-  Marie Tolteca {Github, Website, LinkedIn}
-  Richard Montes Lemus {Github, Website, LinkedIn}

### Client/Advisor
-    Dr. Scott Jasechko

### Data Source
<img width="714" height="397" alt="Screenshot 2026-04-23 at 11 52 26 AM" src="https://github.com/user-attachments/assets/e2e0a229-4761-47de-bebf-9a4f7205c970" />

### References
-  Boryan, C., Yang, Z., Mueller, R., Craig, M., 2011. Monitoring US agriculture: the US Department of Agriculture, National Agricultural Statistics Service, Cropland Data Layer Program. Geocarto International, 26(5), 341–358.

-  Boryan, C., Yang, Z., Willis, P., 2014. US geospatial crop frequency data layers. Third International Conference on Agro-geoinformatics (Agro-geoinformatics 2014), August 11-14, 2014, Beijing, China.

-  Cherry, M. L., & Johnson, Z. C. (2024). Long-term monotonic trends in aquifer and regional groundwater metrics in the United States through 2020 (Data release). U.S. Geological Survey. https://doi.org/10.5066/P1SMQRLG

-  Climate Hazards Center. (2025). Climate Hazards Center Infrared Precipitation with Stations 		(CHIRPS) version 3 [Data set]. https://doi.org/10.15780/G2JQ0P

-  Helsel, D.R., Hirsch, R.M., Ryberg, K.R., Archfield, S.A., and Gilroy, E.J., 2020, Statistical methods in water resources: U.S. Geological Survey Techniques and Methods, book 4, chap. A3, 458 p., https://doi.org/10.3133/tm4a3. [Supersedes USGS Techniques of Water-Resources Investigations, book 4, chap. A3, version 1.1.]

-  Jasechko, S., Seybold, H., Perrone, D., Fan, Y., & Shamsudduha, M. (2024). Groundwater level drawdown in unconfined aquifers worldwide. Nature, 625, 550–556. https://doi.org/10.1038/s41586-023-06879-8

-  Myneni, R., Knyazikhin, Y., & Park, T. (2021). MODIS/Terra Leaf Area Index/FPAR 8-Day L4 Global 500m SIN Grid V061 [Data set]. NASA Land Processes Distributed Active Archive Center. https://doi.org/10.5067/MODIS/MOD15A2H.061 Date Accessed: 2026-01-01 https://doi.org/10.5067/MODIS/MOD15A2H.061

-  National Centers for Environmental Information. (n.d.). Global Precipitation Climatology Project (GPCP) daily precipitation analysis climate data record (CDR) [Data set]. National Oceanic and Atmospheric Administration. https://doi.org/10.7289/V5RX998Z

-  Melton, F., Huntington, J., Grimm, R., et al. (2021). OpenET: Filling a critical data gap in water management for the Western United States. Journal of the American Water Resources Association. https://doi.org/10.1111/1752-1688.12956

-  U.S. Geological Survey. (n.d.). Arizona groundwater exploration (AZ-AGEx) database. https://rconnect.usgs.gov/az-agex/

-  U.S. Geological Survey. (n.d.). USGS 345325119365603. Groundwater data for California: Cuyama Valley. National Water Information System. https://waterdata.usgs.gov/monitoring-location/USGS-345325119365603

-  U.S. Geological Survey. (n.d.). USGS 363310116294001. Groundwater data for Nevada: Amargosa area. National Water Information System. https://waterdata.usgs.gov/monitoring-location/USGS-363310116294001

-  Zomer, R.J.; Xu, J.; Trabuco, A. 2022. Version 3 of the Global Aridity Index and Potential Evapotranspiration Database. Scientific Data 9, 409. https://www.nature.com/articles/s41597-022-01493-1



### Acknowledgements
We would like to extend our deepest gratitude to our clients and advisors whose support and expertise have made this project possible. Your willingness to guide us, share ideas, provide insightful feedback, and commit precious time has been invaluable in ensuring that our project yields meaningful results while reflecting thoughtful analysis. 

We are especially grateful for our client and faculty advisor: 
Dr. Scott Jasechko, Professor, Bren School of Environmental Science & Management

We also thank the following individuals for their support: 

Bren School: 
-  Dr. Carmen Galaz García, Assistant Teaching Professor
-  Alicia (Allie) Caughman, Teaching Assistant, Ph.D. Student
-  Dr. Ashley Larsen, Associate Professor
-  Andrew (Andy) MacDonald, Assistant Professor

OpenET: 
-  Lydia Bleifuss, Program Manager
-  Alberto Guzman, Senior Software Engineer with NASA Ames Research Center and CSU Monterey Bay through the NASA ARC--CREST agreement.

Jack and Laura Dangermond Preserve:
-  The Nature Conservancy (TNC):
-  Moses Katkowski, Dangermond Preserve Director 
-  Emily Alonso, Dangermond Preserve Visitation Coordinator

