# TMDb Data Analysis
This project is an end to end data analysis of a tmdb movie dataset containing over 10.000 movie entries that were released between 1960 and 2015.

## Conclusion
This study assesses and analyzes a given TMDb dataset including over 10.000 movie entries and their properties including budget, revenue, average viewer rating, and runtime dating between 1960 and 2015. The dataset has been cleaned and added new columns for success, title length (in characters), and rating groups (derived from vote_average).

The analysis showed, that a positive correlation between popularity and rating, aswell as between success and rating could be seen. The title length however had no significant correlations with other properties of the dataset. By dividing the dataset in the middle into high and low budget movies, I observed that lower budget movies have higher ROIs. Higher budget movies have on average about 4.59 less ROI than lower budget movies. An insprection of the ratings categories by budget and ROI revealed minor differences in the average budgets and strong positive correlations for the ROI. The average ROI for very high ratings (top 25%) is 4.74.

The last 55+ years reveal changing trends related to the average movie runtime, roi, and budget. According to the findings, the yearly average movie runtime, the yearly average roi, and the yearly average budget have all generally decreased.

The analysis of this dataset has been limited by a significant amount of missing or wrong values. Due to the changes that have been conducted to the budget and revenue columns, a majority of data have not been included in some of the analysis and visualizations. Also, some values in the popularity ratings were flawed and unproportional.

## Prerequisite
### Files that are included:
<ul><li><code>report.html</code> - the complete data analysis report</li>
  <li><code>report_w_code.ipynb</code> - a JSON file, formatted for the usage in Jupyter Notebook</li>
  <li><code>environment.yaml</code> - the environment containing the packages and their versions to be used with Anaconda</li>
  <li><code>requirements.txt</code> - all packages and their versions listed in a txt-file</li>
  <li><code>tmdb-movies.csv</code> - the original dataset file</li>
  <li><code>tmdb_movies_edited.csv</code> - the editied dataset file</li></ul>

### Installation:
In order to run the project on <code>Anaconda</code>, you will need to download the files <code>report_w_code.ipynb</code>, <code>environment.yaml</code>, and <code>tmdb-movies.csv</code> and save them in the same directory. Next, you will have to navigate with the <code>Anaconda Prompt</code> to the directory of the files. Create the environment using <code>conda env create -f environment.yaml</code> and activate it with <code>activate py3</code>. Now you can open the notebook by typing in <code>Jupyter Notebook</code> and run the IPYNB file from there.

### Without Installation:
You can just view the complete analysis and the used code from the included HTML file <code>report.html</code> without any prerequisitions.
