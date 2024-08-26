# Privateer2 trade route calculations 
## Content summary
###
* commodity and route profit calculator
* route distance calculation
* nav point adjacency matrix
* navigation map in gephi format
##
## Content information
###
* file formats currently used: google sheets, csv, gephi and png
* used information provided by the official privateer 2 strategy guide
* the game used for testing is the digital download from GOG.com plus the unofficial patch from wcnews.com
## 
## -------------------
## How to use this repository
###
* **"Priv2 Commodities.xlsx" << THE MAIN FILE** - google sheets document with route calculation, commodity prices, estimated profit, adjacency matrix and data exports for gephi. Link to latest document in google sheets: https://docs.google.com/spreadsheets/d/1ZOjGhJDpJgAbjmIGe3Ixcczv1emhCmAAl9Mf5sv9_hE/edit?usp=sharing
* "Priv2 Commodities - export.csv" - csv exported adjacency matrix of all navigation points (0-225)
* "Priv2 Commodities - export.gephi" - gephi file of imported adjacency matrix showing structure, interconnection and shortest route
* "Priv2_commodity_profit_calc.png" - image file showing how to use the route and profit calculator


## -------------------
### Notes
The profit calculator uses a simple lookup table in the Google Sheets document. The manually entered adjacency matrix in the same sheet is used to create the Gephi graph; there is no other connection between these data sources and it just happens to be stored in the same document.

