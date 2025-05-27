# Pairwise Compare Dash App

This is a Dash App designed to make the experience of comparing records more digestible for end users. Prior to using the app, end users will need a list of IDs and metadata related to those IDs. Workflow is as follows:

* (Optional) Use the initial list of IDs to give a combination list of all IDs (ie, includes 1:4 comparison but not 4:1 comparison)
* Input files with the list of IDs (with an optional column for similarity that can be prior run by the LLM) and a table with relevant metadata to compare against
* Choose columns for comparison and output into the the merged table, which can be filtered, sorted, and exported to Excel (with color formatting intact)
* Click on a row with the radio button to the far left, and get a sleek UI comparison of specified columns that splits up values in terms of unique to an ID or the same (with counts included)
