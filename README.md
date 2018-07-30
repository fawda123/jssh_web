# README

Materials for JSSH analysis website http://162.243.131.102:3838/jssh_web/index.Rmd

## Data

Data from the compiled geodatabase were extracted for exploratory analysis:

* `allfctprs` Pairwise evaluations of year plus habitat variables on S1/S2 density, by watershed and habitat type. Sites averaged within year by watershed, used in `varimp.Rmd`

* `fishdat` spatial data of steelhead and coho salmon surveys, steelhead density is recorded for two size classes (shorter than 75mm, 75mm or longer)

* `habitat` data frame of habitat survey data

* `segment` spatial data for stream segments with fish data

* `stream` spatial data for complete hydrography for the four watersheds with fish and habitat data

Additional data were created for the website analyses:

* `trndhab_prep.RData` preprocessed habitat data for trend analyses at individual sites, used in `saltrends.Rmd`

* `trndst_prep.RData` preprocessed salmonid data for trend analyses at individual sites, used in `haban.Rmd`
