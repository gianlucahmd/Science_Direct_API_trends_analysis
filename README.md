# Science_Direct_API_trends_analysis
iPython notebook to perform analysis on research trends using Science Direct's API

To use this notebook, you need a Science Direct (SD) API key, that you can get for free using their [developers' portal](http://dev.elsevier.com). Make sure you respect their [use policy](http://dev.elsevier.com/policy.html) before using it.

# Possible uses:
This ipynb contains functions to:
* Get and parse SD's .json response based on a specified query, subject and year or years range.
* Get the number of publications for a specific query, subject and year or years range.
* Get the evolution over time of publications for a specific query, subject and years range.
* Fit a logistic function to a timeline to evaluate the state of the innovation diffusion for your query. You can read more about logistic function and diffusion of innovation [here](https://en.wikipedia.org/wiki/Logistic_function#In_economics_and_sociology:_diffusion_of_innovations)
* Get the world distribution of research for a specific query, subject and year or years range.
* Plot all of the above using plot.ly Python API. You'll need a plot.ly account and API key to use the plotting code used here.

# Notes:
The notebook contains queries to look for AI academic research trends as an example.
