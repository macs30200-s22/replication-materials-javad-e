# What Are Tehran’s Friday Speeches About? A Temporal Analysis of Economic Topics Presented by the Friday Imams

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6486536.svg)](https://doi.org/10.5281/zenodo.6486536)

Please use `requirements.txt` file to install all the required packages and dependencies for this project by running:
```
pip install -r requirements.txt
```

# Abstract
Commentators have been speculating changes in the views of the unelected arm of the Iranian government. However, these speculations have not been empirically analyzed. Over the past 42 years, Tehran’s 17 Friday Imams have been delivering speeches every week on political, economic, and social topics. Directly appointed by Iran’s Supreme Leader, the Friday Imams are known as the representatives of the unelected arm of the government. In this study, I collect a dataset of over 340 Friday speeches to explore the changes in the economic values and priorities of the unelected arm. I find a significant increase in attention given to economic topics since 2015. Furthermore, there was a sharp rise in the frequency of unpragmatic economic ideas, such as creating a self-sufficient "resistive economy" immediately after the United States and the United Nations Security Council imposed sanctions on Iran. Being highly correlated with economic performance, the popularity of such ideas has been declining since 2013. Finally, it is discovered several turning points in the trends coincide with presidential elections. Although more evidence is required, this final result could be implying the reorientation of the unelected arm as a consequence of the election results.

# Overview of Results
The following graphs illustrate the results of testing the three main hypotheses of the paper
As illustrated in the first graph, attention to economic policies has been significantly increasing over time.

![image](https://github.com/macs30200-s22/replication-materials-javad-e/blob/main/figures/Screen%20Shot%202022-05-24%20at%2020.21.14.png)


The second hypothesis was about the undemocratic arm of the government shifting its attention from becoming “economically independent”, creating a “resistive economy”, and implementing an “Islamic economy” to more pragmatic policies. Figure 2 provides empirical evidence supporting this argument. Note that 1390 is when the US economic sanctions became very serious.

![image](https://github.com/macs30200-s22/replication-materials-javad-e/blob/main/figures/Screen%20Shot%202022-05-24%20at%2020.21.47.png)


Finally, the third hypothesis was that the undemocratic arm is distancing itself from socialism and moving toward free-market policies. The graph presented below contradicts this hypothesis. Looking at the y-axis values, there is no significant change in the trend, and if anything, the trend is certainly not negative.

![image](https://github.com/macs30200-s22/replication-materials-javad-e/blob/main/figures/Screen%20Shot%202022-05-24%20at%2020.21.52.png)


The preliminary results presented above is promising but based on a linear analysis of word frequencies. The next step is to implement a tf-idf framework for more accurate results.

