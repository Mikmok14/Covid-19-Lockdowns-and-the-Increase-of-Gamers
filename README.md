# Consumer Spending Github Folder

This repo is organized as follows.

The "inputs" folder includes the raw dataset and literature used to support the arguments made in the paper.

The "scripts" folder includes an R-script file that cleans and organizes the raw data found in the data folder.
It also includes an R-script file that scrapes the https://steamcharts.com/ website for player-statistics on the 11
chosen games for this paper. If you wish to have more up-to-date statistics, you can run this script file to create
a raw CSV file with new statistics as the website becomes updated with more information. If you want to get the statistics
directly from Steam itself, you can read more about the Steam Web API here: https://steamcommunity.com/dev
Note that the Steam Web API requires a key to be used and keys are only given to Steam users who have spent at least 
$5 on the Steam store at https://store.steampowered.com/

The "output" folder contains the R-data files created and saved using the R-script. 
The "paper" folder includes a pdf of the paper itself, an R-markdown file that the paper is built on, and a references file
includes references to all the literature and packages used in this paper.