# replication-materials-javad-e

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6486536.svg)](https://doi.org/10.5281/zenodo.6486536)

Please use `requirements.txt` file to install all the required packages and dependencies for this project by running:
```
pip install -r requirements.txt
```
The presented figures can be replicated by running the ```analysis.ipynb``` notebook.

Data Collection: The three scrapers, gather a collection of ~370 speeches.

# Preliminary Results

Please note that in the following graphs:
- The x axis presents years in the Persian calendar (we are currently in year 1401).
- The y axis corresponds to the mean frequency of the terms related to the topics normalized by speech length.
- The dotted lines indicate Iran's presidential elections.

Through a preliminary analysis, I test the three main hypotheses of the project.
As illustrated in the first graph, attention to economic policies has been significantly increasing over time. We can also observe how presidential elections cause shocks.

![image](https://raw.githubusercontent.com/macs30200-s22/replication-materials-javad-e/main/figures/Screen%20Shot%202022-04-25%20at%2020.06.18.png)


The second hypothesis was about the undemocratic arm of the government shifting its attention from becoming “economically independent”, creating a “resistive economy”, and implementing an “Islamic economy” to more pragmatic policies. Figure 2 provides empirical evidence supporting this argument. Note that 1390 is when the US economic sanctions became very serious.

![image](https://raw.githubusercontent.com/macs30200-s22/replication-materials-javad-e/main/figures/Screen%20Shot%202022-04-25%20at%2020.06.27.png)


Finally, the third hypothesis was that the undemocratic arm is distancing itself from socialism and moving toward free-market policies. The graph presented below contradicts this hypothesis. Looking at the y-axis values, there is no significant change in the trend, and if anything, the trend is certainly not negative.

![image](https://raw.githubusercontent.com/macs30200-s22/replication-materials-javad-e/main/figures/Screen%20Shot%202022-04-25%20at%2020.06.34.png)


The preliminary results presented above is promising but based on a linear analysis of word frequencies. The next step is to implement a tf-idf framework for more accurate results.

