# Analysis of Neighbors Ring Alert data set — January 2021 - May 2022 

## Data

This analysis uses msg_extracts.csv spreadsheets.

The spreadsheets come from the following sources:

- Name of source:
  - msg_extracts.csv: Raw data of Brookhaven PD Neighbors Ring alerts as .msg files.  

## Methodology

The notebook data_analysis_trent.ipynb performs the following analyses:

##### Part 1: Unique number of recipients

- This counts the unique number of recipients that the ring alerts were sent to. 


##### Part 2: Tallies over time (resampling)

- This resamples the data by summarizing over time how many ring alerts were sent to each officer. 


## Outputs

The notebooks output these two csv files: output/resampling_Trent.csv and output/unique_count_Trent.csv.

## Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

- Python 3
- The Python libraries specified in [`requirements.txt`](requirements.txt). You can install them by running `pip install -r requirements.txt`

## Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). The data file in the output/ directory is available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?

Contact Paisley Trent at paisley.trent@gmail.com.
