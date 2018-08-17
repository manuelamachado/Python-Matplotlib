
## Python-Matplotlib - The Power of Plots

## Pymaceuticals Inc


Pymaceuticals Inc. is a fictional pharmaceutical company specialized in drug-based, anti-cancer pharmaceuticals. In their most recent efforts, they've since begun screening for potential treatments to squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

Given data from their most recent animal study. In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. I analyzed the data to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.

### Analyzes:

* Created a scatter plot that shows how the tumor volume changes over time for each treatment.
* Created a scatter plot that shows how the number of [metastatic](https://en.wikipedia.org/wiki/Metastasis) (cancer spreading) sites changes over time for each treatment.
* Created a scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
* Created a bar graph that compares the total % tumor volume change for each drug across the full 45 days.

### Applications & Tools:

Utilized the Pandas Library and the Jupyter Notebook.
Utilized the Matplotlib and Seaborn libraries.

# Results and Conclusions: 

1. The study analyzed ten different drugs and their effects on tumor volume in a sample of 250 mice.  We then looked at four drugs in particular (Capomulin, Infubinol, Ketapril, and Placebo) over a 45 day span.  The Ketapril, Infubinol, and Placebo all experienced average increases of tumor volume over 45% while the Capomulin showed a reduction of 19%.

2. Ketapril resulted in the largest number of meatstatic sites at the conclusion of our trial, overtaking the Placebo during the very last days.  Capomulin resulted in the lowest number of metastatic sites throughout the 45 days.

3. Capomulin also proved to be the best treatment when considering survivability with 21 mice living through our trial.  Only 9 mice on the Infubinol treatment survived the duration of the trial.

After the 45 day trial, Capomulin is clearly the best treatment option.  Capomulin was the only drug with a reduction in tumor volume, had the highest survivability rate and the best outcomes on metastatic spread.  No other drug appears to be a viable alternative based on our data.

It is important to mention some limitations of the research such as the credibility of the results based on the small sample size (25 mice per drug).  Without leveraging hypothesis testing we cannot make any significant conclusions.




