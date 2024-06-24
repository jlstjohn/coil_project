# Global Power Plant Database Exploration

University of Denver Partners: Jesse St. John, Thomas Beadle

Silesian University of Technology Partners: Marta Daszkiewicz, Ola, Konrad, Bartek

## Motivation:

As it has become more and more apparent that humans have a direct impact on climate change, the need for reliable and evironmentally sustainable power to support modern society has become a major focus of research.

## Research Question:

Our research question that we initially set out to solve was: Where are there additional opportunities for renewable energy?

As we explored and dug into the data provided by this dataset, we found this question to be difficult to answer directly. This is partly due to the information provided by the dataset overall. The Global Power Plant Dataset seems more suited to questions geared towards questions involving amount of energy generation than exploring possible additional energy resources, although this is not a bad place to start to get an idea of the layout of current existing resources. The gaps in available data (as noted by the authors and data collectors) also hinder exploration into additional renewable resources.

Thus, we explored whether HDI and population had any correlation with renewable energy fuel source use by country. This was something we hadn't seen done elsewhere. We also looked at what other factors could impact where renewable opportunities could be explored from within the dataset.

## Conclusion:

While our exploration into HDI and its possible affect on type of fuel source yielded no correlation. Most of the valuable informative resulted from a deeper look at the dataset itself, utilizing various visualization methods.

The current use of non-renewable fuel sources is deeply entrenched within our society. The two nations (USA and China) that produce the most energy, far outproduce any other nation and do so with largely non-rewnewable resources. While the impact of developed countries switching to renewable sources will be the greatest, opportunities also exist for smaller countries to develop in a more sustainable way.

# Notes:

To view the final Jupyter Notebook presented by Thomas and Jesse for University of Denver's Data Science Tools 1 course please view the 'gpp_final.ipynb' file.

Directory Explanation:
- data folder:
  - README.txt
  - RELEASE_NOTES.txt
  - .ipynb_checkpoints folder: contains README-checkpoint.txt
  - A_Global_Database_of_Power_Plants.pdf: in depth description of data set and how it was collected/compiled
  - Estimating_Power_Plant_Generation_in_the_Global_Power_Plant_Database.pdf: technical note documenting methods used to estimate annual electriciy generation
  - global_power_plant_database.csv: CSV DATA FILE
- Initial data exploration was completed by all members in various stages (together and separately) and can be seen in the following three files in the main directory:
  - null_overview.ipynb
  - renewable_exploration.ipynb
  - main.ipynb
- global_power_plant_project folder: final stages of compiling/visualizing data
  - README.txt
  - renewable_exploration.ipynb
  - global_power_plant_database.csv
  - HDR23-24_Composite_indices_complete_time_series.csv: additional data brought in
  - API_SP.POP.TOTL_DS2_en_csv_v2_237218.csv: additional data brought in
  - GPP_Merged_Data.csv: merged csv data file
  - gpp_final.ipynb
