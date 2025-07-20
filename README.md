# Reuniting Accessibility Measures with Spatial Interaction Principles

Anastasia Soukhov's sissertation towards a 'Doctor of Philosophy' in Transport Geography (Faculty of Science in the School of Earth, Environment and Society) at McMaster University. Superivised by Antonio Páez.

### Lay Abstract:
One of the primary goals of transportation systems is to connect people with opportunities--such as jobs, essential services and community. However, traditional transportation planning practice has largely emphasized mobility, focusing on metrics like distance traveled or travel time, rather than accessibility (the number of opportunities people can reach). Although researchers have long advocated for a shift from mobility-based approaches to accessibility-focused ones, this transition has yet to be fully realized due to several persistent challenges. A key barrier is methodological: the absence of standardized units for measuring accessibility. This thesis seeks to address this barrier by examining how accessibility methods relate to conventional mobility-based techniques, and by exploring how constraints--adapted from spatial interaction models--can be used to return meaningful units to accessibility values and in accessibility analysis. This is done by reviewing the related spatial interaction modeling and accessibility literature, outlining a family of 'constrained' accessibility measures, and detailing an empirical example of accessible parkland area and population in the City of Toronto.

### Reproducibility of Manuscript
To reproduce the manusript, knit the 'index.Rmd' and a pdf titled 'thesis.pdf' will be produced in the '_book' directory. .index.Rmd knits together all chapters and their required component. Chapters include: 01-chap1.Rmd, 02-chap2.Rmd, 03-chap3.Rmd, 04-chap4.Rmd, 05-chap5.Rmd, 06-conclusion.Rmd. These chapters use figures and some tables created in pre-processing documents stored in the 'data' directory.

The 'figures' subdirectory within the 'data' directory contains all figures used in the manuscript.

### Reproducibility of Data Analysis and Figures/Tables
The manuscript uses 7 .Rmds for data processing, all contained in the 'data' directory. .Rmds 01 through 04 prepare the data for accessibility analysis. Namely, 01-park-origin-prep.Rmd processes (i.e., loads in the data, finds represenstive centroid points, data joins) and saves the origin (DB) and parkland data, 02-od-routing.Rmd and 03-od-routing-pt2.Rmd calculates the travel time from origin DB weighted centroid to all park entrances by all modes using r5r and saves resulting matrices, and 04-selecting-tts.Rmd filters the matrices to unique and shortest travel time origin-park-ID pairs for each mode as well as process the 2022 TTS travel times. 

The remaining files (05-07) are chapter specific. 05-data-prep-for-chp3.Rmd prepares all plots and tables for chp 3, 06-data-prep-for-chp4.Rmd calculates unimodal accessibility and prepares all plots/tables for chp4, 07-data-prep-for-chp5.Rmd calcs multimodal accessibility and preapres all plots/tables for chp 5.
