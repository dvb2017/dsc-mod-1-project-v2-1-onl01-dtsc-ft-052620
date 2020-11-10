# Movie Reviews and Box Office Success

This README.md file will serve as the main source of information for the repository.  All of the necessary information will be presented in outline format below.

### List of files in repository:

* `presentation.pdf` \- This is a pdf file containing my presentation slides
* `student.ipynb` \- This is the Jupyter notebook containing my code.  
    * Also contains the questions I set out to answer, as well as actionable recommendations.
* `module1_data` \- This is a folder containing the data I used.
    * Please note that this specific folder is referenced in the Jupyter Notebook.
* `module1_graphs` \- This folder contains copies of all the graphs used in my presentation.

### Initial Questions

These are the intial questions that I set out to answer.
1. Do critic reviews correlate with box office success?
2. Do audience reviews correlate with box office success, and how do they compare to critics?
3. Should MPAA rating be considered when trying to make a successful film?

### Visualizations

I am including a few example visualizations below.  The two scatter plots below are plotting review scores against some metric of box office success.  The first uses audience scores and gross revenue, and the second uses critic scores.  Below that is a simple bar chart comparing the correlation values between the previous metrics.  Audience score is represented by the middle and right bars, broken down between all movies and the top ten percent of highest grossing movies, respectively.

![audience-scores](https://github.com/dvb2017/box-office-reviews/blob/master/module1_graphs/gross_audience_10.png)

![critic-scores](https://github.com/dvb2017/box-office-reviews/blob/master/module1_graphs/critic_score.png)

![compare-corr](https://github.com/dvb2017/box-office-reviews/blob/master/module1_graphs/compare_corr.png)

### Answers and Recommendations

1. Critic reviews **did not** have a statistically significant correlation with box office gross.  **We recommend** that the studio does not follow critical trends, as critical success is a poor indicator of box office success.
2. Audience reviews **did** have a statistically significant correlation with gross and profit.  **We recommend** that the studio focus test extensively in order to maximze audience satisfaction.  This has a significant correlation with increased box office returns.
3. **PG-13** movies comprise the largest share of box office gross by far.  **We recommend** that the studio produces PG-13 movies in order to appeal to the largest possible group of moviegoers.
