# What Are Tehran’s Friday Speeches About? A Temporal Analysis of Economic Topics Presented by the Friday Imams

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6486536.svg)](https://doi.org/10.5281/zenodo.6486536)

The code is written in Python 3.9.7. Please use `requirements.txt` file to install all the required packages and dependencies for this project by running:
```
pip install -r requirements.txt
```
To replicate results, start by running the scrappers and cleaning code in ``` scrape and clean ``` directory. Then you can run the topic modeling, TF-IDF and word count files placed in the ``` analysis ``` directory.

To cite the data or code, please use Zenodo DOI.

# Abstract
Commentators have been speculating changes in the views of the unelected arm of the Iranian government. However, these speculations have not been computationally analyzed. In this study, I analyze the speeches delivered by Tehran’s Friday Imams. Directly appointed by Iran’s Supreme Leader, the Friday Imams are known as the representatives of the unelected arm of the government. Over the past 42 years, Tehran’s 17 Friday Imams have been delivering speeches every week on political, economic, and social topics. I collect a dataset of over 340 Friday speeches to explore the changes in the economic values and priorities of the unelected arm. I find that three years after the horrific economic downturn begins, attention given to economic topics started to significantly increase in 2015. Furthermore, there was a sharp rise in the frequency of unpragmatic economic ideas, such as creating a self-sufficient “resistive economy” immediately after the United States and the United Nations Security Council imposed sanctions on Iran. Being highly correlated with economic performance, the popularity of such ideas has been declining since 2013. The analysis also indicates that there are significant jumps in the trends coinciding with presidential elections in which Reformist candidates were elected. Although more evidence is required, this finding supports the theory of the reorientation of undemocratic regimes as a consequence of strong social signals. Lastly, I investigate the patterns of how individual Imams with various political inclinations differ from each other with regard to their speeches on economic-related topics.

# Overview of the Results
The following graphs illustrate the results of testing the three main hypotheses of the paper
As shown in the first graph, attention to economic topics has been significantly increasing since 2015. The observed trend is in line with the economic situation. Iran’s horrific economic downturn began in 2012 caused by the United Nations Security Council resolutions and the United States trade sanctions against Iran combined with the drop in oil prices.

![image](https://raw.githubusercontent.com/macs30200-s22/replication-materials-javad-e/main/figures/Screen%20Shot%202022-06-05%20at%2016.52.55.png width="50")


The second hypothesis was about the unelected arm of the government shifting its attention from the unpragmatic ideas of implementing a self-sufficient and "resistive" economy to more pragmatic policies. Figure 2 provides empirical evidence supporting this argument. In the early years of the sanctions when they did not have as many consequences as expected, the government became hopeful that it can build its ideal resistive economy. Hence, the mentions of such topics grew by 600 percent between the years 2011 to 2013. However, as the oil prices went down so too did Iran’s economy. As a consequence, the popularity of these unpragmatic ideas sharply declined to almost zero.

![image](https://raw.githubusercontent.com/macs30200-s22/replication-materials-javad-e/main/figures/Screen%20Shot%202022-06-05%20at%2016.54.53.png)


The third hypothesis was that the unelected arm is distancing itself from socialism and moving toward free-market policies. The graph presented below contradicts this hypothesis. There appears to be no monotonic trend.

![image](https://raw.githubusercontent.com/macs30200-s22/replication-materials-javad-e/main/figures/Screen%20Shot%202022-06-05%20at%2016.54.26.png)

One thought-provoking finding of this study is the effect of presidential elections on the discussed trends. The 2013 and 2017 election years, specified by dotted lines in figure 5, are associated with strong turning points in promoting the idea of a resistive economy and socialist ideas. This observation is potentially linked to the concept of the reorientation of authoritarian regimes. However, more supporting evidence is required to confirm a causal relationship between the presidential elections and turning points in the trends.


