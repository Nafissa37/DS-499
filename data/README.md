Source of data: [Pittsburgh Trees](https://catalog.data.gov/dataset/city-of-pittsburgh-trees)

This dataset was obtained from Data.gov and contains information about trees under the supervision of The City of Pittsburgh Department of Public Works Forestry Division. The dataset has 45709 rows and 59 columns and was last updated in 2020.

Each row in this dataset represents a single tree in a specific location within Pittsburgh, Pennsylvania, along with various characteristics, conditions, and the environmental and economic benefits it provides. The data includes information about the tree's physical dimensions, its surroundings, the type of benefits it offers (like stormwater management, property value increase, energy savings, air quality improvement, and CO2 sequestration), and geographic and administrative details (like its location by neighborhood, council district, and other local divisions).

Here is a table of the variables in this dataset:

| Variable                                  | Description 
|:------------------------------------------|:--------------------------------
| `_id`                                     | Unique identifier for the tree (internal use) 
| `id`                                      | Unique identifier for the tree record 
| `address_number`                          | Number of the address where the tree is located 
| `street`                                  | Street name where the tree is located 
| `common_name`                             | Common name of the tree species 
| `scientific_name`                         | Scientific name of the tree species 
| `height`                                  | Height of the tree in feet 
| `width`                                   | Width of the tree in feet 
| `growth_space_length`                     | Length of the space available for the tree's growth in feet 
| `growth_space_width`                      | Width of the space available for the tree's growth in feet 
| `growth_space_type`                       | Type of area where the tree is growing (e.g., Well or Pit, Tree Lawn, etc.)
| `diameter_base_height`                    | Diameter of the tree trunk measured at base height in inches
| `stems`                                   | Number of stems the tree has 
| `overhead_utilities`                      | Indicates whether there are overhead utilities (power lines) near the tree 
| `land_use`                                | Land use category where the tree is planted (e.g., residential, commercial) 
| `condition`                               | Health condition of the tree (e.g., Very Good, Good, Fair, etc.) 
| `stormwater_benefits_dollar_value`        | Monetary value of stormwater benefits provided by the tree (in dollars), ie the tree acting as a drainage system or for flood management 
| `stormwater_benefits_runoff_elim`         | Volume of stormwater runoff absorbed by the tree (in gallons)
| `property_value_benefits_dollarvalue`     | Monetary value of the increase in property value due to the tree (in dollars) 
| `property_value_benefits_leaf_surface_area`| Leaf surface area contributing to property value benefits (in square feet) --Trees with larger leaf surface areas can provide more benefits, such as improving air quality, providing shade, and better aesthetic, etc.
| `energy_benefits_electricity_dollar_value`| Monetary value of electricity savings due to the tree (in dollars) -- trees can provide shade and cooling, which can reduce the need for air conditioning, etc.
| `energy_benefits_gas_dollar_value`        | Monetary value of gas savings due to the tree (in dollars) -- trees can help reduce heating costs by providing insulation in colder months, leading to lower gas consumption for heating
| `air_quality_benfits_o3dep_dollar_value`  | Monetary value of Ozone deposition benefits provided by the tree (in dollars) 
| `air_quality_benfits_o3dep_lbs`           | Amount of Ozone deposited by the tree (in pounds) 
| `air_quality_benfits_vocavd_dollar_value` | Monetary value of VOC (Volatile Organic Compounds such as Benzene) avoidance benefits due to the tree (in dollars) 
| `air_quality_benfits_vocavd_lbs`          | Amount of VOC (Volatile Organic Compounds such as Benzene) avoided by the tree (in pounds) 
| `air_quality_benfits_no2dep_dollar_value` | Monetary value of Nitrogen Dioxide deposition benefits provided by the tree (in dollars) -- e.g. NO2 is used in the making of fertilizers 
| `air_quality_benfits_no2dep_lbs`          | Amount of Nitrogen Dioxide deposited by the tree (in pounds) 
| `air_quality_benfits_no2avd_dollar_value` | Monetary value of Nitrogen Dioxide avoidance benefits due to the tree (in dollars) 
| `air_quality_benfits_no2avd_lbs`          | Amount of Nitrogen Dioxide avoided by the tree (in pounds) 
| `air_quality_benfits_so2dep_dollar_value` | Monetary value of Sulfur Dioxide deposition benefits provided by the tree (in dollars) 
| `air_quality_benfits_so2dep_lbs`          | Amount of Sulfur Dioxide deposited by the tree (in pounds) 
| `air_quality_benfits_so2avd_dollar_value` | Monetary value of Sulfur Dioxide avoidance benefits due to the tree (in dollars) 
| `air_quality_benfits_so2avd_lbs`          | Amount of Sulfur Dioxide avoided by the tree (in pounds) 
| `air_quality_benfits_pm10depdollar_value` | Monetary value of PM10 (tiny particulate matters that could come from dust, smoke, vehicle emissions, etc.) deposition benefits provided by the tree (in dollars) 
| `air_quality_benfits_pm10dep_lbs`         | Amount of PM10 deposited by the tree (in pounds) 
| `air_quality_benfits_pm10avd_dollar_value`| Monetary value of PM10 avoidance benefits due to the tree (in dollars) 
| `air_quality_benfits_pm10avd_lbs`         | Amount of PM10 avoided by the tree (in pounds) 
| `air_quality_benfits_total_dollar_value`  | Total monetary value of air quality benefits provided by the tree (in dollars) 
| `air_quality_benfits_total_lbs`           | Total amount of pollutants deposited or avoided by the tree (in pounds) 
| `co2_benefits_dollar_value`               | Monetary value of CO2 benefits provided by the tree (in dollars) 
| `co2_benefits_sequestered_lbs`            | Amount of CO2 sequestered by the tree (in pounds) 
| `co2_benefits_sequestered_value`          | Monetary value of CO2 sequestered by the tree (in dollars) 
| `co2_benefits_avoided_lbs`                | Amount of CO2 avoided by the tree (in pounds) 
| `co2_benefits_avoided_value`              | Monetary value of CO2 avoided by the tree (in dollars) 
| `co2_benefits_decomp_lbs`                 | Amount of CO2 released through tree decomposition (in pounds) 
| `co2_benefits_maint_lbs`                  | Amount of CO2 released due to tree maintenance (in pounds) 
| `co2_benefits_totalco2_lbs`               | Total amount of CO2 stored or avoided by the tree (in pounds) 
| `overall_benefits_dollar_value`           | Overall monetary value of all benefits provided by the tree (in dollars) 
| `neighborhood`                            | Neighborhood where the tree is located 
| `council_district`                        | Council district where the tree is located 
| `ward`                                    | Ward where the tree is located 
| `tract`                                   | Census tract where the tree is located 
| `public_works_division`                   | Public works division responsible for the tree 
| `pli_division`                            | Department of Permits, Licenses, and Inspections division responsible for the tree 
| `police_zone`                             | Police zone where the tree is located 
| `fire_zone`                               | Fire zone where the tree is located 
| `latitude`                                | Latitude coordinates of the tree 
| `longitude`                               | Longitude coordinates of the tree 
| `diameter_base_height`                    | Diameter of the tree at base height (in inches) -- ie the diameter of the tree measured at a certain height (usually at the base or 4.5 feet above ground) to estimate its size and age






 



