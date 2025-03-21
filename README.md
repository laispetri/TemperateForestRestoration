# Data from: Successful recovery of native plants post-invasive removal in forest understories is driven by native community features

The files in DRYAD allow readers to run models to reproduce results and figures of the paper "Successful recovery of native plants post-invasive removal in forest understories is driven by native community features", published in Ecological Applications (https://doi.org/10.1002/eap.70012).

The code to reproduce results and figures can be found at (https://github.com/laispetri/TemperateForestRestoration.git)

## Description of the data and file structure

The code was build in RMarkdown. All packages needed are listed in the beginning of code, along with extra information on how to organize folders within the working directory.

Here is the description of the CSV files:

* "data.csv": ID = unique identifier per observation (integer); forest\_stand = site (character); plot = plot original number (integer); subplotOriginal = treatment number [one-time removal/multi-year removal = 1/7 - natural regeneration; 3/9 - forbs and grasses added; 4/10 - forbs added] (integer); Cover2019 = native percent cover in 2019 (double); Cover1 = native percent cover in 2020 (double); Cover2 = native percent cover in 2021 (double); Cover3 = native percent cover in 2022 (double); RichNJN1 = native richness in June of 2020 (integer); RichNJN2 = native richness in June of 2021 (integer); RichNJN3 = native richness in June of 2022 (integer); smJL1 = volumetric soil water content (%) in July of 2020 (double); smJL2 = volumetric soil water content (%) in July of 2021 (double); smJL3 = volumetric soil water content (%) in July of 2022 (double); forbAG1 = native forb percent cover in August of 2020 (double); grassAG1 = native graminoids percent cover in August of 2020 (double); woodyAG1 = native woody percent cover in August of 2020 (double); forbAG2 = native forb percent cover in August of 2021 (double); grassAG2 = native graminoids percent cover in August of 2021 (double); woodyAG2 = native woody percent cover in August of 2021 (double); SLA61 = native community weighted mean of specific leaf area in June of 2020 (double); SLA62 = native community weighted mean of specific leaf area in June of 2021 (double); SLA63 = native community weighted mean of specific leaf area in June of 2022 (double); light1 = available % light in peak grenness of 2020 (double); light2 = available percent light in peak grenness of 2021 (double); light3 = available % light in peak grenness of 2022 (double); subplot = ordered subplot number based on subplotOriginal (integer).
* "richnessN.csv": forest\_stand = site (character); plot = plot original number (integer); subplot = treatment number [one-time removal/multi-year removal = 1/7 - natural regeneration; 3/9 - forbs and grasses added; 4/10 - forbs added] (integer); year = year in which the data was collected (integer); PctCover\_100\_N = native percent cover (double); Richness\_N = number of native species within a plot (integer).
* "coverI2019.csv": forest\_stand = site (character); plot = plot original number (integer); subplot = treatment number [one-time removal/multi-year removal = 1/7 - natural regeneration; 3/9 - forbs and grasses added; 4/10 - forbs added] (integer); CoverI2019 = invasive percent cover within a subplot (double); year = year in which the data was collected (integer).
* "dominantI.csv": plot = plot original number (integer); subplot = treatment number [one-time removal/multi-year removal = 1/7 - natural regeneration; 3/9 - forbs and grasses added; 4/10 - forbs added] (integer); year = year in which the data was collected (integer); sppName = invasive species with the largest percent cover within a subplot (character).
* "traitsSeedMix.csv": Species\_name: native species added via seeding (character); Presence = present [1] or absent [0] across all sampled subplots x years(integer); frequency = number of times a species was recorded across all sampled subplots x years (integer); MixType = type of seed mix added (character); SLA\_mm2.mg = species specific leaf area value in mm2.mg (double); SLAmean = mean specfic leaf area of all native species recorded across all sampled subplots x years (double); SLAsd = standard deviation of specfic leaf area of all native species recorded across all sampled subplots x years(double).
* "traitsDiversity.csv": acronym: species acronym (character); SLA\_mm2.mg = specific leaf area value in mm2.mg.
* "VPD.csv": ID = unique identifier (integer); VPD\_cumsum = cumulative sum of vapor pressure deficit from May to August; year = year the data was collected.

Cells with missing data are filled with NAs.

## Sharing/Access information

All four CSV files needed to run this code can be found in DRYAD [https://doi.org/10.5061/dryad.mpg4f4r5w](https://doi.org/10.5061/dryad.mpg4f4r5w).

Please, cite the original paper (https://doi.org/10.1002/eap.70012) if using any data or code shared here.
