# **Introduction**

An information gathering application on the basis of 1x1 logging approach

Use case: Syncing slicers across multiple reports

As an initial approach we have started with the following:

1. Check the push dataset compatibility with other sources
   * The push data set can be used along with the other dataset with a combined query approach.
   * We need to check on the auto refresh of the report and how can we pass the selected filter values to the service  
2. Pass the filters on a Power BI Page using 1x1 pixel image logging
3. Get the selected filter values in a measure
4. Have these selected values in other report using the Power BI real-time datasets
5. Create measure to use the filters
6. Check if the filter is selected for single user
