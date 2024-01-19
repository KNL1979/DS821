# DS821 - News and Market Sentiment Analytics

# Data Source
The source data for this project is available for download from the following link:

https://huggingface.co/datasets/gfissore/arxiv-abstracts-2021/tree/main

The downloaded file is a zipped JSON file, and you can access it through the provided script. However, due to GitHub's size limit (25 MB) for individual files, users are required to download the source data to their local systems.

Note: Adjust the file path in the script to match the location where you downloaded the data.

# Subset of Data in this Repository
To overcome the size limitation, a random subset of the original dataframe has been added to this repository. This subset consists of 14,295 abstracts/rows, and the associated notebook 'DS821_Exam' can be run on this subset.

The code for generating this subset can be found in the 'misc.' subfolder.

# Additional Code and Exploration
The 'misc.' subfolder includes a code snippet for exploring the 'id' column to aid in the encoding process of abstracts with dates.

Unfortunately, some output cells from the script were closed before uploading this notebook. Due to time constraints, rerunning the script is not an option. An alternative option would be to rerun the script with a much smaller subset, but there's a concern that it might not accurately reflect the results described in the associated paper.


