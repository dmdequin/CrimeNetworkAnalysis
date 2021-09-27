# CrimeNetworkAnalysis

# Network Analysis - ITU 2021 - Group 10

This repository contains the code and data regarding the project in the Network Analysis course at ITU.

### Project Goals
We will be analysing the Crime Network. Tasks include:
• Exploratory analysis to discover network statistics of the data (number of nodes, edges, clustering, degree distribution, etc).
• Formulation of a research question.
• The analysis, results, and interpretation that permit answering the research question.


### Project Code
This project  will work with python and jupyter notebook. NetworkX library is largely used for network exploration.

### Data
The data is a bipartite network of associations between suspects, victims and/or witnesses of crimes in St. Louis in the 1990's. Left nodes represent a person and right nodes represent a crime. Edges connect a person to an invidual crime. Metadata includes names, genders and category of the edge (suspect, victim, witness).

Data are derived from police records, via snowball sampling from five initial homicides.

There are 1380 nodes and 1476 edges in the network.

There are two websites that source the same data: 

https://networks.skewed.de/net/crime

http://konect.cc/networks/moreno_crime/
