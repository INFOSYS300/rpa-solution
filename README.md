# Project Overview

This project aims to automate the analysis of movies to aid in the risk assessment of future movie projects. The RPA-based solution scans the box office movies from the previous month and provides their domestic and worldwide grosses alongside studio, director and producer information. The solution also provides information on the highest-grossing movies for each director who had a film in the box office list.

Our GitHub repository for this project can be viewed [here](https://github.com/INFOSYS300/rpa-solution).

# Prerequisites

- Windows OS
- Google Chrome
- Microsoft Edge
- UI Path

# How To Run

1. Open up the `DirectorInformation.xaml` file in UI Path.
2. Click the arrow by `Debug File` at the top left-hand corner of the UI Path window and select `Run`.
3. Wait for the process to finish.
4. Once the process is completed, the two spreadsheets are available in the `output-spreadsheets` folder. The first spreadsheet, `movie-information`, contains the title, the domestic and worldwide gross, studio, director and producer details for each movie at the box office for the last month. The second spreadsheet, `director-gross-information` contains the top five highest-grossing films for each director found in the first spreadsheet, sorted by highest worldwide gross.
