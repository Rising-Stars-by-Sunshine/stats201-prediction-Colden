# Explanation and Prediction Problem Set 2
## Project information
- **Author**: Colden Johnson, Political Economy and Data Science, 2026, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Thank you to Luyao Zhang for her great instruction in class, as well as to Michael Cornell for his help in setting up my virtual machine for this project.
- **Project Summary**: While building toward my final project, I ran into some statistical difficulties on this problem set. For this simple prediction problem, my research aimed to answer to what extent do tweets that are more polarizing see increased reach, as measured through retweets. I queried over 200,000 Tweets from Twitter on the subject of 'Donald Trump' across a timespan of several years to answer this question. However, my results, as validated through multiple machine learning models as well as linear regression, indicated that there is very low correlation between these X and Y variables.

I present two hypotheses for why this may be the case. First, there may genuinely be no relationship between X and Y. Second, I believe taht the sentiment analysis model chosen for the data was not equipped to handle the task. Tweet sentiment analysis is difficult, as not only are Tweets short, but they often have unseen context. As such, I believe I would like to rerun this analysis while incorporating more X variables and better sentiment analysis tools, to refine my conclusion.

## Table of Contents
- data
- code
- spotlight



## Data

![ConfusionMatrix0_PS2](https://user-images.githubusercontent.com/118926209/220028879-892a571a-3638-4630-b51c-ca3ee25107e3.png)
![ConfusionMatrix1_PS2](https://user-images.githubusercontent.com/118926209/220029038-87b8b59e-dd92-4c92-9ce9-3f0759d48db7.png)
![RandomForestRegression_PS2Stats](https://user-images.githubusercontent.com/118926209/220029045-4fe87804-b09e-4b92-b797-99c5d3a367c1.png)


## Code
- Query Data
- Process Data
- Analyze Data
- ...

## Spotlight
- Figures
- Posters
- Slides
- Presentations
- Review articles
- Media appearance

## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

