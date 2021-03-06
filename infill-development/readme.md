# [Share of New Development Occurring in Highly and Partially Infill Supportive Areas](https://www.cmap.illinois.gov/2050/indicators/infill-development)

This indicator uses the Northeastern Illinois Development Database (NDD) to measure the cumulative share of development that occurs in the region’s highly and partially infill supportive areas. This measure addresses a critical element of ON TO 2050: encouraging development in existing communities where infrastructure to support it is already in place while also avoiding the expansion of new infrastructure with long-term maintenance costs. Developments that are completed or under construction will be tracked. For this indicator, the term “development” is used in a general sense to include both new development and redevelopment of existing uses. Residential and non-residential development will be tracked separately.

**Note:** The methodology for this indicator has been slightly modified from what was included in ON TO 2050. The original queries of the NDD database accidentally included developments that were known to be complete, but which did not have associated completion dates, meaning they may have been completed outside the date range of the intended query. The targets were based on the old methodology, and will likely be revised when ON TO 2050 is updated.

### infill-development.csv

Header | Definition
-------|-----------
`YEAR_RANGE` | Range of observation years
`END_YEAR` | Last year of observation range
`PCT_SUPPORTIVE_RES_INFILL` | Percentage of new residential units developed since 2015 located within highly and partially infill supportive areas
`PCT_SUPPORTIVE_NONRES_INFILL` | Percentage of new non-residential square footage developed since 2015 located within highly and partially infill supportive areas
`ACTUAL_OR_TARGET` | `Actual` if the record is from observed data; `Target` if it is an ON TO 2050 target

**Source:** CMAP’s Northeastern Illinois Development Database (NDD)

**Geography:** Seven-county CMAP region

---

# [Share of New Infill Development Occurring in Economically Disconnected Areas](https://www.cmap.illinois.gov/2050/indicators/infill-development#InclusiveGrowth)

Infill development and land use patterns are crucial to promoting economic growth in many [economically disconnected and disinvested areas (EDAs)](https://www.cmap.illinois.gov/2050/maps/eda) and in connecting the region’s EDA residents to economic opportunity. As a kindred indicator, ON TO 2050 will track the share of new infill development occurring in EDAs. Roughly forty percent of the region’s population lives in EDAs. However, EDAs received a disproportionately low share of new infill development between 2000 and 2015. CMAP recommends increased infill development in EDAs to increase efficient use of limited resources and help these communities grow.

**Note:** The methodology for this indicator has been slightly modified from what was included in ON TO 2050. The original queries of the NDD database accidentally included developments that were known to be complete, but which did not have associated completion dates, meaning they may have been completed outside the date range of the intended query.

### infill-development-in-edas.csv

Header | Definition
-------|-----------
`YEAR_RANGE` | Range of observation years
`END_YEAR` | Last year of observation range
`PCT_RES_INFILL_EDA` | Share of new infill residential units within EDAs
`PCT_RES_INFILL_NOT_EDA` | Share of new infill residential units *not* within EDAs
`PCT_NONRES_INFILL_EDA` | Share of new infill non-residential square footage within EDAs
`PCT_NONRES_INFILL_NOT_EDA` | Share of new infill non-residential square footage *not* within EDAs
`ACTUAL_OR_TARGET` | `Actual` if the record is from observed data; `Target` if it is an ON TO 2050 target

**Source:** CMAP’s Northeastern Illinois Development Database (NDD)

**Geography:** Seven-county CMAP region (divided into EDAs vs. the rest of the region)
