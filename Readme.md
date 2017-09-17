Interactive, Bespoke Visualization

Part 2 gives deatails about the distribution of IMLS grants, and what do these grants do?

The dataset is be the IMLS discretionary grants database. These grants include information about the topic of the grant, the institution that received it, its duration, and a few other pieces of data. You may also find useful and interesting data (especially related to zip codes and economic factors) at FRED.

A few of the concepts that are explored:

What types of grants are supported by IMLS?
How are these grants distributed across the United States? Are they particularly clustered in certain states?
Is there a relationship between the economic factors in a zip code and the grants from IMLS?

System for Receiving New Data

A function which will either produce a visualization (either static or interactive) that provides an overview of the data. This may mean applying heuristics to the data to guess at different possible interesting characteristics. This function accepts a pandas dataframe.

The data will have eight columns:

Name
Date
Latitude, longitude
At least 1 Categorical label
At least 3 Quantitive columns


Narrative Report Around a Dataset


The output is in the form of an "infographic." This includes the visualization, narrative text, and design to convey a story.
