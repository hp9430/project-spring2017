Interactive, Bespoke Visualization

Concept: What is the distribution of IMLS grants, and what do these grants do?

Your dataset will be the IMLS discretionary grants database. These grants include information about the topic of the grant, the institution that received it, its duration, and a few other pieces of data. You may also find useful and interesting data (especially related to zip codes and economic factors) at FRED.

There are several frameworks you can use to do this. The three that we have discussed in detail in class have been using the IPython widgets interface to build small, exploratory visualizations, the Bokeh framework and Plotly. You may not use Tableau to build this visualization. If there is another framework you would like to use, please ask.

A few of the concepts that you may explore:

What types of grants are supported by IMLS?
How are these grants distributed across the United States? Are they particularly clustered in certain states?
Is there a relationship between the economic factors in a zip code and the grants from IMLS?
Generate from this data either a notebook that can be executed, a python script that can be executed, or a plotly dashboard that can be accessed. If you utilize plotly, at lease some of the plotly setup must be in a python script.

System for Receiving New Data

Concept: Given limited information about a dataset, what types of all-purpose visualizations can you construct to provide an overview of the data?

You will build a function which will either produce a visualization (either static or interactive) that provides an overview of the data. This may mean applying heuristics to the data to guess at different possible interesting characteristics. This function should accept a pandas dataframe.

The data will have at least eight columns:

Name
Date
Latitude, longitude
At least 1 Categorical label
At least 3 Quantitive columns
There will be three sample datasets provided.

Narrative Report Around a Dataset

Concept: From the visualization you constructed in either component 1 or component 2, construct a narrative. You should take the visual output, possibly modifying it (potentially with something like photoshop or gimp) to fit the style of the rest of your text.

Your output should be in the form of an "infographic." This should include the visualization, narrative text, and should be designed to convey a story of your own choosing.

This component will be graded on style of presentation, aesthetics, representation of the data, and breakdown of the information for understanding by lay people.
