# 🎯OVERVIEW.
In this checkpoint, I workED on 'The Tunisian flight company: Tunisair' dataset.

# 📢DESCRIPTION.
 The dataset included a historical data of flight delays. My objective is to investigate the flight delays factors.

# ℹ️INSTRUCTION.
Part 1: Data Exploration with Pandas
- Load the provided dataset into a pandas dataframe
- Use pandas to explore the dataset. For example, you might start by using the head() and info() methods to get an overview of the data.
- Look for missing values in the dataset. You can use the isnull() method to identify missing values.
- Use pandas to calculate some summary statistics for the dataset. For example, you might use the describe() method to get summary statistics for the numerical columns in the dataset.

Part 2: Data Exploration with ydata-Profiling
- Use ydata-profiling to generate a report of the provided dataset.
- Look for missing values in the dataset. You can use the report generated by ydata-profiling to identify missing values.
- Look for correlations between different columns in the dataset. You can use the report generated by ydata-profiling to identify correlations between different columns.
- Identify any outliers or unusual values in the dataset. You can use the report generated by ydata-profiling to identify any outliers or unusual values.

Summary
At the end of this exercise, write a summary of your findings. Did you find any interesting patterns or correlations in the data? Were there any issues or challenges you encountered while exploring the dataset? Use your summary to reflect on your experience using pandas and ydata-profiling to explore and understand a new dataset.

# 🛠️🛠️TOOLS USED.
- Anaconda.
- Jupyter Notebook.
- Python.
- Git.
- GitHub.
- VSCode.

```
import pandas as pd
flight_df.info()
flight_df.describe()
```