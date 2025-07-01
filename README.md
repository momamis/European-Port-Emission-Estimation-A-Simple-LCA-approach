# European-Port-Emission-Estimation-A-Simple-LCA-approach

## Overview
In this project, I conducted a simplified Life Cycle Assessment (LCA) focusing on emissions from container ships during maneuvering and hotelling phases in European ports. Maneuvering refers to the movement of ships within the port area, such as entering, docking, and leaving the berth, while hotelling refers to the time ships spend docked at the port while running auxiliary engines to maintain onboard operations.
Using emission factors and methodology from the EMEP 2023 Guidebook, I calculated the CO₂ emissions generated during these phases. Additionally, I assessed the potential environmental impact of switching from onboard auxiliary engines to shore power (cold ironing) during hotelling. The analysis revealed a significant percentage decrease in CO₂ emissions with the use of shore power, underlining its effectiveness in reducing the carbon footprint of port activities.

![screenshot](https://github.com/momamis/European-Port-Emission-Estimation-A-Simple-LCA-approach/blob/main/emission_by_pollutant.png)

## Steps Taken

- Data collection on navigation from the 2023 EMEP Guidebook.
- Estimation of emission from the main and auxiliary enginges of a medium sized European container ship under the assumption that the main enginge is turned off during hotelling while the auxiliary enginge is mostly inactive during maneuvering .
- Visualization of the amount of pollutants other than carbon dioxide released during maneuvering and hotelling.
- Calculation of carbon dioxide emission from the auxiliary enginge with and without shore power.
- Estimation of reduction in carbon dioxide emission if the enginge were to switch to shore power.

![screenshot](https://github.com/momamis/European-Port-Emission-Estimation-A-Simple-LCA-approach/blob/main/CO2_emission_reduction.png)

## Insights

- NOx seems to account for a huge proportion of air pollution due to maneuvering and hotelling of container ships.
- The amount of carbon dioxide released during the hotelling phase could be reduced by more than 60% if a container ship switches to shore power.
- The findings are in line with the [FuelEU Maritime Regulation](https://transport.ec.europa.eu/transport-modes/maritime/decarbonising-maritime-transport-fueleu-maritime_en).
